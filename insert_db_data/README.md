{
  "active": false,
  "connections": {
    "When Executed by Another Workflow": {
      "main": [
        [
          {
            "node": "AI Agent",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "MCP Client": {
      "ai_tool": [
        [
          {
            "node": "AI Agent",
            "type": "ai_tool",
            "index": 0
          }
        ]
      ]
    },
    "AI Agent": {
      "main": [
        [
          {
            "node": "HTTP Request",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Auto-fixing Output Parser": {
      "ai_outputParser": [
        [
          {
            "node": "AI Agent",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    },
    "Structured Output Parser": {
      "ai_outputParser": [
        [
          {
            "node": "Auto-fixing Output Parser",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    },
    "HTTP Request": {
      "main": [
        [],
        []
      ]
    },
    "OpenAI Chat Model": {
      "ai_languageModel": [
        [
          {
            "node": "AI Agent",
            "type": "ai_languageModel",
            "index": 0
          },
          {
            "node": "Auto-fixing Output Parser",
            "type": "ai_languageModel",
            "index": 0
          }
        ]
      ]
    }
  },
  "createdAt": "2025-04-29T16:09:24.611Z",
  "id": "WpgegqVk9wnmBrZT",
  "meta": {
    "templateCredsSetupCompleted": true
  },
  "name": "insert_db_data",
  "nodes": [
    {
      "parameters": {
        "promptType": "define",
        "text": "=id: {{ $json.id }}\n{{ $json.description }}",
        "hasOutputParser": true,
        "options": {
          "systemMessage": "You are an agent responsible for building a valid JSON body to create a new record in a Notion database using its API. You will receive as input the ID of a Notion database and a natural language description of what should be recorded.\n\nYour task is completely agnostic to the structure of the database: you must process any database without assuming specific fields.\n\n**Steps to follow:**\n\n1. Query the database schema using the `GET /v1/databases/{database_id}` endpoint to dynamically obtain:\n   - The exact names of all properties.\n   - The type of each property (e.g.: `title`, `rich_text`, `select`, `multi_select`, `number`, `checkbox`, `date`, `status`, `people`, `files`, etc.).\n   - Valid options for `select` and `multi_select` if they exist.\n   - Which properties have a defined type and therefore should be considered required.\n\n2. From the user's description:\n   - Identify which value corresponds to each mentioned property.\n   - Assign values only if they can be clearly inferred.\n   - If a property is marked as required by the schema but cannot be inferred from the message, skip it to avoid errors—unless it is of type `title`, which must be included compulsorily.\n\n3. When constructing the final JSON object:\n   - Include only the properties that have inferred values.\n   - Never include a property that is empty or has an invalid value according to its type.\n   - Use the correct structures for each type, for example:\n     - `title`: must be an array containing a `text.content` object.\n     - `select` and `multi_select`: must include only predefined valid values from the schema.\n     - `date`: must be in ISO 8601 format (`YYYY-MM-DD`).\n     - `checkbox`: must be a boolean.\n     - `number`: must be numeric.\n   - Strictly follow the format required by the Notion API and do not add any properties not defined in the schema.\n\nYour final response must be exclusively a JSON object representing the body of the request for `POST /v1/pages`, following all of the above rules. Do **not** include explanations or comments—only the JSON."
        }
      },
      "type": "@n8n/n8n-nodes-langchain.agent",
      "typeVersion": 1.9,
      "position": [
        220,
        0
      ],
      "id": "47660bae-f71b-4938-a643-85a0c2965eb2",
      "name": "AI Agent"
    },
    {
      "parameters": {
        "workflowInputs": {
          "values": [
            {
              "name": "id"
            },
            {
              "name": "data"
            }
          ]
        }
      },
      "type": "n8n-nodes-base.executeWorkflowTrigger",
      "typeVersion": 1.1,
      "position": [
        0,
        0
      ],
      "id": "e88cbb6b-b81c-427a-8a97-02d40bcbb5c0",
      "name": "When Executed by Another Workflow"
    },
    {
      "parameters": {
        "sseEndpoint": "https://n8n.salesgenius.co/mcp/notiondb/sse",
        "authentication": "bearerAuth",
        "include": "selected",
        "includeTools": [
          "get_db_structure"
        ]
      },
      "type": "@n8n/n8n-nodes-langchain.mcpClientTool",
      "typeVersion": 1,
      "position": [
        360,
        260
      ],
      "id": "bf4d4215-ae31-4930-8be9-600956bfbbf2",
      "name": "MCP Client",
      "credentials": {
        "httpBearerAuth": {
          "id": "W8jPE6HrmWmbxBe2",
          "name": "MCPTEST"
        }
      }
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.notion.com/v1/pages",
        "authentication": "predefinedCredentialType",
        "nodeCredentialType": "notionApi",
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={{ $json.output }}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        660,
        -220
      ],
      "id": "9b68ceed-707e-4f6b-bceb-c1a288c11ae3",
      "name": "HTTP Request",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      },
      "onError": "continueRegularOutput"
    },
    {
      "parameters": {
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserAutofixing",
      "typeVersion": 1,
      "position": [
        460,
        180
      ],
      "id": "76be863f-0ea5-4875-9475-c6e30a708828",
      "name": "Auto-fixing Output Parser"
    },
    {
      "parameters": {
        "schemaType": "manual",
        "inputSchema": "{\n  \"type\": \"object\",\n  \"required\": [\"parent\", \"properties\"],\n  \"properties\": {\n    \"parent\": {\n      \"type\": \"object\",\n      \"required\": [\"database_id\"],\n      \"properties\": {\n        \"database_id\": {\n          \"type\": \"string\"\n        }\n      },\n      \"additionalProperties\": false\n    },\n    \"properties\": {\n      \"type\": \"object\",\n      \"minProperties\": 1,\n      \"additionalProperties\": {\n        \"type\": \"object\",\n        \"oneOf\": [\n          {\n            \"required\": [\"title\"],\n            \"properties\": {\n              \"title\": {\n                \"type\": \"array\",\n                \"items\": {\n                  \"type\": \"object\",\n                  \"required\": [\"text\"],\n                  \"properties\": {\n                    \"text\": {\n                      \"type\": \"object\",\n                      \"required\": [\"content\"],\n                      \"properties\": {\n                        \"content\": { \"type\": \"string\" }\n                      }\n                    }\n                  }\n                }\n              }\n            }\n          },\n          {\n            \"required\": [\"rich_text\"],\n            \"properties\": {\n              \"rich_text\": {\n                \"type\": \"array\",\n                \"items\": {\n                  \"type\": \"object\",\n                  \"required\": [\"text\"],\n                  \"properties\": {\n                    \"text\": {\n                      \"type\": \"object\",\n                      \"required\": [\"content\"],\n                      \"properties\": {\n                        \"content\": { \"type\": \"string\" }\n                      }\n                    }\n                  }\n                }\n              }\n            }\n          },\n          {\n            \"required\": [\"select\"],\n            \"properties\": {\n              \"select\": {\n                \"type\": \"object\",\n                \"required\": [\"name\"],\n                \"properties\": {\n                  \"name\": { \"type\": \"string\" }\n                }\n              }\n            }\n          },\n          {\n            \"required\": [\"multi_select\"],\n            \"properties\": {\n              \"multi_select\": {\n                \"type\": \"array\",\n                \"items\": {\n                  \"type\": \"object\",\n                  \"required\": [\"name\"],\n                  \"properties\": {\n                    \"name\": { \"type\": \"string\" }\n                  }\n                }\n              }\n            }\n          },\n          {\n            \"required\": [\"number\"],\n            \"properties\": {\n              \"number\": { \"type\": \"number\" }\n            }\n          },\n          {\n            \"required\": [\"checkbox\"],\n            \"properties\": {\n              \"checkbox\": { \"type\": \"boolean\" }\n            }\n          },\n          {\n            \"required\": [\"date\"],\n            \"properties\": {\n              \"date\": {\n                \"type\": \"object\",\n                \"required\": [\"start\"],\n                \"properties\": {\n                  \"start\": {\n                    \"type\": \"string\",\n                    \"format\": \"date\"\n                  },\n                  \"end\": {\n                    \"type\": \"string\",\n                    \"format\": \"date\"\n                  }\n                }\n              }\n            }\n          },\n          {\n            \"required\": [\"status\"],\n            \"properties\": {\n              \"status\": {\n                \"type\": \"object\",\n                \"required\": [\"name\"],\n                \"properties\": {\n                  \"name\": { \"type\": \"string\" }\n                }\n              }\n            }\n          },\n          {\n            \"required\": [\"people\"],\n            \"properties\": {\n              \"people\": {\n                \"type\": \"array\",\n                \"items\": {\n                  \"type\": \"object\",\n                  \"required\": [\"id\"],\n                  \"properties\": {\n                    \"id\": { \"type\": \"string\" }\n                  }\n                }\n              }\n            }\n          },\n          {\n            \"required\": [\"files\"],\n            \"properties\": {\n              \"files\": {\n                \"type\": \"array\",\n                \"items\": {\n                  \"type\": \"object\"\n                }\n              }\n            }\n          }\n        ]\n      }\n    }\n  },\n  \"additionalProperties\": false\n}\n"
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserStructured",
      "typeVersion": 1.2,
      "position": [
        640,
        440
      ],
      "id": "d20febc1-388f-4001-b825-8eb98f46089d",
      "name": "Structured Output Parser"
    },
    {
      "parameters": {
        "model": {
          "__rl": true,
          "mode": "list",
          "value": "gpt-4o-mini"
        },
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.lmChatOpenAi",
      "typeVersion": 1.2,
      "position": [
        60,
        280
      ],
      "id": "7abb477b-c8cd-48be-abe5-c8317c1490ad",
      "name": "OpenAI Chat Model",
      "credentials": {
        "openAiApi": {
          "id": "OLHtLOP5C47dG8d5",
          "name": "OpenAi account"
        }
      }
    }
  ],
  "settings": {
    "executionOrder": "v1"
  },
  "shared": [
    {
      "createdAt": "2025-04-29T16:09:24.633Z",
      "updatedAt": "2025-04-29T16:09:24.633Z",
      "role": "workflow:owner",
      "workflowId": "WpgegqVk9wnmBrZT",
      "projectId": "JPifOz0qwqZ4t1q3",
      "project": {
        "createdAt": "2025-01-22T02:43:20.320Z",
        "updatedAt": "2025-01-22T02:44:04.001Z",
        "id": "JPifOz0qwqZ4t1q3",
        "name": "Emma Pace <emma@salesgenius.co>",
        "type": "personal",
        "icon": null,
        "projectRelations": [
          {
            "createdAt": "2025-01-22T02:43:20.320Z",
            "updatedAt": "2025-01-22T02:43:20.320Z",
            "role": "project:personalOwner",
            "userId": "f8bb0fb6-1857-45fa-9ac1-27b6e6497323",
            "projectId": "JPifOz0qwqZ4t1q3",
            "user": {
              "createdAt": "2025-01-22T02:43:19.556Z",
              "updatedAt": "2025-05-02T12:52:46.487Z",
              "id": "f8bb0fb6-1857-45fa-9ac1-27b6e6497323",
              "email": "emma@salesgenius.co",
              "firstName": "Emma",
              "lastName": "Pace",
              "personalizationAnswers": {
                "version": "v4",
                "personalization_survey_submitted_at": "2025-01-22T02:45:22.428Z",
                "personalization_survey_n8n_version": "1.74.3",
                "companySize": "<20",
                "companyType": "digital-agency",
                "role": "business-owner",
                "reportedSource": "youtube"
              },
              "settings": {
                "userActivated": true,
                "easyAIWorkflowOnboarded": true,
                "firstSuccessfulWorkflowId": "TotyBJ1rIIIGlYrK",
                "userActivatedAt": 1737997390312,
                "npsSurvey": {
                  "responded": true,
                  "lastShownAt": 1739558292687
                }
              },
              "role": "global:owner",
              "disabled": false,
              "mfaEnabled": false,
              "isPending": false,
              "isOwner": true
            }
          }
        ]
      }
    }
  ],
  "staticData": null,
  "tags": [],
  "triggerCount": 0,
  "updatedAt": "2025-04-30T16:59:19.000Z",
  "versionId": "445760b8-0b9c-4394-8862-af33a3306d4a"
}