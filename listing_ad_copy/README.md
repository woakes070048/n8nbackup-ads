{
  "active": false,
  "connections": {
    "Headline Agent": {
      "main": [
        [
          {
            "node": "Merge1",
            "type": "main",
            "index": 2
          },
          {
            "node": "Email Agent",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Lead In Agent": {
      "main": [
        [
          {
            "node": "Headline Agent",
            "type": "main",
            "index": 0
          },
          {
            "node": "Merge1",
            "type": "main",
            "index": 1
          }
        ]
      ]
    },
    "ad lead ins": {
      "ai_outputParser": [
        [
          {
            "node": "Lead In Agent",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    },
    "ad headlines": {
      "ai_outputParser": [
        [
          {
            "node": "Headline Agent",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    },
    "Merge1": {
      "main": [
        [
          {
            "node": "Combine & Clean",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Combine & Clean": {
      "main": [
        [
          {
            "node": "Create Notion Page",
            "type": "main",
            "index": 0
          },
          {
            "node": "Create Notion Task #3",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "claude 3.7": {
      "ai_languageModel": [
        [
          {
            "node": "Headline Agent",
            "type": "ai_languageModel",
            "index": 0
          },
          {
            "node": "Lead In Agent",
            "type": "ai_languageModel",
            "index": 0
          }
        ]
      ]
    },
    "All Inputs": {
      "main": [
        [
          {
            "node": "Find Contact on Notion1",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Find Contact on Notion1": {
      "main": [
        [
          {
            "node": "Contact Exists?",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Create Notion Task #3": {
      "main": [
        [
          {
            "node": "Update Listing Ad Campaign with Copy",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Delete Older Notion Task #3": {
      "main": [
        []
      ]
    },
    "Code2": {
      "main": [
        [
          {
            "node": "Create New Listing Ad Campaign",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Update Listing Ad Campaign": {
      "main": [
        []
      ]
    },
    "Create New Listing Ad Campaign": {
      "main": [
        [
          {
            "node": "Create Client Deliverables Page",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Contact Exists?": {
      "main": [
        [
          {
            "node": "Find Client",
            "type": "main",
            "index": 0
          }
        ],
        [
          {
            "node": "Create new Contact",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Create new Contact": {
      "main": [
        [
          {
            "node": "Create new Client",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Create new Client": {
      "main": [
        [
          {
            "node": "set fields",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "set fields": {
      "main": [
        [
          {
            "node": "Merge",
            "type": "main",
            "index": 1
          }
        ]
      ]
    },
    "set client fields": {
      "main": [
        [
          {
            "node": "Merge",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Merge": {
      "main": [
        [
          {
            "node": "Code2",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Code": {
      "main": [
        [
          {
            "node": "Create New Service Request",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Update Listing Ad Campaign with Copy": {
      "main": [
        [
          {
            "node": "Delete Older Notion Task #3",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Create New Service Request": {
      "main": [
        [
          {
            "node": "Code - Prepare Tasks Array",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Email Agent": {
      "main": [
        [
          {
            "node": "Code3",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "emails": {
      "ai_outputParser": [
        [
          {
            "node": "Email Agent",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    },
    "OpenAI Chat Model": {
      "ai_languageModel": [
        [
          {
            "node": "Email Agent",
            "type": "ai_languageModel",
            "index": 0
          },
          {
            "node": "Creative Generator",
            "type": "ai_languageModel",
            "index": 0
          }
        ]
      ]
    },
    "Code3": {
      "main": [
        [
          {
            "node": "Update Email Task",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Update Email Task": {
      "main": [
        [
          {
            "node": "Creative Generator",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Listing Ad - Create Task - Write Body Copy": {
      "main": [
        [
          {
            "node": "Listing Ad - Create Task  - Design Ad Creatives",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Listing Ad - Create Task  - Design Ad Creatives": {
      "main": [
        [
          {
            "node": "Listing Ad - Create Task - Finalize Email Sequence",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Listing Ad - Create Task - Finalize Email Sequence": {
      "main": [
        []
      ]
    },
    "Listing Ad - Create Task  - Send Ad Content to Client for Approval": {
      "main": [
        [
          {
            "node": "Listing Ad - Create Task - Add Emails into Clients CRM",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Listing Ad - Create Task - Add Emails into Clients CRM": {
      "main": [
        [
          {
            "node": "Listing Ad - Create Task - Schedule Ad on Meta",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Listing Ad - Create Task - Schedule Ad on Meta": {
      "main": [
        []
      ]
    },
    "Edit Fields": {
      "main": [
        [
          {
            "node": "Template #1",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #3": {
      "main": [
        [
          {
            "node": "Template #3 Vertical",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #2": {
      "main": [
        [
          {
            "node": "Template #2 Vertical",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Structured Output Parser": {
      "ai_outputParser": [
        [
          {
            "node": "Creative Generator",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    },
    "Template #1": {
      "main": [
        [
          {
            "node": "Template #1 Vertical",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #4": {
      "main": [
        [
          {
            "node": "Template #4 Vertical",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Creative Generator": {
      "main": [
        [
          {
            "node": "Edit Fields",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Find Client": {
      "main": [
        [
          {
            "node": "set client fields",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #1 Vertical": {
      "main": [
        [
          {
            "node": "Template #2",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #2 Vertical": {
      "main": [
        [
          {
            "node": "Template #3",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #3 Vertical": {
      "main": [
        [
          {
            "node": "Template #4",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #4 Vertical": {
      "main": [
        [
          {
            "node": "Template #5",
            "type": "main",
            "index": 0
          }
        ],
        [
          {
            "node": "Template #5",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #5": {
      "main": [
        [
          {
            "node": "Template #5 Vertical",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #5 Vertical": {
      "main": [
        [
          {
            "node": "Template #6",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #6": {
      "main": [
        [
          {
            "node": "Template #6 Vertical",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #6 Vertical": {
      "main": [
        [
          {
            "node": "Template #7",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #7": {
      "main": [
        [
          {
            "node": "Template #7 Vertical",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Template #7 Vertical": {
      "main": [
        [
          {
            "node": "Update Listing Ad Creative Task, with New Images Generated1",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Code - Prepare Tasks Array": {
      "main": [
        [
          {
            "node": "Create Tasks",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Typeform Trigger": {
      "main": [
        [
          {
            "node": "All Inputs",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Code1": {
      "main": [
        [
          {
            "node": "All Inputs",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Webhook": {
      "main": [
        [
          {
            "node": "Code1",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Code - Aggregate Task IDs": {
      "main": [
        [
          {
            "node": "Body Copy Agent",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Create Tasks": {
      "main": [
        [
          {
            "node": "Code - Aggregate Task IDs",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Create Client Deliverables Page": {
      "main": [
        [
          {
            "node": "Code",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "Body Copy Agent": {
      "main": [
        [
          {
            "node": "Headline Agent1",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "ad body copies": {
      "ai_outputParser": [
        [
          {
            "node": "Body Copy Agent",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    },
    "Google Gemini Chat Model": {
      "ai_languageModel": [
        [
          {
            "node": "Body Copy Agent",
            "type": "ai_languageModel",
            "index": 0
          },
          {
            "node": "Headline Agent1",
            "type": "ai_languageModel",
            "index": 0
          }
        ]
      ]
    },
    "Headline Agent1": {
      "main": [
        [
          {
            "node": "Update Listing Ad Campaign with Copy1",
            "type": "main",
            "index": 0
          }
        ]
      ]
    },
    "ad headlines1": {
      "ai_outputParser": [
        [
          {
            "node": "Headline Agent1",
            "type": "ai_outputParser",
            "index": 0
          }
        ]
      ]
    }
  },
  "createdAt": "2025-05-01T14:29:56.784Z",
  "id": "m9ePaOw1Y5JGcKMk",
  "meta": {
    "templateCredsSetupCompleted": true
  },
  "name": "Listing Ad copy",
  "nodes": [
    {
      "parameters": {
        "promptType": "define",
        "text": "=\nYOUR ROLE\nYou are a consortium of the world's most renowned headline specialists including Sabri Suby, Alex Hormozi, Perry Belcher, Clayton Makepeace, Gary Halbert, Joseph Sugarman, and John Carlton. You create headlines so compelling they achieve 6%+ CTRs on Facebook consistently.\nINPUT DATA\nProperty Essence\nProperty Type: {{ $('All Inputs').item.json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice Point: {{ $('All Inputs').item.json['What is the listing price? (e.g., $599,000.)'] }}[RULE: Only reference if \"Show In Ad\" is selected]\nLocation: {{ $('All Inputs').item.json['City/Town'] }}, {{ $('All Inputs').item.json['State/Region/Province'] }}\nKey Feature: {{ $('All Inputs').item.json['What\\'s the biggest WOW factor about this home?'] }}\nKey Emotion: {{ $('All Inputs').item.json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}\nTarget Audience Composite\nCombined profile of all three buyer personas:\nPrimary: {{ $('All Inputs').item.json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary: {{ $('All Inputs').item.json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary: {{ $('All Inputs').item.json['Buyer Profile #3 (If another type of buyer applies.)'] }}\nPreviously Generated Content\n[INCLUDE EXAMPLES OF LEAD-INS AND BODY COPIES]\n\nLead Ins:\n1. {{ $('Lead In Agent').item.json.output.ad_lead_ins[0].lead_ins[0].lead_in }} \n2. {{ $('Lead In Agent').item.json.output.ad_lead_ins[0].lead_ins[1].lead_in }} \n3. {{ $('Lead In Agent').item.json.output.ad_lead_ins[0].lead_ins[2].lead_in }} \n4. {{ $('Lead In Agent').item.json.output.ad_lead_ins[1].lead_ins[0].lead_in }} \n5. {{ $('Lead In Agent').item.json.output.ad_lead_ins[1].lead_ins[1].lead_in }} \n6. {{ $('Lead In Agent').item.json.output.ad_lead_ins[1].lead_ins[2].lead_in }} \n7. {{ $('Lead In Agent').item.json.output.ad_lead_ins[2].lead_ins[0].lead_in }} \n8. {{ $('Lead In Agent').item.json.output.ad_lead_ins[2].lead_ins[1].lead_in }} \n9. {{ $('Lead In Agent').item.json.output.ad_lead_ins[2].lead_ins[2].lead_in }} \n\nBody Copies:\nBODY COPY 1: {{ $('Body Copy Agent').item.json.output.ad_body_copies[0].body_copy }} \nBODY COPY 2: {{ $('Body Copy Agent').item.json.output.ad_body_copies[1].body_copy }}\nBODY COPY 3: {{ $('Body Copy Agent').item.json.output.ad_body_copies[2].body_copy }}\n\nTASK Create 10 scroll-stopping Facebook ad headlines that read like National Enquirer or Cosmopolitan magazine covers. These headlines must capture attention instantly and achieve 6%+ click-through rates.\nHEADLINE PATTERNS Use these proven high-conversion patterns:\n1. Feature + Feature Combo:\n    * \"Sunset Views + 1370 sqft\"\n    * \"Elite School Zone + Private Pool Retreat\"\n    * \"Sunset Balcony + Subway Access\"\n2. Location + Unique Description:\n    * \"Hidden Resort\" Style Home In Thornhill Woods\"\n    * \"Vaughan's Ultimate Backyard Escape\"\n    * \"Langley's $5.7M Real Estate Masterpiece\"\n3. Curiosity Gap with Special Descriptors:\n    * \"Toronto's 1370 sqft 'Unicorn Property'\"\n    * \"Rare 1370 sqft 'Giant Condo'\"\n    * \"The $5.7M Estate That Has Vancouver's Wealthy FLEEING The City\"\n4. Size/Value Statements:\n    * \"Large 2 Bed w/ Sunset Views\"\n    * \"Penthouse Feel. Hardwood Floors. Only $374K!\"\n    * \"The 6-Bedroom Mansion That Has Luxury Buyers In A FRENZY\"\nSTYLE GUIDELINES Character Length:\n* Aim for 20-40 characters when possible\n* Longer headlines acceptable when they tell a compelling story\nProperty-Specific Styling: FOR PROPERTIES UNDER $500K:\n* Focus on value, timing, and accessible luxury\n* Use words like: Smart buy, Rare find, Hidden gem\nFOR PROPERTIES $500K-$1M:\n* Emphasize elevated lifestyle and strategic advantages\n* Use words like: Exclusive access, Limited opportunity, Status symbol\nFOR PROPERTIES OVER $1M:\n* Highlight prestige, legacy, and uncompromising standards\n* Use words like: Private sanctuary, Elite address, Ultimate luxury\nLANGUAGE TECHNIQUES\n* Use single quotes around special descriptors ('Unicorn Property', 'Giant Condo')\n* Incorporate attention-grabbing words: Hidden, Secret, Rare, Ultimate, Private, Exclusive\n* For luxury properties use: Resort, Estate, Oasis, Sanctuary, Paradise, Retreat\n* For condos use: Views, Spacious, Giant, Unicorn, Gem, Marvel\n* Strategic capitalization (no ALL CAPS headlines, but strategic words can be CAPITALIZED)\n* Use symbols like + & to connect features efficiently\n* Create immediate cognitive dissonance or curiosity\nCOPYWRITING APPROACHES Each headline should embody one master copywriter's signature approach:\n* Sabri Suby: Bold claim that creates immediate FOMO Example: \"They Banned This Backyard in Vaughan\"\n* Alex Hormozi: Value-equation focused headline Example: \"$2.9M Buys a Home. This One Gives PRIVACY\"\n* Perry Belcher: Story hook that implies a twist Example: \"Neighbors Whisper About This Court's Secret\"\n* Clayton Makepeace: Emotionally charged power words Example: \"PRIVATE SANCTUARY Unleashed in Thornhill\"\n* Gary Halbert: Ultra-specific claim with implied proof Example: \"The Only Rebuilt Saltwater Oasis on Court\"\n* Joseph Sugarman: Psychological curiosity trigger Example: \"What Lies Beyond These Mature Trees\"\n* John Carlton: \"Outrageous\" claim with credibility element Example: \"Banned From MLS: Too Much Luxury\"\n* Eugene Schwartz: Market sophistication-appropriate revelation Example: \"Insiders Discovered This Vaughan Sanctuary\"\n* Gary Bencivenga: Research-implied credibility hook Example: \"Research Shows: Pool Owners Live Longer\"\n* David Deutsch: \"Information gap\" headline Example: \"Sophisticated Families Know This Secret\"\nFORBIDDEN ELEMENTS\n* Never use: \"must see,\" \"dream home,\" \"perfect,\" \"stunning,\" or \"beautiful\"\n* Never use exclamation points\n* Never use ellipses at the end of headlines\n* Never use questions that can be answered with \"no\"\n* Never use generic descriptors that could apply to any property\n* Never directly mention \"real estate,\" \"property,\" or \"home\" unless used in a pattern-interrupting way\nOUTPUT FORMAT [FACEBOOK AD HEADLINES: {Property Type} in {Location}] {headline text} [Sabri Suby Style] {headline text} [Alex Hormozi Style] {headline text} [Perry Belcher Style] {headline text} [Clayton Makepeace Style] {headline text} [Gary Halbert Style] {headline text} [Joseph Sugarman Style] {headline text} [John Carlton Style] {headline text} [Eugene Schwartz Style] {headline text} [Gary Bencivenga Style] {headline text} [David Deutsch Style]\nSUCCESS CRITERIA A 6%+ CTR headline will:\n* Force a pattern interrupt in the Facebook feed\n* Create immediate, irresistible curiosity\n* Speak directly to the desires/fears of the target audience\n* Avoid all real estate marketing clichés\n* Feel unlike any other real estate ad headline\n* Be impossible to scroll past without clicking\n* Work effectively with all lead-ins and body copies\n* Stand out visually in a crowded Facebook feed\n* Create a \"I need to know more\" response\n* Leverage a psychological trigger that bypasses logical resistance\nYou must respond ONLY with the requested JSON and no other text. Do not include explanations, introductions, or anything other than the JSON object.\n",
        "hasOutputParser": true,
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.agent",
      "typeVersion": 1.8,
      "position": [
        -8260,
        5140
      ],
      "id": "08f71cd9-66b0-4ebe-b5ac-738c8eb61137",
      "name": "Headline Agent"
    },
    {
      "parameters": {
        "promptType": "define",
        "text": "=YOUR ROLE\nYou are a consortium of the world's elite lead-in specialists, including Sabri Suby, Gary Bencivenga, Eugene Schwartz, John Caples, Robert Collier, and David Ogilvy. Your sole mission is to craft the perfect opening line that compels prospects to read the next sentence.\n\nINPUT DATA\nProperty Essence\nProperty Type: {{ $('All Inputs').item.json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice Point: {{ $('All Inputs').item.json['What is the listing price? (e.g., $599,000.)'] }}[RULE: Only reference if \"Show In Ad\" is selected]\nLocation: {{ $('All Inputs').item.json['City/Town'] }}, {{ $('All Inputs').item.json['State/Region/Province'] }}\nKey Feature: {{ $('All Inputs').item.json['What\\'s the biggest WOW factor about this home?'] }}\nKey Emotion: {{ $('All Inputs').item.json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}\nTarget Audience Composite\nCombined profile of all three buyer personas:\nPrimary: {{ $('All Inputs').item.json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary: {{ $('All Inputs').item.json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary: {{ $('All Inputs').item.json['Buyer Profile #3 (If another type of buyer applies.)'] }}\nPreviously Generated Content\n[INCLUDE EXAMPLES OF LEAD-INS AND BODY COPIES]\n\nBody Copies\nBODY COPY 1: {{ $('Body Copy Agent').item.json.output.ad_body_copies[0].body_copy }} \nBODY COPY 2: {{ $('Body Copy Agent').item.json.output.ad_body_copies[1].body_copy }}\nBODY COPY 3: {{ $('Body Copy Agent').item.json.output.ad_body_copies[2].body_copy }}\nTASK\nGenerate five unique, high-converting lead-in sentences for each of the three body copies (15 total) that will appear at the very beginning of the Facebook ad.\nSTYLE GUIDELINES\nUniversal Rules\nMaximum Length: 60 characters (including spaces)\nMust fit entirely on one line on mobile devices\nMust transition seamlessly into its associated body copy\nMust create immediate interest within the first 3-4 words\nProfile-Specific Styling\nFor Body Copy 1 ({{ $('Body Copy Agent').item.json.output.ad_body_copies[0].buyer_profile }}):\nIf the profile includes \"first-time buyer\" or \"young family\":\nTone: Exciting, approachable (max 1 strategic emoji)\nVoice: Direct \"you\" address, acting as a helpful insider\nAppeal: Affordability, opportunity, perfect timing\nIf the profile includes \"luxury\" or \"high-end\":\nTone: Exclusive and refined, with no emojis\nVoice: Authoritative with understated confidence\nAppeal: Status, distinction, limited access\nIf the profile includes \"investor\":\nTone: Urgent and data-driven, with no emojis\nVoice: Fellow investor and strategic advisor\nAppeal: ROI, market timing, competitive advantage\nAdapt styles similarly for Body Copies 2 and 3 based on their respective profiles.\nTECHNICAL REQUIREMENTS\nFor each set of five lead-ins:\nLocation: At least two must mention the location specifically\nUrgency: At least one must create a sense of urgency (without using the word \"urgent\")\nWOW Factor: At least one must focus on the WOW factor\nExclusivity: At least one must leverage exclusivity or scarcity\nPrice: If \"Show In Ad\" is selected for the price, at least two must include the price\nRestrictions:\nNo lead-in should begin with \"Introducing\" or \"Just Listed\"\nNo lead-in should end with an ellipsis (...)\nNo lead-in should include exclamation points\nEach lead-in within a set must utilize a different psychological trigger\nCOPYWRITING TECHNIQUES\nEach set of five lead-ins must include one example of each master's signature approach:\nSabri Suby Style: Bold claim that creates immediate FOMO\nGary Bencivenga Style: Specific, credible promise of value\nEugene Schwartz Style: Taps into existing market desire with a new angle\nJohn Caples Style: Curiosity-driven headline that promises news\nDavid Ogilvy Style: Direct, specific benefit statement\nOUTPUT FORMAT\nLead-ins for Body Copy 1 ({{ $('Body Copy Agent').item.json.output.ad_body_copies[0].buyer_profile }}):\n{lead-in text} [Sabri Suby Style]\n{lead-in text} [Gary Bencivenga Style]\n{lead-in text} [Eugene Schwartz Style]\n{lead-in text} [John Caples Style]\n{lead-in text} [David Ogilvy Style]\nLead-ins for Body Copy 2 ({{ $('Body Copy Agent').item.json.output.ad_body_copies[1].buyer_profile }}):\n{lead-in text} [Sabri Suby Style]\n{lead-in text} [Gary Bencivenga Style]\n{lead-in text} [Eugene Schwartz Style]\n{lead-in text} [John Caples Style]\n{lead-in text} [David Ogilvy Style]\nLead-ins for Body Copy 3 ({{ $('Body Copy Agent').item.json.output.ad_body_copies[2].buyer_profile }}):\n{lead-in text} [Sabri Suby Style]\n{lead-in text} [Gary Bencivenga Style]\n{lead-in text} [Eugene Schwartz Style]\n{lead-in text} [John Caples Style]\n{lead-in text} [David Ogilvy Style]\nSUCCESS CRITERIA\nA successful lead-in will:\nImmediately capture the reader's attention and make them stop scrolling\nSpark high curiosity, making the body copy irresistible to read\nClearly resonate with its specific buyer profile\nAvoid all real estate clichés\nSeamlessly flow into its corresponding body copy\n\n\n",
        "hasOutputParser": true,
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.agent",
      "typeVersion": 1.8,
      "position": [
        -8620,
        5020
      ],
      "id": "56f94e56-59a0-40bc-92a4-25e2cb27e8e4",
      "name": "Lead In Agent"
    },
    {
      "parameters": {
        "jsonSchemaExample": "{\n \"ad_lead_ins\": [\n   {\n     \"buyer_profile\": \"\",\n     \"lead_ins\": [\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       }\n     ]\n   },\n   {\n     \"buyer_profile\": \"\",\n     \"lead_ins\": [\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       }\n     ]\n   },\n   {\n     \"buyer_profile\": \"\",\n     \"lead_ins\": [\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       },\n       {\n         \"lead_in\": \"\",\n         \"style\": \"\"\n       }\n     ]\n   }\n ]\n}"
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserStructured",
      "typeVersion": 1.2,
      "position": [
        -8540,
        5240
      ],
      "id": "ac9540ab-847b-447d-9228-a3d2e7d68d5a",
      "name": "ad lead ins"
    },
    {
      "parameters": {
        "jsonSchemaExample": "{\n \"ad_headlines\": [\n   {\n     \"headline\": \"\",\n     \"style\": \"\"\n   },\n   {\n     \"headline\": \"\",\n     \"style\": \"\"\n   },\n   {\n     \"headline\": \"\",\n     \"style\": \"\"\n   }\n ]\n}"
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserStructured",
      "typeVersion": 1.2,
      "position": [
        -8160,
        5360
      ],
      "id": "92be5c0a-01ad-4280-868c-85a5438efc87",
      "name": "ad headlines"
    },
    {
      "parameters": {
        "numberInputs": 3
      },
      "type": "n8n-nodes-base.merge",
      "typeVersion": 3,
      "position": [
        -7800,
        4840
      ],
      "id": "334809fb-a6a6-477f-9f52-8ced157d9633",
      "name": "Merge1"
    },
    {
      "parameters": {
        "jsCode": "// Transform multiple items into a single clean JSON object\nfunction transformToCleanJson() {\n  // Initialize our new structure\n  const cleanJson = {};\n  \n  // Process all items\n  $input.all().forEach(item => {\n    // Make sure we have an item with output property\n    if (item && item.json && item.json.output) {\n      // Get the key from this item's output (assuming each item has a different key)\n      const outputKeys = Object.keys(item.json.output);\n      \n      // Add each key-value pair to our clean JSON\n      outputKeys.forEach(key => {\n        cleanJson[key] = item.json.output[key];\n      });\n    }\n  });\n  \n  // Return as a single item\n  return [{ json: cleanJson }];\n}\n\n// Process all input items\nreturn transformToCleanJson();"
      },
      "type": "n8n-nodes-base.code",
      "typeVersion": 2,
      "position": [
        -7500,
        4840
      ],
      "id": "0c77a05f-7098-4c6b-b491-ccbfacf03e86",
      "name": "Combine & Clean"
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1af1d08c-4f5a-8013-a4cb-ed1633f9429c",
          "mode": "list",
          "cachedResultName": "Ad Content Generations",
          "cachedResultUrl": "https://www.notion.so/1af1d08c4f5a8013a4cbed1633f9429c"
        },
        "title": "={{ $('All Inputs').first().json.Address }}",
        "simple": false,
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Type|select",
              "selectValue": "Listing Ad"
            },
            {
              "key": "ai model|select",
              "selectValue": "claude-3.7"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_1",
              "textContent": "=Headlines"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[0].headline }} ({{ $json.ad_headlines[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[1].headline }} ({{ $json.ad_headlines[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[2].headline }} ({{ $json.ad_headlines[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[3].headline }} ({{ $json.ad_headlines[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[4].headline }} ({{ $json.ad_headlines[4].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[5].headline }} ({{ $json.ad_headlines[5].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[6].headline }} ({{ $json.ad_headlines[6].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[7].headline }} ({{ $json.ad_headlines[7].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[8].headline }} ({{ $json.ad_headlines[8].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[9].headline }} ({{ $json.ad_headlines[9].style }})"
            },
            {
              "type": "heading_1",
              "textContent": "=Lead-ins"
            },
            {
              "type": "heading_3",
              "textContent": "={{ $json.ad_lead_ins[0].buyer_profile }} Lead-ins"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[0].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[1].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[2].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[3].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[4].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[4].style }})"
            },
            {
              "type": "heading_3",
              "textContent": "={{ $json.ad_lead_ins[1].buyer_profile }} Lead-ins"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[0].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[1].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[2].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[3].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[4].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[4].style }})"
            },
            {
              "type": "heading_3",
              "textContent": "={{ $json.ad_lead_ins[2].buyer_profile }} Lead-ins"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[0].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[1].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[2].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[3].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[4].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[4].style }})"
            },
            {
              "type": "heading_1",
              "textContent": "=Body Copies"
            },
            {
              "type": "heading_2",
              "textContent": "={{ $json.ad_body_copies[0].buyer_profile }} Body Copy:"
            },
            {
              "textContent": "={{ $json.ad_body_copies[0].body_copy }}"
            },
            {
              "type": "heading_2",
              "textContent": "={{ $json.ad_body_copies[1].buyer_profile }} Body Copy:"
            },
            {
              "textContent": "={{ $json.ad_body_copies[1].body_copy }}"
            },
            {
              "type": "heading_2",
              "textContent": "={{ $json.ad_body_copies[2].buyer_profile }} Body Copy:"
            },
            {
              "textContent": "={{ $json.ad_body_copies[2].body_copy }}"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -7280,
        4940
      ],
      "id": "48c02312-12e9-4f2b-9883-406c3023aa40",
      "name": "Create Notion Page",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "model": "=claude-3-7-sonnet-20250219",
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.lmChatAnthropic",
      "typeVersion": 1.2,
      "position": [
        -8000,
        5560
      ],
      "id": "f3aca1b6-701d-4003-9fb1-1f7aa696cdae",
      "name": "claude 3.7",
      "credentials": {
        "anthropicApi": {
          "id": "vvRYzeVE6A8mYyNt",
          "name": "Anthropic - Claude"
        }
      }
    },
    {
      "parameters": {
        "assignments": {
          "assignments": [
            {
              "id": "85777823-62f2-4d19-9b55-8d86bc69b239",
              "name": "Address",
              "value": "={{ $json[\"Address\"] }}",
              "type": "string"
            },
            {
              "id": "8855c0da-52cf-4b84-a5ff-4c6500358fa5",
              "name": "City/Town",
              "value": "={{ $json[\"City/Town\"] }}",
              "type": "string"
            },
            {
              "id": "19d24efe-3314-4bb6-80b8-c5f5a0801eac",
              "name": "State/Region/Province",
              "value": "={{ $json[\"State/Region/Province\"] }}",
              "type": "string"
            },
            {
              "id": "cda2b4e7-981e-4d81-a5f2-1830391013fa",
              "name": "Zip/Post Code",
              "value": "={{ $json[\"Zip/Post Code\"] }}",
              "type": "string"
            },
            {
              "id": "7bfe01b6-9016-4e0c-8f16-29f6c3e59f66",
              "name": "Country",
              "value": "={{ $json[\"Country\"] }}",
              "type": "string"
            },
            {
              "id": "58b357ed-d34c-4e76-bc9e-6be935953456",
              "name": "*What Is The Objective Of Your Ad?*",
              "value": "={{ $json[\"*What Is The Objective Of Your Ad?*\"] }}",
              "type": "string"
            },
            {
              "id": "0c2eb890-51ce-4cb0-a1e4-c293ffc9d12c",
              "name": "What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)",
              "value": "={{ $json[\"What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)\"] }}",
              "type": "string"
            },
            {
              "id": "3449ecdd-516d-4954-a102-c77c5c3650e7",
              "name": "What is the listing price? (e.g., $599,000.)",
              "value": "={{ $json[\"What is the listing price? (e.g., $599,000.)\"] }}",
              "type": "string"
            },
            {
              "id": "a4039104-cb16-4f8d-b4b1-bede14e87821",
              "name": "Do you want the listing price shown in the ad or only in the email follow-up? (Show In Ad, Only Show In Email Sequence)",
              "value": "={{ $json[\"Do you want the listing price shown in the ad or only in the email follow-up? (Show In Ad, Only Show In Email Sequence)\"] }}",
              "type": "string"
            },
            {
              "id": "e87752fa-1ae6-4375-9054-b2a17518f568",
              "name": "How many bedrooms? ",
              "value": "={{ $json[\"How many bedrooms? \"] }}",
              "type": "string"
            },
            {
              "id": "3ef3f0a4-24e3-4121-bc58-bf7f9ff3248d",
              "name": "How many bathrooms? ",
              "value": "={{ $json[\"How many bathrooms? \"] }}",
              "type": "string"
            },
            {
              "id": "104ffc45-d707-42f8-b631-b3a4bd8e5098",
              "name": "What are the top 3-5 selling features of this home? (Examples: Open-concept kitchen, large backyard, lake view, school zone, etc.)",
              "value": "={{ $json[\"What are the top 3-5 selling features of this home? (Examples: Open-concept kitchen, large backyard, lake view, school zone, etc.)\"] }}",
              "type": "string"
            },
            {
              "id": "955b68b3-0b54-407a-93d7-dac72192958f",
              "name": "What's the biggest WOW factor about this home?",
              "value": "={{ $json[\"What’s the biggest WOW factor about this home?\"] }}",
              "type": "string"
            },
            {
              "id": "86ad2395-9f08-4708-836a-0395e40fd41c",
              "name": "What's one thing people LOVE when they walk in?",
              "value": "={{ $json[\"What’s one thing people LOVE when they walk in?\"] }}",
              "type": "string"
            },
            {
              "id": "62296e42-7f80-423f-af26-7072a08b4a43",
              "name": "What are some things people don't immediately notice but should?",
              "value": "={{ $json[\"What are some things people don’t immediately notice but should?\"] }}",
              "type": "string"
            },
            {
              "id": "254b9379-2081-4350-89ff-537f22fabf7f",
              "name": "Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)",
              "value": "={{ $json[\"Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)\"] }}",
              "type": "string"
            },
            {
              "id": "69ed1a35-bc7e-4044-b8e1-2cdba7caddd4",
              "name": "Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)",
              "value": "={{ $json[\"Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)\"] }}",
              "type": "string"
            },
            {
              "id": "39db1e70-c265-4ebf-bfb9-9c4e25bc16bf",
              "name": "Buyer Profile #3 (If another type of buyer applies.)",
              "value": "={{ $json[\"Buyer Profile #3 (If another type of buyer applies.)\"] }}",
              "type": "string"
            },
            {
              "id": "40cdb3fe-2d8a-4698-a3d0-6000caba144d",
              "name": "What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)[0]",
              "value": "={{ $json[\"What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)\"][0] }}",
              "type": "string"
            },
            {
              "id": "12fc5531-2f2f-475c-ad42-352dd4f8f4f3",
              "name": "What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)[1]",
              "value": "={{ $json[\"What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)\"][1] }}",
              "type": "string"
            },
            {
              "id": "a0b1d36b-ab17-47b4-920b-5cdb270222ed",
              "name": "What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)[2]",
              "value": "={{ $json[\"What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)\"][2] }}",
              "type": "string"
            },
            {
              "id": "db192850-bfec-4728-b0be-3550dbff2cfd",
              "name": "What makes this home better than similar listings in the area?",
              "value": "={{ $json[\"What makes this home better than similar listings in the area?\"] }}",
              "type": "string"
            },
            {
              "id": "3d55e100-9028-432d-92bb-e0ea6f7d997b",
              "name": "What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)",
              "value": "={{ $json[\"What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)\"] }}",
              "type": "string"
            },
            {
              "id": "74cf4200-c85f-4d9d-bfbd-c0955f2539b0",
              "name": "Is this an investment property?",
              "value": "={{ $json[\"Is this an investment property?\"] }}",
              "type": "boolean"
            },
            {
              "id": "f2d9fe9c-59cf-45f0-a08d-57bf43ceae3c",
              "name": "What is your total daily budget for ads? ",
              "value": "={{ $json[\"What is your total daily budget for ads? \"] }}",
              "type": "string"
            },
            {
              "id": "fef5a3fd-da32-409c-90ed-30e192bc6b4b",
              "name": "Enter Branded Photo Tour / 3D Tour URL ",
              "value": "={{ $json[\"Enter Branded Photo Tour / 3D Tour URL \"] }}",
              "type": "string"
            },
            {
              "id": "a4ceb728-d6e3-4f1e-b472-12da38857856",
              "name": "Upload THE BEST raw listing photo.",
              "value": "={{ $json[\"Upload THE BEST raw listing photo.\"] }}",
              "type": "string"
            },
            {
              "id": "587030b6-245d-4960-982d-7040d202d0df",
              "name": "Copy & Paste the current listing description here. (We'll refine and optimize it for ad effectiveness!)",
              "value": "={{ $json[\"Copy & Paste the current listing description here. (We’ll refine and optimize it for ad effectiveness!)\"] }}",
              "type": "string"
            },
            {
              "id": "c3456e0b-7e4d-46ab-ab51-ab02d31f9226",
              "name": "First name",
              "value": "={{ $json[\"First name\"] }}",
              "type": "string"
            },
            {
              "id": "6d6ad49d-1980-4e96-8064-0be5c8d02ae5",
              "name": "=Last name",
              "value": "={{ $json[\"Last name\"] }}",
              "type": "string"
            },
            {
              "id": "a5a9ec05-feda-485d-91da-6950ddc7e4f7",
              "name": "Phone number",
              "value": "={{ $json[\"Phone number\"] }}",
              "type": "string"
            },
            {
              "id": "8357e6fd-6ed0-4db1-bb2e-f5ece4836e69",
              "name": "Email",
              "value": "={{ $json[\"Email\"] }}",
              "type": "string"
            },
            {
              "id": "26cbf96a-a654-41f0-a6dc-74505b0ffb4f",
              "name": "Company",
              "value": "={{ $json[\"Company\"] }}",
              "type": "string"
            }
          ]
        },
        "includeOtherFields": true,
        "options": {}
      },
      "type": "n8n-nodes-base.set",
      "typeVersion": 3.4,
      "position": [
        -9800,
        2780
      ],
      "id": "bc4c7646-ac0b-4aa8-9932-a16aab926c72",
      "name": "All Inputs"
    },
    {
      "parameters": {
        "resource": "databasePage",
        "operation": "getAll",
        "databaseId": {
          "__rl": true,
          "value": "1761d08c-4f5a-8016-89dd-f81384652240",
          "mode": "list",
          "cachedResultName": "Contacts",
          "cachedResultUrl": "https://www.notion.so/1761d08c4f5a801689ddf81384652240"
        },
        "returnAll": true,
        "filterType": "manual",
        "filters": {
          "conditions": [
            {
              "key": "email|email",
              "condition": "contains",
              "emailValue": "={{ $('All Inputs').first().json.Email }}"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -9580,
        2780
      ],
      "id": "25b2bbd9-30bd-48c6-8ae2-e5b9f35f7c9d",
      "name": "Find Contact on Notion1",
      "alwaysOutputData": true,
      "notesInFlow": false,
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
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8010-9e47-c82ce7f1f1ea",
          "mode": "list",
          "cachedResultName": "Client Tasks",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80109e47c82ce7f1f1ea"
        },
        "title": "=Finalize Ad Copy for {{ $('All Inputs').first().json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}",
        "simple": false,
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Tags|multi_select",
              "multiSelectValue": [
                "New Listing"
              ]
            },
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Priority|select",
              "selectValue": "Medium"
            },
            {
              "key": "Status|status",
              "statusValue": "Ready To-Do"
            },
            {
              "key": "Assignee|people",
              "peopleValue": [
                "17ad872b-594c-8163-b836-0002befd0f21"
              ]
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Update Listing Ad Campaign').first().json.id }}"
              ]
            },
            {
              "key": "Due|date",
              "includeTime": false,
              "date": "={{ new Date(new Date().getTime() + (2*24*60*60*1000)).toISOString() }}"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_1",
              "textContent": "=Headlines"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[0].headline }} ({{ $json.ad_headlines[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[1].headline }} ({{ $json.ad_headlines[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[2].headline }} ({{ $json.ad_headlines[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[3].headline }} ({{ $json.ad_headlines[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[4].headline }} ({{ $json.ad_headlines[4].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[5].headline }} ({{ $json.ad_headlines[5].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[6].headline }} ({{ $json.ad_headlines[6].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[7].headline }} ({{ $json.ad_headlines[7].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[8].headline }} ({{ $json.ad_headlines[8].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_headlines[9].headline }} ({{ $json.ad_headlines[9].style }})"
            },
            {
              "type": "heading_1",
              "textContent": "=Lead-ins"
            },
            {
              "type": "heading_3",
              "textContent": "={{ $json.ad_lead_ins[0].buyer_profile }} Lead-ins"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[0].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[1].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[2].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[3].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[0].lead_ins[4].lead_in }} ({{ $json.ad_lead_ins[0].lead_ins[4].style }})"
            },
            {
              "type": "heading_3",
              "textContent": "={{ $json.ad_lead_ins[1].buyer_profile }} Lead-ins"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[0].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[1].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[2].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[3].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[1].lead_ins[4].lead_in }} ({{ $json.ad_lead_ins[1].lead_ins[4].style }})"
            },
            {
              "type": "heading_3",
              "textContent": "={{ $json.ad_lead_ins[2].buyer_profile }} Lead-ins"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[0].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[0].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[1].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[1].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[2].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[2].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[3].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[3].style }})"
            },
            {
              "type": "bulleted_list_item",
              "textContent": "={{ $json.ad_lead_ins[2].lead_ins[4].lead_in }} ({{ $json.ad_lead_ins[2].lead_ins[4].style }})"
            },
            {
              "type": "heading_1",
              "textContent": "=Body Copies"
            },
            {
              "type": "heading_2",
              "textContent": "={{ $json.ad_body_copies[0].buyer_profile }} Body Copy:"
            },
            {
              "textContent": "={{ $json.ad_body_copies[0].body_copy }}"
            },
            {
              "type": "heading_2",
              "textContent": "={{ $json.ad_body_copies[1].buyer_profile }} Body Copy:"
            },
            {
              "textContent": "={{ $json.ad_body_copies[1].body_copy }}"
            },
            {
              "type": "heading_2",
              "textContent": "={{ $json.ad_body_copies[2].buyer_profile }} Body Copy:"
            },
            {
              "textContent": "={{ $json.ad_body_copies[2].body_copy }}"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -7280,
        4640
      ],
      "id": "c70c86b4-6233-4994-a656-6a6a7711e8e7",
      "name": "Create Notion Task #3",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "operation": "archive",
        "pageId": {
          "__rl": true,
          "value": "={{ $('Listing Ad - Create Task - Write Body Copy').first().json.id }}",
          "mode": "id",
          "__regex": "^([0-9a-f]{8}-?[0-9a-f]{4}-?[0-9a-f]{4}-?[0-9a-f]{4}-?[0-9a-f]{12})"
        }
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -6680,
        4640
      ],
      "id": "75a31336-621a-47e8-9375-b63bb68bf8c1",
      "name": "Delete Older Notion Task #3",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "jsCode": "const processedItems = $('All Inputs').all().map(item => {\n  try {\n    // Get form data\n    const formData = item.json;\n    \n    // Get client relation ID from Merge node - ensure it exists\n    const clientRelationId = $('Merge').first()?.json?.['notion client id'];\n    console.log('Client Relation ID:', clientRelationId); // Debug log\n    \n    // Extract form title (use Address or another primary field as the page title)\n    const pageTitle = formData.Address || \"Form Submission\";\n    \n    // Create content blocks for Notion\n    const contentBlocks = [];\n    \n    // Add title block\n    contentBlocks.push({\n      object: \"block\",\n      type: \"heading_1\",\n      heading_1: {\n        rich_text: [{\n          type: \"text\",\n          text: { content: pageTitle }\n        }]\n      }\n    });\n    \n    // Process each field in the form data\n    for (const [question, answer] of Object.entries(formData)) {\n      // Skip internal fields or metadata\n      if (question.startsWith('_') || question === 'markdown' || question === 'error') {\n        continue;\n      }\n      \n      // Format the question (remove asterisks and trim)\n      const formattedQuestion = question.replace(/\\*/g, '').trim();\n      \n      // Add question as heading\n      contentBlocks.push({\n        object: \"block\",\n        type: \"heading_3\",\n        heading_3: {\n          rich_text: [{\n            type: \"text\",\n            text: { content: formattedQuestion }\n          }]\n        }\n      });\n      \n      // Format the answer based on its type\n      let formattedAnswer;\n      let blockType = \"paragraph\";\n      \n      if (answer === undefined || answer === null) {\n        formattedAnswer = 'Not provided';\n      } else if (Array.isArray(answer)) {\n        formattedAnswer = answer.join(', ');\n      } else if (typeof answer === 'object') {\n        // Handle nested objects (like the emotions field)\n        formattedAnswer = Object.entries(answer)\n          .map(([key, val]) => `${key}: ${val}`)\n          .join(', ');\n      } else if (typeof answer === 'boolean') {\n        formattedAnswer = answer ? 'Yes' : 'No';\n      } else {\n        formattedAnswer = String(answer);\n      }\n      \n      // Check if this is an image URL\n      const isImage = typeof answer === 'string' && \n                (answer.includes('api.typeform.com/responses/files') || \n                 (answer.startsWith('http') && \n                  (answer.endsWith('.jpg') || answer.endsWith('.png') || \n                   answer.endsWith('.jpeg') || answer.endsWith('.gif'))));\n      \n      if (isImage) {\n        // Add image block\n        contentBlocks.push({\n          object: \"block\",\n          type: \"image\",\n          image: {\n            type: \"external\",\n            external: {\n              url: answer\n            }\n          }\n        });\n      } else {\n        // Add text block\n        contentBlocks.push({\n          object: \"block\",\n          type: \"paragraph\",\n          paragraph: {\n            rich_text: [{\n              type: \"text\",\n              text: { content: formattedAnswer }\n            }]\n          }\n        });\n      }\n    }\n    \n    // Prepare data for Notion API\n    console.log('Creating Notion data structure'); // Debug log\n    \n    // Generate the Campaign Name with address information\n    const address = formData.Address || \"\";\n    const addressLine2 = formData['Address line 2'] || \"\";\n    const campaignName = `New Listing | ${address} ${addressLine2}`.trim();\n    \n    // Get the location from form data\n    const location = formData[\"Which location would you like to target with the ad? \"] || \"\";\n    \n    // Get the budget per day and extract just the number\n    const budgetPerDay = formData[\"What is your total daily budget for ads? \"] || \"\";\n    // Extract number from string (remove $ and any other non-numeric characters except decimal point)\n    const numericBudget = budgetPerDay ? parseFloat(budgetPerDay.replace(/[^\\d.-]/g, '')) : 0;\n    \n    // Get end date for ad\n    const endDate = formData[\"End Date For Ad \"] || \"\";\n    \n    item.json.notionData = {\n      parent: {\n        // Replace with your actual database ID\n        database_id: \"1a41d08c4f5a808b8944c0faa8922503\"\n      },\n      icon: {\n        type: \"emoji\",\n        emoji: \"🏠\"\n      },\n      properties: {\n        \"Campaign Name\": {\n          title: [\n            {\n              text: {\n                content: campaignName\n              }\n            }\n          ]\n        },\n        \"Campaign Type\": {\n          \"multi_select\": [\n            {\n              \"name\": \"Listing Ad\"\n            }\n          ]\n        },\n        \"Platform\": {\n          \"multi_select\": [\n            {\n              \"name\": \"Instagram\"\n            },\n            {\n              \"name\": \"Facebook\"\n            }\n          ]\n        },\n        \"Status\": {\n          \"status\": {\n            \"name\": \"Planning\"\n          }\n        },\n        \"Start Date\": {\n          \"date\": {\n            \"start\": (function(){\n              let d = new Date();\n              let b = 2;\n              while(b > 0){\n                d.setDate(d.getDate() + 1);\n                if(d.getDay() !== 0 && d.getDay() !== 6) b--;\n              }\n              return d.toISOString();\n            })()\n          }\n        },\n        \"End Date\": {\n          \"date\": {\n            \"start\": endDate\n          }\n        },\n        \"Location\": {\n          \"rich_text\": [\n            {\n              \"text\": {\n                \"content\": location\n              }\n            }\n          ]\n        },\n        \"Budget Per Day\": {\n          \"number\": numericBudget\n        }\n      },\n      children: contentBlocks\n    };\n    \n    // Add Client relation property if clientRelationId exists\n    if (clientRelationId) {\n      item.json.notionData.properties[\"Client\"] = {\n        \"relation\": Array.isArray(clientRelationId) ? \n          clientRelationId.map(id => ({ id })) : \n          [{ id: clientRelationId }]\n      };\n    }\n    \n    // Add Campaign Objective property based on condition\n    const campaignObjective = (formData[\"*What Is The Objective Of Your Ad?*\"] === \"I Want To Get Maximum Exposure\") \n      ? \"Exposure\" \n      : \"Leads\";\n    \n    item.json.notionData.properties[\"Campaign Objective\"] = {\n      \"select\": {\n        \"name\": campaignObjective\n      }\n    };\n    \n    console.log('Final Notion Data:', JSON.stringify(item.json.notionData)); // Debug log\n    \n    return item;\n  } catch (error) {\n    // Handle errors gracefully\n    console.error('Error processing form data:', error.message);\n    item.json.error = error.message;\n    return item;\n  }\n});\n// Return the processed items\nreturn processedItems;"
      },
      "type": "n8n-nodes-base.code",
      "typeVersion": 2,
      "position": [
        -8260,
        2780
      ],
      "id": "b15a3895-4bde-4b07-b203-5ee4da6b67d9",
      "name": "Code2",
      "retryOnFail": true
    },
    {
      "parameters": {
        "resource": "databasePage",
        "operation": "update",
        "pageId": {
          "__rl": true,
          "value": "={{ $('Create New Listing Ad Campaign').first().json.id }}",
          "mode": "id"
        },
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Campaign Name|title",
              "title": "=New Listing |  {{ $('All Inputs').first().json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}"
            },
            {
              "key": "Campaign Type|multi_select",
              "multiSelectValue": "={{ [\"Listing Ad\"] }}"
            },
            {
              "key": "Status|status",
              "statusValue": "=Planning"
            },
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Start Date|date",
              "includeTime": false,
              "date": "={{ new Date(new Date().getTime() + (4*24*60*60*1000)).toISOString() }}",
              "timezone": "America/Toronto"
            },
            {
              "key": "Headline 4|rich_text",
              "textContent": "={{ $('All Inputs').first().json[\"Which location would you like to target with the ad? \"] }}"
            },
            {
              "key": "Platform|multi_select",
              "multiSelectValue": [
                "Facebook",
                "Instagram"
              ]
            },
            {
              "key": "Campaign Objective|select",
              "selectValue": "={{ \n  ($('All Inputs').first().json[\"*What Is The Objective Of Your Ad?*\"] === \"I Want To Get Maximum Exposure\") \n  ? \"Exposure\" \n  : \"Leads\" \n}}"
            },
            {
              "key": "Budget Per Day|number"
            }
          ]
        },
        "options": {
          "icon": "🏠"
        }
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -10240,
        4260
      ],
      "id": "f23544c8-a7f7-492f-a3cb-2c2a06555291",
      "name": "Update Listing Ad Campaign",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.notion.com/v1/pages",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "Authorization",
              "value": "Bearer ntn_y77938235783grxbphRwEazxtixxh4eENsIdl2RRJyW9fy"
            },
            {
              "name": "Notion-Version",
              "value": "2022-06-28"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={{ $('Code2').item.json.notionData }}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -8040,
        2780
      ],
      "id": "7fc0e725-c69d-45d1-9f44-a7b4e45ad0fb",
      "name": "Create New Listing Ad Campaign",
      "retryOnFail": true
    },
    {
      "parameters": {
        "conditions": {
          "options": {
            "caseSensitive": true,
            "leftValue": "",
            "typeValidation": "strict",
            "version": 2
          },
          "conditions": [
            {
              "id": "0c01aa16-f3be-440a-935f-c9acc54f7ab9",
              "leftValue": "={{ $json }}",
              "rightValue": "",
              "operator": {
                "type": "object",
                "operation": "notEmpty",
                "singleValue": true
              }
            }
          ],
          "combinator": "and"
        },
        "options": {}
      },
      "type": "n8n-nodes-base.if",
      "typeVersion": 2.2,
      "position": [
        -9360,
        2780
      ],
      "id": "ca49c607-9eaa-49fc-8e34-e2b9a63e55e1",
      "name": "Contact Exists?"
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1761d08c-4f5a-8016-89dd-f81384652240",
          "mode": "list",
          "cachedResultName": "Contacts",
          "cachedResultUrl": "https://www.notion.so/1761d08c4f5a801689ddf81384652240"
        },
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Client Name|title",
              "title": "={{ $('All Inputs').first().json[\"First name\"] }} {{ $('All Inputs').first().json[\"Last name\"] }}"
            },
            {
              "key": "email_name|rich_text",
              "textContent": "={{ $('All Inputs').first().json[\"First name\"] }}"
            },
            {
              "key": "email|email",
              "emailValue": "={{ $('All Inputs').first().json[\"Email\"] }}"
            },
            {
              "key": "Type|select",
              "selectValue": "Listing Ad"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "textContent": "Created through New Listing Ad Submission"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -9140,
        2880
      ],
      "id": "f9dbde95-4ab5-43ec-a33a-9b3f86252afd",
      "name": "Create new Contact",
      "alwaysOutputData": false,
      "notesInFlow": false,
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      },
      "onError": "continueErrorOutput"
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8088-8995-c96c2350b25d",
          "mode": "list",
          "cachedResultName": "Our Clients",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80888995c96c2350b25d"
        },
        "title": "={{ $json.name }}",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Contacts|relation",
              "relationValue": [
                "={{ $json.id }}"
              ]
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "textContent": "Created through New Listing Ad Submission"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -8920,
        2880
      ],
      "id": "537680d6-32dc-4e87-9e6b-2967f55e3ad4",
      "name": "Create new Client",
      "alwaysOutputData": false,
      "notesInFlow": false,
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      },
      "onError": "continueErrorOutput"
    },
    {
      "parameters": {
        "assignments": {
          "assignments": [
            {
              "id": "e3e1905c-f295-479b-8eb9-a2ddab717559",
              "name": "notion contact id",
              "value": "={{ $('Create new Contact').item.json.id }}",
              "type": "string"
            },
            {
              "id": "0170b413-ddcd-403b-9aef-dc2613fb63da",
              "name": "notion client id",
              "value": "={{ $json.id }}",
              "type": "string"
            },
            {
              "id": "18e83fc0-cd45-445c-af50-cd0328944eef",
              "name": "first name",
              "value": "={{ $('All Inputs').first().json[\"First name\"] }}",
              "type": "string"
            },
            {
              "id": "693b605d-0f1a-49aa-96c2-664e38d5cf47",
              "name": "email",
              "value": "={{ $('All Inputs').first().json.Email }}",
              "type": "string"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.set",
      "typeVersion": 3.4,
      "position": [
        -8700,
        2880
      ],
      "id": "48005fd9-c92b-4d0a-961a-d09b8c234835",
      "name": "set fields"
    },
    {
      "parameters": {
        "assignments": {
          "assignments": [
            {
              "id": "e3e1905c-f295-479b-8eb9-a2ddab717559",
              "name": "notion contact id",
              "value": "={{ $('Find Contact on Notion1').item.json.id }}",
              "type": "string"
            },
            {
              "id": "0170b413-ddcd-403b-9aef-dc2613fb63da",
              "name": "notion client id",
              "value": "={{ $('Find Contact on Notion1').item.json.property_clients_brands[0] }}",
              "type": "string"
            },
            {
              "id": "18e83fc0-cd45-445c-af50-cd0328944eef",
              "name": "first name",
              "value": "={{ $('Find Contact on Notion1').item.json.property_email_name }}",
              "type": "string"
            },
            {
              "id": "693b605d-0f1a-49aa-96c2-664e38d5cf47",
              "name": "email",
              "value": "={{ $('Find Contact on Notion1').item.json.property_email }}",
              "type": "string"
            },
            {
              "id": "0383e125-a50c-4f8a-b941-775491c6b7a7",
              "name": "headshot",
              "value": "={{ $json.property_headshot_bg }}",
              "type": "string"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.set",
      "typeVersion": 3.4,
      "position": [
        -8700,
        2680
      ],
      "id": "f60cc55d-6aee-4978-af33-4e3b380d4d11",
      "name": "set client fields"
    },
    {
      "parameters": {},
      "type": "n8n-nodes-base.merge",
      "typeVersion": 3,
      "position": [
        -8480,
        2780
      ],
      "id": "5ba799aa-16d2-4d11-983d-9982c177921e",
      "name": "Merge"
    },
    {
      "parameters": {
        "jsCode": "const processedItems = $('All Inputs').all().map(item => {\n  try {\n    // Get form data\n    const formData = item.json;\n    \n    // Extract form title (use Address or another primary field as the page title)\n    const pageTitle = formData.Address || \"Form Submission\";\n    \n    // Create content blocks for Notion\n    const contentBlocks = [];\n    \n    // Add title block\n    contentBlocks.push({\n      object: \"block\",\n      type: \"heading_1\",\n      heading_1: {\n        rich_text: [{\n          type: \"text\",\n          text: { content: pageTitle }\n        }]\n      }\n    });\n    \n    // Process each field in the form data\n    for (const [question, answer] of Object.entries(formData)) {\n      // Skip internal fields or metadata\n      if (question.startsWith('_') || question === 'markdown' || question === 'error') {\n        continue;\n      }\n      \n      // Format the question (remove asterisks and trim)\n      const formattedQuestion = question.replace(/\\*/g, '').trim();\n      \n      // Add question as heading\n      contentBlocks.push({\n        object: \"block\",\n        type: \"heading_3\",\n        heading_3: {\n          rich_text: [{\n            type: \"text\",\n            text: { content: formattedQuestion }\n          }]\n        }\n      });\n      \n      // Format the answer based on its type\n      let formattedAnswer;\n      let blockType = \"paragraph\";\n      \n      if (answer === undefined || answer === null) {\n        formattedAnswer = 'Not provided';\n      } else if (Array.isArray(answer)) {\n        formattedAnswer = answer.join(', ');\n      } else if (typeof answer === 'object') {\n        // Handle nested objects (like the emotions field)\n        formattedAnswer = Object.entries(answer)\n          .map(([key, val]) => `${key}: ${val}`)\n          .join(', ');\n      } else if (typeof answer === 'boolean') {\n        formattedAnswer = answer ? 'Yes' : 'No';\n      } else {\n        formattedAnswer = String(answer);\n      }\n      \n      // Check if this is an image URL\n      const isImage = typeof answer === 'string' && \n                (answer.includes('api.typeform.com/responses/files') || \n                 (answer.startsWith('http') && \n                  (answer.endsWith('.jpg') || answer.endsWith('.png') || \n                   answer.endsWith('.jpeg') || answer.endsWith('.gif'))));\n      \n      if (isImage) {\n        // Add image block\n        contentBlocks.push({\n          object: \"block\",\n          type: \"image\",\n          image: {\n            type: \"external\",\n            external: {\n              url: answer\n            }\n          }\n        });\n      } else {\n        // Add text block\n        contentBlocks.push({\n          object: \"block\",\n          type: \"paragraph\",\n          paragraph: {\n            rich_text: [{\n              type: \"text\",\n              text: { content: formattedAnswer }\n            }]\n          }\n        });\n      }\n    }\n    \n // Prepare data for Notion API\nitem.json.notionData = {\n  parent: {\n    // Your database ID\n    database_id: \"1b41d08c4f5a80c1a843f04215bd0fd0\"\n  },\n  properties: {\n    // Main field: Name (title field)\n    \"Name\": {\n      title: [\n        {\n          text: {\n            content: pageTitle\n          }\n        }\n      ]\n    },\n    // Second field: Request Type (single select)\n    \"Request Type\": {\n      select: {\n        name: \"Listing Ad\"\n      }\n    },\n    // Third field: Client (relation field)\n    \"Client\": {\n      relation: [\n        {\n          id: $('Merge').first().json[\"notion client id\"]\n        }\n      ]\n    },\n    // Fourth field: Submission Date (date field)\n    \"Submission Date\": {\n      date: {\n        start: new Date().toISOString()\n      }\n    },\n    // New relation field: Client Ad Campaigns\n    \"Client Ad Campaigns\": {\n      relation: [\n        {\n          id: $('Create New Listing Ad Campaign').first().json[\"id\"]\n        }\n      ]\n    }\n  },\n  children: contentBlocks\n};\n    \n    return item;\n  } catch (error) {\n    // Handle errors gracefully\n    console.error('Error processing form data:', error.message);\n    item.json.error = error.message;\n    return item;\n  }\n});\n\n// Return the processed items\nreturn processedItems;\n\n"
      },
      "type": "n8n-nodes-base.code",
      "typeVersion": 2,
      "position": [
        -7600,
        2780
      ],
      "id": "12736514-9050-46fa-b50d-8202761d3f8f",
      "name": "Code",
      "retryOnFail": true
    },
    {
      "parameters": {
        "resource": "databasePage",
        "operation": "update",
        "pageId": {
          "__rl": true,
          "value": "={{ $('Create New Listing Ad Campaign').first().json.id }}",
          "mode": "id"
        },
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Body Copy 1|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_body_copies[0].body_copy }}"
            },
            {
              "key": "Body Copy 2|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_body_copies[1].body_copy }}"
            },
            {
              "key": "Body Copy 3|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_body_copies[2].body_copy }}"
            },
            {
              "key": "Headline 1|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_headlines[0].headline }}"
            },
            {
              "key": "Headline 2|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_headlines[1].headline }}"
            },
            {
              "key": "Headline 3|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_headlines[2].headline }}"
            },
            {
              "key": "Headline 4|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_headlines[3].headline }}"
            },
            {
              "key": "Headline 5|rich_text",
              "textContent": "={{ $('Combine & Clean').item.json.ad_headlines[4].headline }}"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -6980,
        4640
      ],
      "id": "d9570ae9-eb28-43fb-b561-c7f26bb8a95a",
      "name": "Update Listing Ad Campaign with Copy",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.notion.com/v1/pages",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "Authorization",
              "value": "Bearer ntn_y77938235783grxbphRwEazxtixxh4eENsIdl2RRJyW9fy"
            },
            {
              "name": "Notion-Version",
              "value": "2022-06-28"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={{ $('Code').item.json.notionData }}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -7380,
        2780
      ],
      "id": "d0c59603-d541-43a6-bcfb-e3359c59c213",
      "name": "Create New Service Request",
      "retryOnFail": true
    },
    {
      "parameters": {
        "promptType": "define",
        "text": "=# YOUR ROLE\nYou are a consortium of the world's most renowned email copywriting specialists including Perry Belcher, Frank Kern, Ryan Deiss, Gary Halbert, Laura Belgray, Joanna Wiebe, and Ben Settle. You create emails so compelling they achieve 30%+ open rates and 5%+ click-through rates consistently.\n\n# INPUT DATA\nProperty Essence\nProperty Type: {{ $('All Inputs').first().json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice Point: {{ $('All Inputs').first().json['What is the listing price? (e.g., $599,000.)'] }}[RULE: Only reference if \"Show In Ad\" is selected]\nLocation: {{ $('All Inputs').first().json['City/Town'] }}, {{ $('All Inputs').first().json['State/Region/Province'] }}\nKey Feature: {{ $('All Inputs').first().json['What\\'s the biggest WOW factor about this home?'] }}\nKey Emotion: {{ $('All Inputs').first().json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}\nTarget Audience Composite\nCombined profile of all three buyer personas:\nPrimary: {{ $('All Inputs').first().json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary: {{ $('All Inputs').first().json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary: {{ $('All Inputs').first().json['Buyer Profile #3 (If another type of buyer applies.)'] }}\n\nPreviously Generated Content\nLead Ins:\n\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[0].lead_ins[0].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[0].lead_ins[1].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[0].lead_ins[2].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[1].lead_ins[0].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[1].lead_ins[1].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[1].lead_ins[2].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[2].lead_ins[0].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[2].lead_ins[1].lead_in }}\n{{ $('Lead In Agent').item.json.output.ad_lead_ins[2].lead_ins[2].lead_in }}\n\nBody Copies:\nBODY COPY 1: {{ $('Body Copy Agent').item.json.output.ad_body_copies[0].body_copy }}\nBODY COPY 2: {{ $('Body Copy Agent').item.json.output.ad_body_copies[1].body_copy }}\nBODY COPY 3: {{ $('Body Copy Agent').item.json.output.ad_body_copies[2].body_copy }}\n\nAgent Info: \nFirst Name: {{ $('Merge').item.json['first name'] }}\nEmail: {{ $('Merge').item.json.email }}\n\n\n# TASK\nCreate 3 high-converting email body copies that achieve 5%+ click-through rates. Each email should follow a proven email framework and have a distinct personality while maintaining brand consistency.\n\n# EMAIL PATTERNS\nUse these proven high-conversion patterns for real estate emails:\n\n1. Feature-Highlight Email:\n   * Open with a standout feature (size, location, etc.)\n   * Present bulleted list of key property features with checkmarks (✔)\n   * Emphasize location benefits\n   * Close with clear viewing call-to-action\n\n2. Value-Proposition Email:\n   * Open with market comparison (what makes this property special)\n   * List features with checkmarks (✔) focusing on value aspects\n   * Emphasize investment potential\n   * Close with clear viewing call-to-action\n\n3. Urgency-Driven Email:\n   * Open with time-sensitive messaging\n   * Reinforce key property features with checkmarks (✔)\n   * Emphasize rising demand factors\n   * Close with urgent viewing call-to-action\n\n# STYLE GUIDELINES\n\n## Length & Structure:\n* 150-300 words total (concise and impactful)\n* Use short paragraphs (1-3 sentences)\n* Format with strategic bold text for emphasis\n* Use emoji icons (🏡, ✨, 👉, etc.) to break up sections\n* Use checkmark lists (✔) for features and benefits\n* Include a clear call-to-action with reply prompt\n* End with signature, phone number, and company name\n\n## Email-Specific Styling:\n\nFOR SALES EMAILS:\n* Focus on benefits, scarcity, and urgency\n* Use words like: Limited offer, Exclusive access, Time-sensitive, Only X remaining\n\nFOR NEWSLETTER EMAILS:\n* Emphasize value, education, and relationship-building\n* Use words like: Insider update, Just discovered, Thought you'd appreciate, Quick tip\n\nFOR WELCOME EMAILS:\n* Highlight appreciation, next steps, and expectations\n* Use words like: Thrilled to have you, Your journey begins, Here's what to expect\n\nFOR FOLLOW-UP EMAILS:\n* Focus on helpfulness, value-add, and gentle persistence\n* Use words like: Checking in, Quick question, In case you missed, Just a reminder\n\n# LANGUAGE TECHNIQUES\n* Start with \"Hi {contact_first_name}\" personalization\n* Use **bold text** strategically for emphasis on key selling points\n* Incorporate emojis (🏡, ✨, 👉, 🚀, etc.) as visual section dividers\n* Use checkmarks (✔) before each feature in lists\n* Include specific property details (address, square footage)\n* Use phrases like \"rare opportunity,\" \"won't last long,\" and \"bargain\"\n* Create clear reply prompts in bold (\"Reply 'SHOW ME'\")\n* Always include signature with phone number and company name\n\n# EMAIL SEQUENCE APPROACH\nCreate a strategic 3-email sequence that builds interest and urgency:\n\n* Email 1 - Feature Introduction:\n  Focus on the property's standout features and unique selling points\n  Highlight size, layout, and special attributes\n  Use a subject line that emphasizes the property's most impressive feature\n  Example: \"🏡 A 2+Den Condo with 1,370 SqFt? See Inside!\"\n\n* Email 2 - Value Proposition:\n  Focus on the financial and lifestyle value of the property\n  Compare to market conditions (smaller, more expensive alternatives)\n  Use a subject line that emphasizes value and bargain\n  Example: \"💰 1,370 SqFt for This Price? A Bargain You Can't Ignore\"\n\n* Email 3 - Urgency Creation:\n  Focus on limited time and increasing demand\n  Reinforce key selling points but add urgency\n  Use a subject line that creates fear of missing out\n  Example: \"🚨 This Spacious Condo Won't Be Available for Long!\"\n\n# REQUIRED ELEMENTS\nEach email MUST include:\n* An emoji in the subject line\n* \"Hi {contact_first_name}\" greeting (including the curly braces)\n* Bold formatting for key property features\n* Emoji section headers (🏡, ✨, 👉, etc.)\n* Checkmark lists (✔) for property features  \n* Specific property details (address, square footage)\n* A clear call-to-action with specific reply prompt in quotes\n* Agent signature with phone number and company name\n\n# FORBIDDEN ELEMENTS\n* Never use generic real estate descriptions like \"cozy\" or \"charming\"\n* Never use ALL CAPS except for reply prompts\n* Never write emails longer than 300 words\n* Never omit the property's exact address\n* Never use subjective claims without specifics (e.g., \"great location\" without explaining why)\n* Never include multiple different calls-to-action\n* Never forget to include the agent's contact information\n\n# SUCCESS CRITERIA\nA high-converting real estate email will:\n* Include an emoji in the subject line for higher open rates\n* Highlight the property's standout feature in the first sentence\n* Use bold formatting to emphasize key selling points\n* Break content into scannable sections with emoji headers\n* Use checkmark lists (✔) for property features\n* Include specific details (exact square footage, address, etc.)\n* Emphasize location advantages and investment potential\n* Include a clear viewing call-to-action with a reply prompt\n* Create urgency through scarcity or limited time messaging\n* Close with complete agent contact information\n\n# HTML FORMATTING GUIDELINES\nFor the BodyHtml field:\n* Use `<strong>` tags for all bold text\n* Use `<br>` tags for line breaks\n* Use `<p>` tags for paragraphs\n* Use `<ul>` and `<li>` for feature lists\n* Preserve all emojis from the plain text version\n* Use `<h3>` tags for section headers\n* Include proper spacing and formatting\n* Make URLs clickable with `<a href=\"\">` tags\n\n# OUTPUT FORMAT\n{\n  \"emails\": [\n    {\n      \"Name\": \"Email 1\",\n      \"Subject\": \"COMPELLING SUBJECT LINE WITH EMOJI\",\n      \"Body\": \"FULL PLAIN TEXT EMAIL BODY\",\n      \"BodyHtml\": \"FULL HTML FORMATTED EMAIL BODY\"\n    },\n    {\n      \"Name\": \"Email 2\",\n      \"Subject\": \"COMPELLING SUBJECT LINE WITH EMOJI\",\n      \"Body\": \"FULL PLAIN TEXT EMAIL BODY\",\n      \"BodyHtml\": \"FULL HTML FORMATTED EMAIL BODY\"\n    },\n    {\n      \"Name\": \"Email 3\",\n      \"Subject\": \"COMPELLING SUBJECT LINE WITH EMOJI\",\n      \"Body\": \"FULL PLAIN TEXT EMAIL BODY\",\n      \"BodyHtml\": \"FULL HTML FORMATTED EMAIL BODY\"\n    }\n  ]\n}\n\n\nYou must respond ONLY with the requested JSON and no other text. Do not include explanations, introductions, or anything other than the JSON object.",
        "hasOutputParser": true,
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.agent",
      "typeVersion": 1.8,
      "position": [
        -7880,
        5200
      ],
      "id": "efb001ba-29a8-494f-baa9-99ceb4005d26",
      "name": "Email Agent"
    },
    {
      "parameters": {
        "jsonSchemaExample": "{\n \"emails\": [\n   {\n     \"Name\":\"Email 1\",\n     \"Subject\": \"\",\n     \"Body\": \"\",\n     \"BodyHtml\":\"\"\n   },\n   {\n     \"Name\":\"Email 1\",\n     \"Subject\": \"\",\n     \"Body\": \"\",\n     \"BodyHtml\":\"\"\n   },\n   {\n     \"Name\":\"Email 2\",\n     \"Subject\": \"\",\n     \"Body\": \"\",\n     \"BodyHtml\":\"\"\n   }\n ]\n}"
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserStructured",
      "typeVersion": 1.2,
      "position": [
        -7720,
        5420
      ],
      "id": "8e197d50-bdaa-4e20-b302-64954e0cd0c9",
      "name": "emails"
    },
    {
      "parameters": {
        "model": {
          "__rl": true,
          "value": "o3-mini-2025-01-31",
          "mode": "list",
          "cachedResultName": "o3-mini-2025-01-31"
        },
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.lmChatOpenAi",
      "typeVersion": 1.2,
      "position": [
        -7840,
        5420
      ],
      "id": "1746e9bd-042b-46dc-a5c7-2739660e3339",
      "name": "OpenAI Chat Model",
      "credentials": {
        "openAiApi": {
          "id": "OLHtLOP5C47dG8d5",
          "name": "OpenAi account"
        }
      }
    },
    {
      "parameters": {
        "jsCode": "// Process emails from input node and format for Notion\nconst emails = $('Email Agent').first().json.output.emails;\n\n// Create an array to hold all blocks for the Notion page\nconst notionBlocks = [];\n\n// Add title block\nnotionBlocks.push({\n  object: \"block\",\n  type: \"heading_1\",\n  heading_1: {\n    rich_text: [{\n      type: \"text\",\n      text: { content: \"3 Email Sequence Generated for New Listing Ad\" }\n    }]\n  }\n});\n\n// Add description paragraph\nnotionBlocks.push({\n  object: \"block\",\n  type: \"paragraph\",\n  paragraph: {\n    rich_text: [{\n      type: \"text\",\n      text: { content: \"Model Used: openai-o3-mini\" }\n    }]\n  }\n});\n\n// Process each email\nemails.forEach((email, emailIndex) => {\n  try {\n    const { Name, Subject, Body } = email;\n    \n    // Add divider between emails (except before the first one)\n    if (emailIndex > 0) {\n      notionBlocks.push({\n        object: \"block\",\n        type: \"divider\",\n        divider: {}\n      });\n    }\n    \n    // Add the email name as heading_1\n    notionBlocks.push({\n      object: \"block\",\n      type: \"heading_1\",\n      heading_1: {\n        rich_text: [{\n          type: \"text\",\n          text: { content: Name }\n        }]\n      }\n    });\n    \n    // Add subject as paragraph with bold formatting\n    notionBlocks.push({\n      object: \"block\",\n      type: \"paragraph\",\n      paragraph: {\n        rich_text: [{\n          type: \"text\",\n          text: { content: `Subject: ${Subject}` },\n          annotations: {\n            bold: true\n          }\n        }]\n      }\n    });\n    \n    // Process the email body\n    // Split into paragraphs\n    const paragraphs = Body.split('\\n\\n');\n    \n    paragraphs.forEach(paragraph => {\n      // Check if it's a feature section heading (starts with emoji + **)\n      if (paragraph.startsWith('🏡 **') || paragraph.startsWith('✨ **') || paragraph.startsWith('👉 **')) {\n        // This is a features heading section - use paragraph with bold formatting instead of heading\n        notionBlocks.push({\n          object: \"block\",\n          type: \"paragraph\",\n          paragraph: {\n            rich_text: [{\n              type: \"text\",\n              text: { content: paragraph.replace(/\\*\\*/g, '') },\n              annotations: {\n                bold: true\n              }\n            }]\n          }\n        });\n      } else if (paragraph.includes('✔')) {\n        // This is a list of features - convert to bulleted list\n        const listItems = paragraph.split('\\n');\n        \n        listItems.forEach(item => {\n          if (item.trim()) {\n            // Remove the ✔ symbol and any bold markdown\n            const cleanItem = item.trim().replace(/✔ /g, '').replace(/\\*\\*/g, '');\n            \n            notionBlocks.push({\n              object: \"block\",\n              type: \"bulleted_list_item\",\n              bulleted_list_item: {\n                rich_text: [{\n                  type: \"text\",\n                  text: { content: cleanItem }\n                }]\n              }\n            });\n          }\n        });\n      } else if (paragraph.includes('**Reply')) {\n        // Call to action - make it bold\n        notionBlocks.push({\n          object: \"block\",\n          type: \"paragraph\",\n          paragraph: {\n            rich_text: [{\n              type: \"text\",\n              text: { content: paragraph.replace(/\\*\\*/g, '') },\n              annotations: {\n                bold: true\n              }\n            }]\n          }\n        });\n      } else if (paragraph.startsWith('Best regards')) {\n        // Signature section - convert newlines to rich text\n        const signatureLines = paragraph.split('\\n');\n        const richTextArray = signatureLines.map((line, index) => ({\n          type: \"text\",\n          text: { content: index < signatureLines.length - 1 ? line + \"\\n\" : line }\n        }));\n        \n        notionBlocks.push({\n          object: \"block\",\n          type: \"paragraph\",\n          paragraph: {\n            rich_text: richTextArray\n          }\n        });\n      } else if (paragraph.trim()) {\n        // Regular paragraph\n        notionBlocks.push({\n          object: \"block\",\n          type: \"paragraph\",\n          paragraph: {\n            rich_text: [{\n              type: \"text\",\n              text: { content: paragraph }\n            }]\n          }\n        });\n      }\n    });\n    \n  } catch (error) {\n    // Handle errors gracefully\n    console.error(`Error processing email \"${email.Name}\":`, error.message);\n    notionBlocks.push({\n      object: \"block\",\n      type: \"paragraph\",\n      paragraph: {\n        rich_text: [{\n          type: \"text\",\n          text: { content: `Error processing email: ${error.message}` }\n        }]\n      }\n    });\n  }\n});\n\n// Return just the blocks for the API endpoint\nreturn { \n  json: { \n    children: notionBlocks \n  } \n};"
      },
      "type": "n8n-nodes-base.code",
      "typeVersion": 2,
      "position": [
        -7500,
        5200
      ],
      "id": "024f298c-cfab-47ae-b051-2bb03f8ad34a",
      "name": "Code3",
      "retryOnFail": true
    },
    {
      "parameters": {
        "method": "PATCH",
        "url": "=https://api.notion.com/v1/blocks/{{ $('Listing Ad - Create Task - Finalize Email Sequence').first().json.id }}/children",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "Authorization",
              "value": "Bearer ntn_y77938235783grxbphRwEazxtixxh4eENsIdl2RRJyW9fy"
            },
            {
              "name": "Notion-Version",
              "value": "2022-06-28"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={{ $('Code3').item.json }}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -7280,
        5200
      ],
      "id": "e4aca47b-329b-4d14-a3e0-8a036e2345a8",
      "name": "Update Email Task",
      "retryOnFail": true
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8010-9e47-c82ce7f1f1ea",
          "mode": "list",
          "cachedResultName": "Client Tasks",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80109e47c82ce7f1f1ea"
        },
        "title": "=Finalize the Ad Copy for {{ $('All Inputs').item.json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Status|status",
              "statusValue": "Ready To-Do"
            },
            {
              "key": "Priority|select",
              "selectValue": "Medium"
            },
            {
              "key": "Assignee|people",
              "peopleValue": [
                "17ad872b-594c-8163-b836-0002befd0f21"
              ]
            },
            {
              "key": "Tags|multi_select",
              "multiSelectValue": [
                "New Listing"
              ]
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Update Listing Ad Campaign').first().json.id }}"
              ]
            },
            {
              "key": "Due|date",
              "includeTime": false,
              "date": "={{ (function(){let d=new Date();let b=2;while(b>0){d.setDate(d.getDate()+1);if(d.getDay()!==0&&d.getDay()!==6)b--;}return d.toISOString();})() }}"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_1",
              "textContent": "Objective: Create Google Drive Folder"
            },
            {
              "type": "heading_2",
              "textContent": "Please add a link to the Folder created."
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -9800,
        4260
      ],
      "id": "e7f5d6b4-961c-42de-abbb-0913e726740c",
      "name": "Listing Ad - Create Task - Write Body Copy",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8010-9e47-c82ce7f1f1ea",
          "mode": "list",
          "cachedResultName": "Client Tasks",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80109e47c82ce7f1f1ea"
        },
        "title": "=Design the Ad Creatives for {{ $('All Inputs').first().json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Status|status",
              "statusValue": "=Ready To-Do"
            },
            {
              "key": "Priority|select",
              "selectValue": "=Medium"
            },
            {
              "key": "Assignee|people",
              "peopleValue": [
                "1afd872b-594c-81e9-a20d-00020d9c9f7c"
              ]
            },
            {
              "key": "Tags|multi_select",
              "multiSelectValue": [
                "New Listing"
              ]
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Update Listing Ad Campaign').first().json.id }}"
              ]
            },
            {
              "key": "Due|date",
              "includeTime": false,
              "date": "={{ (function(){let d=new Date();let b=2;while(b>0){d.setDate(d.getDate()+1);if(d.getDay()!==0&&d.getDay()!==6)b--;}return d.toISOString();})() }}"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_1",
              "textContent": "Objective: Please design the Ad Creatives for this new listing."
            },
            {
              "type": "heading_2",
              "textContent": "These are the images uploaded by the client:"
            },
            {
              "type": "image",
              "url": "={{ $('All Inputs').item.json['Upload THE BEST raw listing photo.'] }}"
            },
            {
              "type": "image",
              "url": "={{ $('All Inputs').item.json['Upload THE SECOND BEST raw listing photos.'] }}"
            },
            {
              "type": "=image",
              "url": "={{ $('All Inputs').item.json['Upload THE THIRD BEST raw listing photo.'] }}"
            },
            {
              "type": "image",
              "url": "={{ $('All Inputs').item.json['Upload THE FOURTH BEST raw listing photo.'] }}"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -9580,
        4260
      ],
      "id": "bd366a6f-212b-4fd7-a162-0bbffa443be4",
      "name": "Listing Ad - Create Task  - Design Ad Creatives",
      "retryOnFail": true,
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
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8010-9e47-c82ce7f1f1ea",
          "mode": "list",
          "cachedResultName": "Client Tasks",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80109e47c82ce7f1f1ea"
        },
        "title": "=Finalize E-Mail Nurture Sequence for {{ $('All Inputs').first().json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Status|status",
              "statusValue": "=Ready To-Do"
            },
            {
              "key": "Priority|select",
              "selectValue": "=Medium"
            },
            {
              "key": "Assignee|people",
              "peopleValue": [
                "17ad872b-594c-8163-b836-0002befd0f21"
              ]
            },
            {
              "key": "Tags|multi_select",
              "multiSelectValue": [
                "New Listing"
              ]
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Update Listing Ad Campaign').first().json.id }}"
              ]
            },
            {
              "key": "Due|date",
              "includeTime": false,
              "date": "={{ (function(){let d=new Date();let b=2;while(b>0){d.setDate(d.getDate()+1);if(d.getDay()!==0&&d.getDay()!==6)b--;}return d.toISOString();})() }}"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_3",
              "richText": true,
              "text": {
                "text": [
                  {
                    "text": "Objective: Please write the E-Mail sequence for this new Listing Ad submission.",
                    "annotationUi": {
                      "code": false,
                      "color": "yellow"
                    }
                  }
                ]
              }
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -9360,
        4260
      ],
      "id": "1e9f2d2e-c952-45d0-b105-b7309854e8a4",
      "name": "Listing Ad - Create Task - Finalize Email Sequence",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8010-9e47-c82ce7f1f1ea",
          "mode": "list",
          "cachedResultName": "Client Tasks",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80109e47c82ce7f1f1ea"
        },
        "title": "=Send deliverables to the client for review and approval for  {{ $('All Inputs').first().json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Status|status",
              "statusValue": "BackLog"
            },
            {
              "key": "Priority|select",
              "selectValue": "=Medium"
            },
            {
              "key": "Assignee|people",
              "peopleValue": [
                "1afd872b-594c-81e9-a20d-00020d9c9f7c"
              ]
            },
            {
              "key": "Tags|multi_select",
              "multiSelectValue": [
                "New Listing"
              ]
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Update Listing Ad Campaign').first().json.id }}"
              ]
            },
            {
              "key": "Due|date",
              "includeTime": false,
              "date": "={{ (function(){let d=new Date();let b=2;while(b>0){d.setDate(d.getDate()+1);if(d.getDay()!==0&&d.getDay()!==6)b--;}return d.toISOString();})() }}"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_1",
              "textContent": "The Client Delivery Page has been created:"
            },
            {
              "richText": true,
              "text": {
                "text": [
                  {
                    "text": "={{ $json.url }}",
                    "isLink": true,
                    "annotationUi": {
                      "bold": true
                    }
                  }
                ]
              }
            },
            {
              "textContent": "Please add the “New Client Ad Delivery” Template to it and adjust the content and publish to be able to share with client"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -8920,
        4260
      ],
      "id": "7740ee46-d3a5-4160-b8a9-151505e2771c",
      "name": "Listing Ad - Create Task  - Send Ad Content to Client for Approval",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8010-9e47-c82ce7f1f1ea",
          "mode": "list",
          "cachedResultName": "Client Tasks",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80109e47c82ce7f1f1ea"
        },
        "title": "=Add Sequence into client’s CRM for {{ $('All Inputs').first().json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Status|status",
              "statusValue": "BackLog"
            },
            {
              "key": "Priority|select",
              "selectValue": "=Medium"
            },
            {
              "key": "Assignee|people",
              "peopleValue": [
                "17ad872b-594c-8163-b836-0002befd0f21",
                "1afd872b-594c-81e9-a20d-00020d9c9f7c"
              ]
            },
            {
              "key": "Tags|multi_select",
              "multiSelectValue": [
                "New Listing"
              ]
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Update Listing Ad Campaign').first().json.id }}"
              ]
            },
            {
              "key": "Due|date",
              "includeTime": false,
              "date": "={{ (function(){let d=new Date();let b=2;while(b>0){d.setDate(d.getDate()+1);if(d.getDay()!==0&&d.getDay()!==6)b--;}return d.toISOString();})() }}"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_1",
              "textContent": "Objective: Please upload the E-Mail Sequence into client’s CRM, "
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -8700,
        4260
      ],
      "id": "c1acbff9-785a-4eee-8b82-83c3e240d6c7",
      "name": "Listing Ad - Create Task - Add Emails into Clients CRM",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1491d08c-4f5a-8010-9e47-c82ce7f1f1ea",
          "mode": "list",
          "cachedResultName": "Client Tasks",
          "cachedResultUrl": "https://www.notion.so/1491d08c4f5a80109e47c82ce7f1f1ea"
        },
        "title": "=Schedule Ad to be Published on Meta for {{ $('All Inputs').first().json.Address }} {{ $('All Inputs').first().json['Address line 2'] }}",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Client|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Status|status",
              "statusValue": "BackLog"
            },
            {
              "key": "Priority|select",
              "selectValue": "=Medium"
            },
            {
              "key": "Assignee|people",
              "peopleValue": [
                "17ad872b-594c-8163-b836-0002befd0f21"
              ]
            },
            {
              "key": "Tags|multi_select",
              "multiSelectValue": [
                "New Listing"
              ]
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Update Listing Ad Campaign').first().json.id }}"
              ]
            },
            {
              "key": "Due|date",
              "includeTime": false,
              "date": "={{ (function(){let d=new Date();let b=3;while(b>0){d.setDate(d.getDate()+1);if(d.getDay()!==0&&d.getDay()!==6)b--;}return d.toISOString();})() }}"
            }
          ]
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "heading_1",
              "textContent": "Objective: Please upload Schedule the Launch in Meta,"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -8480,
        4260
      ],
      "id": "45cdf448-a425-40d5-9ba4-5261f066b2ae",
      "name": "Listing Ad - Create Task - Schedule Ad on Meta",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "assignments": {
          "assignments": [
            {
              "id": "2ddbb046-c97d-4b2e-949e-b9875b043f88",
              "name": "template1.headline",
              "value": "={{ $json.output.template1.headline }}",
              "type": "string"
            },
            {
              "id": "a0068fa2-1e88-468b-b701-b33ef052884b",
              "name": "template1.agent_name",
              "value": "={{ $json.output.template1.agent_name }}",
              "type": "string"
            },
            {
              "id": "03d4be2b-e99c-4f02-a281-1fd854bc531e",
              "name": "template1.instagram_handle",
              "value": "={{ $json.output.template1.instagram_handle }}",
              "type": "string"
            },
            {
              "id": "cbacb0ae-2b81-4f93-8256-917ab73b07c3",
              "name": "template2.headline",
              "value": "={{ $json.output.template2.headline }}",
              "type": "string"
            },
            {
              "id": "52439763-9c92-4020-a540-946289848899",
              "name": "template2.bed_bath_type",
              "value": "={{ $json.output.template2.bed_bath_type }}",
              "type": "string"
            },
            {
              "id": "68510394-fe67-4a57-9920-588271a0f516",
              "name": "template2.available_city",
              "value": "={{ $json.output.template2.available_city }}",
              "type": "string"
            },
            {
              "id": "0d0c1718-9bfe-428f-b7a9-4c498e9d114c",
              "name": "template3.headline",
              "value": "={{ $json.output.template3.headline }}",
              "type": "string"
            },
            {
              "id": "755ebb2d-56ba-49c5-b992-51c97f3d5728",
              "name": "template3.text_list_1",
              "value": "={{ $json.output.template3.text_list_1 }}",
              "type": "string"
            },
            {
              "id": "2720d389-ed0e-4217-ae9c-351c8e6eb9d4",
              "name": "template3.text_list_2",
              "value": "={{ $json.output.template3.text_list_2 }}",
              "type": "string"
            },
            {
              "id": "19ee7310-d821-4529-bb0e-9820d597a55c",
              "name": "template3.text_list_3",
              "value": "={{ $json.output.template3.text_list_3 }}",
              "type": "string"
            },
            {
              "id": "8c31e547-aa42-442b-94f6-160c2cb9a3ce",
              "name": "template4.address",
              "value": "={{ $json.output.template4.address }}",
              "type": "string"
            },
            {
              "id": "bcea50c1-24a6-419d-bcd6-182fb9d4a467",
              "name": "template4.beds_baths",
              "value": "={{ $json.output.template4.beds_baths }}",
              "type": "string"
            },
            {
              "id": "092f50b7-1644-46c8-baa7-7d2616a3b2fc",
              "name": "template4.price",
              "value": "={{ $json.output.template4.price }}",
              "type": "string"
            },
            {
              "id": "043511ae-df67-4c8a-a6fc-0b8b40c3aad0",
              "name": "template4.just_listed",
              "value": "={{ $json.output.template4.just_listed }}",
              "type": "string"
            },
            {
              "id": "20fe602c-31ac-403d-bcbc-dc45f9a3d851",
              "name": "template4.text_phone_number",
              "value": "={{ $json.output.template4.text_phone_number }}",
              "type": "string"
            },
            {
              "id": "c6aed5c1-8180-47ca-b911-642982d1b6ec",
              "name": "template4.text_mail",
              "value": "={{ $json.output.template4.text_mail }}",
              "type": "string"
            },
            {
              "id": "d12f9363-75d8-44cd-9e00-b6a0ebea9b8b",
              "name": "template5.beds_baths",
              "value": "={{ $json.output.template5.beds_baths }}",
              "type": "string"
            },
            {
              "id": "85f67f67-2451-4852-8453-2db453549078",
              "name": "template5.for_sale_city",
              "value": "={{ $json.output.template5.for_sale_city }}",
              "type": "string"
            },
            {
              "id": "5aabe314-7066-4cb3-ae4c-0e3b9526c779",
              "name": "template6.beds_text",
              "value": "={{ $json.output.template6.beds_text }}",
              "type": "string"
            },
            {
              "id": "c7478014-7f8b-4bef-a84b-10927bf1372e",
              "name": "template6.baths_text",
              "value": "={{ $json.output.template6.baths_text }}",
              "type": "string"
            },
            {
              "id": "f34a9e75-e48e-42e9-83a2-26e58111068d",
              "name": "template6.address",
              "value": "={{ $json.output.template6.address }}",
              "type": "string"
            },
            {
              "id": "c6e6b412-5b55-4908-8928-7ab6f2bf2eb3",
              "name": "template6.address",
              "value": "={{ $json.output.template6.address }}",
              "type": "string"
            },
            {
              "id": "cc1c0049-9f3d-4a4a-b250-b67a20f73fb4",
              "name": "template7.just_listed",
              "value": "={{ $json.output.template7.just_listed }}",
              "type": "string"
            },
            {
              "id": "5cadb98f-51aa-4854-adab-c0346fed3c62",
              "name": "template7.beds_baths",
              "value": "={{ $json.output.template7.beds_baths }}",
              "type": "string"
            },
            {
              "id": "e4d0f7a8-d3b0-4dc8-88aa-4dcac8733003",
              "name": "template7.property_type",
              "value": "={{ $json.output.template7.property_type }}",
              "type": "string"
            },
            {
              "id": "00eb71c2-a9fc-417c-a21e-122b883c4a2f",
              "name": "image1",
              "value": "={{ $('All Inputs').first().json[\"Upload THE BEST raw listing photo.\"] }}",
              "type": "string"
            },
            {
              "id": "747bfee4-59df-4045-aa9e-22a28401bcb1",
              "name": "image2",
              "value": "={{$('All Inputs').first().json['Upload THE SECOND BEST raw listing photos.']}}",
              "type": "string"
            },
            {
              "id": "f6fc3ab0-589b-43a8-9e53-883aef875477",
              "name": "image3",
              "value": "={{ $('All Inputs').first().json[\"Upload THE THIRD BEST raw listing photo.\"] }}",
              "type": "string"
            },
            {
              "id": "6aa16ad0-c579-4e6a-89b2-e1e021a2d41c",
              "name": "image4",
              "value": "={{ $('All Inputs').first().json[\"Upload THE FOURTH BEST raw listing photo.\"] }}",
              "type": "string"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.set",
      "typeVersion": 3.4,
      "position": [
        -6680,
        5200
      ],
      "id": "d410a4f0-adf2-49e9-b13d-33554a5165b0",
      "name": "Edit Fields"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/2f2097c1-d6df-4839-81ae-56a335ddbb05/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"facebook-post\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"headline\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.headline }}\"\n    },\n    \"text_list_1\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.text_list_1 }}\"\n    },\n    \"text_list_2\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.text_list_2 }}\"\n    },\n    \"text_list_3\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.text_list_3 }}\"\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n    },\n    \"property_image_1\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"}\n\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -5580,
        5200
      ],
      "id": "fb000983-05b0-4a4a-a493-5fed4d90e136",
      "name": "Template #3"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/0374a4cf-4c4a-4b07-9fda-0b640c480ecf/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"facebook-post\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"property_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"bed_bath_type\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template2.bed_bath_type }}\"\n\n    },\n    \"headline\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template2.headline }}\"\n\n    },\n    \"available_city\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template2.available_city }}\"\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -6020,
        5200
      ],
      "id": "aa3c8f77-7615-41f3-a1cc-d1831c31c11a",
      "name": "Template #2"
    },
    {
      "parameters": {
        "jsonSchemaExample": "{\n  \"template1\": {\n    \"headline\": \"string\",\n    \"agent_name\": \"string\",\n    \"instagram_handle\": \"@name\"\n  },\n  \"template2\": {\n    \"headline\": \"string\",\n    \"bed_bath_type\": \"string\",\n    \"available_city\": \"string\"\n  },\n  \"template3\": {\n    \"headline\": \"string\",\n    \"text_list_1\": \"string\",\n    \"text_list_2\": \"string\",\n    \"text_list_3\": \"string\"\n  },\n  \"template4\": {\n    \"address\": \"string\",\n    \"beds_baths\": \"string\",\n    \"price\": \"string\",\n    \"just_listed\": \"string\",\n    \"text_phone_number\": \"string\",\n    \"text_mail\": \"string\"\n  },\n  \"template5\": {\n    \"beds_baths\": \"string\",\n    \"for_sale_city\": \"string\"\n  },\n  \"template6\": {\n    \"beds_text\": \"string\",\n    \"baths_text\": \"string\",\n    \"address\": \"string\"\n  },\n  \"template7\": {\n    \"just_listed\": \"string\",\n    \"beds_baths\": \"string\",\n    \"property_type\": \"string\"\n  }\n}"
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserStructured",
      "typeVersion": 1.2,
      "position": [
        -6980,
        5420
      ],
      "id": "2e4ae904-2d20-4b3a-b571-e76acd748feb",
      "name": "Structured Output Parser"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/85c4ab4a-7b35-48a0-a753-e1fe86d0a944/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"facebook-post\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"agent_headshot\": {\n      \"image_url\": \"{{$('All Inputs').first().json['Upload THE SECOND BEST raw listing photos.']}}\"\n    },\n    \"agent_name\": {\n      \"payload\": \"{{ $('Edit Fields').item.json.template1.agent_name }}\"\n    },\n    \"headline\": {\n      \"payload\": \"{{ $('Edit Fields').item.json.template1.headline }}\"\n    },\n    \"instagram_handle\": {\n      \"payload\": \"@{{ $('Edit Fields').item.json.template1.instagram_handle }}\"\n    },\n    \"property_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -6460,
        5200
      ],
      "id": "4e5f2e0b-d934-4a6f-b446-2bd323821ee0",
      "name": "Template #1"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/89949082-a1f3-472a-84e9-3b6b9200765f/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"facebook-post\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"bg_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"text_mail\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.text_mail }}\"\n\n    },\n    \"text_phone_number\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.text_phone_number }}\"\n\n    },\n    \"image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n\n    },\n    \"price\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.price }}\"\n\n    },\n    \"beds_baths\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.beds_baths }}\"\n\n    },\n    \"just_listed\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.just_listed }}\"\n\n    },\n    \"address\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.address }}\"\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -5140,
        5200
      ],
      "id": "29fc3be2-0596-424e-a996-6b923e0d43f1",
      "name": "Template #4"
    },
    {
      "parameters": {
        "promptType": "define",
        "text": "={{ JSON.stringify( $node[\"All Inputs\"].json) }}\n\nAgent Details:\nName: {{ $('Merge').first().json['first name'] }}\nEmail: {{ $('Merge').first().json.email }}\n\nMore Context:\n# INPUT DATA\nProperty Essence\nProperty Type: {{ $('All Inputs').first().json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice Point: {{ $('All Inputs').first().json['What is the listing price? (e.g., $599,000.)'] }}[RULE: Only reference if \"Show In Ad\" is selected]\nLocation: {{ $('All Inputs').first().json['City/Town'] }}, {{ $('All Inputs').first().json['State/Region/Province'] }}\nKey Feature: {{ $('All Inputs').first().json['What\\'s the biggest WOW factor about this home?'] }}\nKey Emotion: {{ $('All Inputs').first().json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}\nTarget Audience Composite\nCombined profile of all three buyer personas:\nPrimary: {{ $('All Inputs').first().json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary: {{ $('All Inputs').first().json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary: {{ $('All Inputs').first().json['Buyer Profile #3 (If another type of buyer applies.)'] }}\n\nPreviously Generated Content\nLead Ins:\n\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[0].lead_ins[0].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[0].lead_ins[1].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[0].lead_ins[2].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[1].lead_ins[0].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[1].lead_ins[1].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[1].lead_ins[2].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[2].lead_ins[0].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[2].lead_ins[1].lead_in }}\n{{ $('Lead In Agent').first().json.output.ad_lead_ins[2].lead_ins[2].lead_in }}\n\nBody Copies:\nBODY COPY 1: {{ $('Body Copy Agent').first().json.output.ad_body_copies[0].body_copy }}\nBODY COPY 2: {{ $('Body Copy Agent').first().json.output.ad_body_copies[1].body_copy }}\nBODY COPY 3: {{ $('Body Copy Agent').first().json.output.ad_body_copies[2].body_copy }}\n\nAgent Info: \nFirst Name: {{ $('Merge').first().json['first name'] }}\nEmail: {{ $('Merge').first().json.email }}",
        "hasOutputParser": true,
        "options": {
          "systemMessage": "=# Real Estate Template Text Generator\n\nYou are a specialized real estate marketing text generator for Abyssale templates. Your job is to analyze property data and generate template-specific text that perfectly matches the specified formats and character limits.\n\n## Instructions\n\n1. Analyze all available property data in the input\n2. Generate appropriate text for each template field based on the style guides\n3. Ensure all text fits the specified character limits for each field\n4. Return a JSON object with all generated text fields, organized by template\n\n## Input Data\n\nThe input will be a property data object with information such as:\n- Basic details (address, bedrooms, bathrooms, property type, price)\n- Features (pool, views, renovations, etc.)\n- Location benefits (schools, parks, proximity)\n- Interior and exterior details\n- Agent/brokerage information\n\n## Output Format\n\nReturn a JSON object with this exact structure:\n\n\n{\n  \"template1\": {\n    \"headline\": \"string\",\n    \"agent_name\": \"string\",\n    \"instagram_handle\": \"string\"\n  },\n  \"template2\": {\n    \"headline\": \"string\",\n    \"bed_bath_type\": \"string\",\n    \"available_city\": \"string\"\n  },\n  \"template3\": {\n    \"headline\": \"string\",\n    \"text_list_1\": \"string\",\n    \"text_list_2\": \"string\",\n    \"text_list_3\": \"string\"\n  },\n  \"template4\": {\n    \"address\": \"string\",\n    \"beds_baths\": \"string\",\n    \"price\": \"string\",\n    \"just_listed\": \"string\",\n    \"text_phone_number\": \"string\",\n    \"text_mail\": \"string\"\n  },\n  \"template5\": {\n    \"beds_baths\": \"string\",\n    \"for_sale_city\": \"string\"\n  },\n  \"template6\": {\n    \"beds_text\": \"string\",\n    \"baths_text\": \"string\",\n    \"address\": \"string\"\n  },\n  \"template7\": {\n    \"just_listed\": \"string\",\n    \"beds_baths\": \"string\",\n    \"property_type\": \"string\"\n  }\n}\n\n\n## Style Guides with Character Limits\n\n### Template 1 (Realtor Profile with Property Headline)\n- **headline**: Format as \"[Key Feature] + [Key Feature] + [Key Feature] = Your Perfect [Property Type] Just Listed!\"\n- Character limit: 50-70 characters (font size 35)\n- Example: \"Lake Views + Pool + Space = Your Perfect Family Home Just Listed!\"\n- Select the 3 most impressive features from the property data\n- Choose appropriate property type label (Home, Family Home, Luxury Condo, etc.)\n- **agent_name**: Use the agent's full name as provided\n- **instagram_handle**: Use the agent's social media handle without the \"@\" symbol\n- IMPORTANT: If no social media handle is available, use the property address with no spaces as a failsafe\n- Example: If address is \"100 Morrison St\", use \"100MorrisonSt\" as the instagram_handle\n\n### Template 2 (Direct Property Ad)\n- **headline**: Format as \"ATTENTION [CITY] [TARGET DEMOGRAPHIC]\"\n- All capital letters, character limit: 30-40 characters (font size 65)\n- Example: \"ATTENTION VAUGHAN GROWING FAMILIES\"\n- **bed_bath_type**: Format as \"[X] BED + [Y] BATH [PROPERTY TYPE]\"\n- All capital letters, character limit: 20-30 characters (font size 70)\n- Example: \"3 BED + 3 BATH TOWNHOUSE\"\n- **available_city**: Format as \"NOW AVAILABLE IN [CITY]\"\n- All capital letters, character limit: 20-30 characters (font size 70)\n- Example: \"NOW AVAILABLE IN VAUGHAN\"\n\n### Template 3 (Detailed Features with Bullet Points)\n- **headline**: Format as \"Attn: [City] [Target Demographic], [X] Bed + [Y] Bath [Property Type] [New Listing]\"\n- Character limit: 60-80 characters (font size 60)\n- Example: \"Attn: Vaughan Growing Families, 3 Bed + 3 Bath Townhouse [New Listing]\"\n- **text_list_1**: Focus on interior features\n- Format as \"[Verb] [FEATURE] with [detail] & [detail]\"\n- Character limit: 50-70 characters (font size 40)\n- Example: \"Enjoy STUNNING open-concept living with hardwood floors & pot lights\"\n- **text_list_2**: Focus on location benefits\n- Format as \"[QUALITY] location steps away from [amenity], [amenity] & [amenity]\"\n- Character limit: 70-90 characters (font size 40)\n- Example: \"PRIME location steps away from top-rated schools, local parks & family-friendly restaurants\"\n- **text_list_3**: Focus on quality/move-in readiness\n- Format as \"[CONDITION] home with [feature], [feature] & [feature]\"\n- Character limit: 75-95 characters (font size 40)\n- Example: \"Move-in READY home with high-end finishes: Granite counters, stone fireplace & modern kitchen\"\n\n### Template 4 (Traditional Listing)\n- **address**: Format as street number and street name\n- Example: \"93 Allegranza Av\"\n- **beds_baths**: Format as \"[X] BEDS + [Y] BATHS\"\n- All capital letters, character limit: 15-20 characters (font size 46)\n- Example: \"3 BEDS + 3 BATHS\"\n- **price**: Format with $ symbol, commas, and decimal places\n- Example: \"$867,999.00\"\n- **just_listed**: Always \"JUST LISTED\"\n- **text_phone_number**: Brokerage name\n- Example: \"SkyGroup\"\n- **text_mail**: Agent email\n- Example: \"stephen@theskygroup.ca\"\n\n### Template 5 (Collage with Red Banner)\n- **beds_baths**: Format as \"NEW [X] BED + [Y] BATH [PROPERTY TYPE]\"\n- All capital letters, character limit: 25-35 characters (font size 60)\n- Example: \"NEW 3 BED + 3 BATH TOWNHOUSE\"\n- **for_sale_city**: Format as \"FOR SALE IN [CITY]\"\n- All capital letters, character limit: 15-25 characters (font size 60)\n- Example: \"FOR SALE IN VAUGHAN\"\n\n### Template 6 (Elegant Property Showcase)\n- **beds_text**: Format as \"[X] Bedrooms\"\n- Title case, character limit: 8-15 characters (font size 60)\n- Example: \"3 Bedrooms\"\n- **baths_text**: Format as \"[Y] Bathrooms\"\n- Title case, character limit: 8-15 characters (font size 60)\n- Example: \"3 Bathrooms\"\n- **address**: Full property address including street name and type\n- Example: \"93 Allegranza Avenue\"\n\n### Template 7 (Modern Gallery Grid)\n- **just_listed**: Always \"Just Listed\" (title case)\n- **beds_baths**: Format as \"[X] Bed + [Y] Bath\"\n- Title case, character limit: 12-18 characters (font size 50)\n- Example: \"3 Bed + 3 Bath\"\n- **property_type**: Just the property type in title case\n- Character limit: 5-15 characters (font size 50)\n- Example: \"Townhouse\"\n\n## Target Demographics Guide\n\nDetermine target demographic based on:\n- \"Growing Families\" - 3+ bedrooms, near schools/parks\n- \"Luxury Buyers\" - High price, luxury finishes\n- \"First-Time Buyers\" - Lower price, condo/townhouse\n- \"Downsizers\" - 1-2 bedrooms, main floor living\n- \"Smart Investors\" - Good rental potential\n\n## Property Type Guide\n\nDetermine property type label based on:\n- For condos: \"Condo\" or \"Luxury Condo\"\n- For townhouses: \"Townhome\" or \"Family Townhome\"\n- For houses: \"Home\", \"Family Home\", or \"Luxury Home\"\n\n## Feature Selection Guide\n\nSelect top features based on:\n- Views (lake, mountain, city)\n- Outdoor amenities (pool, backyard, garden)\n- Location benefits (walkability, parks, schools)\n- Interior highlights (modern, spacious, renovated)\n- Luxury elements (high-end finishes, premium features)\n\nBe mindful of text length for all templates. When faced with a choice, prioritize clarity and readability over including more details. If a template text field is approaching the upper character limit, simplify the language to fit within the constraints.\n\nReturn only the structured JSON output with no additional commentary."
        }
      },
      "type": "@n8n/n8n-nodes-langchain.agent",
      "typeVersion": 1.8,
      "position": [
        -7060,
        5200
      ],
      "id": "d7095447-d2ea-4f23-8001-6719428217b6",
      "name": "Creative Generator"
    },
    {
      "parameters": {
        "resource": "block",
        "blockId": {
          "__rl": true,
          "value": "={{ $('Listing Ad - Create Task  - Design Ad Creatives').first().json.id }}",
          "mode": "id"
        },
        "blockUi": {
          "blockValues": [
            {
              "type": "image",
              "url": "={{ $('Template #1').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #1 Vertical').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #2').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #2 Vertical').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #3').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #3 Vertical').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #4').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #4 Vertical').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #5').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #5 Vertical').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #6').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #6 Vertical').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #7').first().json.file.url }}"
            },
            {
              "type": "image",
              "url": "={{ $('Template #7 Vertical').first().json.file.url }}"
            }
          ]
        }
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -3380,
        5200
      ],
      "id": "26d6b912-31bb-48b2-82a2-fba29f023ffa",
      "name": "Update Listing Ad Creative Task, with New Images Generated1",
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
        "resource": "databasePage",
        "operation": "get",
        "pageId": {
          "__rl": true,
          "value": "={{ $json.property_clients_brands[0] }}",
          "mode": "id"
        }
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -8920,
        2680
      ],
      "id": "6f352547-438c-4693-81d3-d46179314ae5",
      "name": "Find Client",
      "alwaysOutputData": true,
      "notesInFlow": false,
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
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/85c4ab4a-7b35-48a0-a753-e1fe86d0a944/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"instagram-story\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"agent_headshot\": {\n      \"image_url\": \"{{$('All Inputs').first().json['Upload THE SECOND BEST raw listing photos.']}}\"\n\n    },\n    \"agent_name\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template1.agent_name }}\"\n\n    },\n    \"headline\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template1.headline }}\"\n\n    },\n    \"instagram_handle\": {\n      \"payload\": \"@{{ $('Edit Fields').first().json.template1.instagram_handle }}\"\n\n    },\n    \"property_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -6240,
        5200
      ],
      "id": "580302fc-cf62-46a6-9384-c4ded54e4121",
      "name": "Template #1 Vertical"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/0374a4cf-4c4a-4b07-9fda-0b640c480ecf/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"instagram-story\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"property_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"bed_bath_type\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template2.bed_bath_type }}\"\n\n    },\n    \"headline\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template2.headline }}\"\n\n    },\n    \"available_city\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template2.available_city }}\"\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -5800,
        5200
      ],
      "id": "95311eea-b14d-45c0-9545-02f958f8b5d4",
      "name": "Template #2 Vertical"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/2f2097c1-d6df-4839-81ae-56a335ddbb05/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"instagram-story\",\n \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"headline\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.headline }}\"\n    },\n    \"text_list_1\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.text_list_1 }}\"\n    },\n    \"text_list_2\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.text_list_2 }}\"\n    },\n    \"text_list_3\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template3.text_list_3 }}\"\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n    },\n    \"property_image_1\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"}\n\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -5360,
        5200
      ],
      "id": "99d639bb-d1f7-47bd-96f5-dcc6bf60ff20",
      "name": "Template #3 Vertical"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/89949082-a1f3-472a-84e9-3b6b9200765f/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"instagram-story\",\n   \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"bg_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"text_mail\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.text_mail }}\"\n\n    },\n    \"text_phone_number\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.text_phone_number }}\"\n\n    },\n    \"image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n\n    },\n    \"price\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.price }}\"\n\n    },\n    \"beds_baths\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.beds_baths }}\"\n\n    },\n    \"just_listed\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.just_listed }}\"\n\n    },\n    \"address\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template4.address }}\"\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -4920,
        5200
      ],
      "id": "014a8399-141c-42c2-9b22-a8f93f98bd64",
      "name": "Template #4 Vertical",
      "onError": "continueErrorOutput"
    },
    {
      "parameters": {
        "method": "PATCH",
        "url": "=https://api.notion.com/v1/blocks/{{ $('Listing Ad - Create Task - Schedule Ad on Meta').first().json.id }}/children",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "Authorization",
              "value": "Bearer ntn_y77938235783grxbphRwEazxtixxh4eENsIdl2RRJyW9fy"
            },
            {
              "name": "Notion-Version",
              "value": "2022-06-28"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "{\n  \"children\": [\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_1\",\n      \"heading_1\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Objective: Please upload Schedule the Launch in Meta\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_2\",\n      \"heading_2\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"QA CHECKLIST: \"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"orange_background\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Please Ensure This Check Lists Has Been Checked Off Prior To Marking The Task As Complete/Done.\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": true,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"orange_background\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_3\",\n      \"heading_3\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"1. CAMPAIGN LEVEL\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Set Objective:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Leads\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Special Ad Category:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Housing \"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"(required for compliance)\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": true,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Campaign Name: \"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Follow Naming Convention: New Listing | Lead | ADDRESS\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_3\",\n      \"heading_3\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"2. AD SET LEVEL\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Daily Budget:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Matches client budget request on typeform (e.g., $10/day)\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Schedule:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Morning of requested launch date 6am\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\",\n        \"children\": [\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"Set to run until sold or with end date based on client preference in typeform\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\"\n            }\n          }\n        ]\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Location Targeting:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Ensure pin is dropped within the city radius requested on the typeform - in none requested use the listing address. Broad area targeting (e.g., \\\"Toronto + Durham Region\\\" with 15+ mi radius)\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Select The Correct Business Account\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Conversion Location:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" On-Facebook Instant Form\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Optimization & Delivery:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Leads\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_3\",\n      \"heading_3\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"3. AD LEVEL\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Facebook Page + Instagram Account:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Correct accounts selected\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Ad Name:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" New Listing | Lead | ADDRESS\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Creative\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"3 Dynamic Images added\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Video:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Optional – only if provided by client\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Copy Review\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Primary Text (Body Copy):\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" 2 Copies Added \"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Headline:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" 2 Headlines\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"CTA Button:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" \\\"Learn More\\\"\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_3\",\n      \"heading_3\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"4. INSTANT FORM QA\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Form Title:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" New Listing | Lead | ADDRESS\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Intro Text:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\",\n        \"children\": [\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"PREMIERE:\"\n                  },\n                  \"annotations\": {\n                    \"bold\": true,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\",\n              \"children\": [\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"Get The Listing Details Below\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"Here's what will be sent to your email…\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"➡️ All Listing Photos\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"➡️ Address\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"➡️ Pricing\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"➡️ Floor Plan\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                }\n              ]\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"LEADGENIUS/ FREE ADS\"\n                  },\n                  \"annotations\": {\n                    \"bold\": true,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\",\n              \"children\": [\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"Get The Listing Details Below **\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                }\n              ]\n            }\n          }\n        ]\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Fields:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Name, Email, Phone only\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Custom Questions:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\",\n        \"children\": [\n          {\n            \"object\": \"block\",\n            \"type\": \"paragraph\",\n            \"paragraph\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"When are you looking to move?\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"bulleted_list_item\",\n            \"bulleted_list_item\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"ASAP\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"color\": \"default\"\n            }\n          },\n             {\n            \"object\": \"block\",\n            \"type\": \"bulleted_list_item\",\n            \"bulleted_list_item\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"3-9 Months\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"bulleted_list_item\",\n            \"bulleted_list_item\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"12 Months+\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"bulleted_list_item\",\n            \"bulleted_list_item\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"I'm Not, I'm A Local Neighbour\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"color\": \"default\"\n            }\n          }\n        ]\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Privacy Policy URL added\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Thank You Screen:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\",\n        \"children\": [\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"PREMIERE:\"\n                  },\n                  \"annotations\": {\n                    \"bold\": true,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\",\n              \"children\": [\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"Thanks, you're all set.\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"Check Your Email For The Details!\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                }\n              ]\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"LEADGENIUS/ FREE ADS\"\n                  },\n                  \"annotations\": {\n                    \"bold\": true,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\",\n              \"children\": [\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"Thanks, you're all set.\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"Stay Tuned For The Details!\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                }\n              ]\n            }\n          }\n        ]\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Test Lead Submitted:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\",\n        \"children\": [\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"PREMIERE:\"\n                  },\n                  \"annotations\": {\n                    \"bold\": true,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\",\n              \"children\": [\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"If FUB - Testing Happens In CRM Once Scheduled *** (No Action Needed In Ad Set Up)\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                },\n                {\n                  \"object\": \"block\",\n                  \"type\": \"paragraph\",\n                  \"paragraph\": {\n                    \"rich_text\": [\n                      {\n                        \"type\": \"text\",\n                        \"text\": {\n                          \"content\": \"If LOFTY -  Use Meta Test Tool to confirm CRM\"\n                        },\n                        \"annotations\": {\n                          \"bold\": false,\n                          \"italic\": false,\n                          \"strikethrough\": false,\n                          \"underline\": false,\n                          \"code\": false,\n                          \"color\": \"default\"\n                        }\n                      }\n                    ],\n                    \"color\": \"default\"\n                  }\n                }\n              ]\n            }\n          }\n        ]\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_3\",\n      \"heading_3\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"5. LINK & RESOURCE CHECK\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Click All Links:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Working no broken links & shortened if needed\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\",\n        \"children\": [\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"Branded Photo Tour Link\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"Google Drive (Public Access) - Photos\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"Floor Plan Link\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"Calendly Link\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\"\n            }\n          }\n        ]\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Check Listing Price Location:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" if the client said \\\"only in email\\\" ensure no mention of the listing price in the ad copy or creative\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_3\",\n      \"heading_3\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"6. CRM Access & Integration With Meta \"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Premiere Only (separate QA process for Drip Set Up) \"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": true,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Have Access To The Client's CRM (Login Details)\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Login To Client's CRM\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" - follow up with them if verification codes are needed\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Check That FB Account Is Integrated With CRM\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"paragraph\",\n      \"paragraph\": {\n        \"rich_text\": [],\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"heading_3\",\n      \"heading_3\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"7. COMPLIANCE & FINAL REVIEW\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"color\": \"default\",\n        \"is_toggleable\": false\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Confirm Housing Compliance:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" No exclusionary or discriminatory language\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Spelling & Grammar:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Final check done\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Pull Ad Preview Link:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Add to Notion Board\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Meta Approval Check:\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          },\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \" Confirm ad is scheduled & under review\"\n            },\n            \"annotations\": {\n              \"bold\": false,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\"\n      }\n    },\n    {\n      \"object\": \"block\",\n      \"type\": \"to_do\",\n      \"to_do\": {\n        \"rich_text\": [\n          {\n            \"type\": \"text\",\n            \"text\": {\n              \"content\": \"Internal Team is Notified ad is scheduled for launch (launch date)\"\n            },\n            \"annotations\": {\n              \"bold\": true,\n              \"italic\": false,\n              \"strikethrough\": false,\n              \"underline\": false,\n              \"code\": false,\n              \"color\": \"default\"\n            }\n          }\n        ],\n        \"checked\": false,\n        \"color\": \"default\",\n        \"children\": [\n          {\n            \"object\": \"block\",\n            \"type\": \"to_do\",\n            \"to_do\": {\n              \"rich_text\": [\n                {\n                  \"type\": \"text\",\n                  \"text\": {\n                    \"content\": \"Client Notified: ad is scheduled for launch\"\n                  },\n                  \"annotations\": {\n                    \"bold\": false,\n                    \"italic\": false,\n                    \"strikethrough\": false,\n                    \"underline\": false,\n                    \"code\": false,\n                    \"color\": \"default\"\n                  }\n                }\n              ],\n              \"checked\": false,\n              \"color\": \"default\"\n            }\n          }\n        ]\n      }\n    }\n  ]\n} ",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -6020,
        4640
      ],
      "id": "32bbbc19-9770-421c-9e2d-28366a63deab",
      "name": "Add QA Checklist to Schedule Task"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/541fa704-1fb5-4a08-9e4a-2d6abc8ad071/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"facebook-post\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"property_image_4\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n\n    },\n    \"property_image_3\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image3 }}\"\n\n    },\n    \"property_image_1\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image4 }}\"\n\n    },\n    \"beds_baths\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template5.beds_baths }}\"\n\n    },\n    \"for_sale_city\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template5.for_sale_city }}\"\n\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -4700,
        5200
      ],
      "id": "2d362120-fa83-489b-b503-d25188c0f13d",
      "name": "Template #5"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/541fa704-1fb5-4a08-9e4a-2d6abc8ad071/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"instagram-story\",\n    \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"property_image_4\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n\n    },\n    \"property_image_3\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image3 }}\"\n\n    },\n    \"property_image_1\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image4 }}\"\n\n    },\n    \"beds_baths\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template5.beds_baths }}\"\n\n    },\n    \"for_sale_city\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template5.for_sale_city }}\"\n\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -4480,
        5200
      ],
      "id": "dd3c45f1-94b2-4ada-98dd-e0d66514429c",
      "name": "Template #5 Vertical"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/add3e545-1856-4184-8d17-f4e49685043c/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"facebook-post\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"property_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n    },\n    \"beds_text\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template6.beds_text }}\"\n    },\n    \"baths_text\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template6.baths_text }}\"\n    },\n    \"address\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template6.address }}\"\n\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -4260,
        5200
      ],
      "id": "8adfd601-2c69-4a7f-9460-49e0b2d8736d",
      "name": "Template #6"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/add3e545-1856-4184-8d17-f4e49685043c/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"instagram-story\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#FFFFFF\"\n    },\n    \"property_image\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n    },\n    \"beds_text\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template6.beds_text }}\"\n    },\n    \"baths_text\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template6.baths_text }}\"\n    },\n    \"address\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template6.address }}\"\n\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -4040,
        5200
      ],
      "id": "77a96bb3-bcf7-4e09-a1ec-ddbd2097033c",
      "name": "Template #6 Vertical"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/74a3f34e-943e-4a12-8fd2-c21a214ecf81/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"facebook-post\",\n  \"elements\": {\n    \"root\": {\n      \"background_color\": \"#ffffff\"\n    },\n    \"white_rectangle\": {\n      \"background_color\": \"#ffffff\",\n      \"hidden\": false\n    },\n    \"property_image_1\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"property_image_6\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n\n    },\n    \"property_image_5\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n\n    },\n    \"property_image_3\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image3 }}\"\n\n    },\n    \"property_image_4\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image4 }}\"\n\n    },\n    \"beds_baths\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template7.beds_baths }}\"\n\n    },\n    \"property_type\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template7.property_type }}\"\n\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -3820,
        5200
      ],
      "id": "ed193aec-f907-4d94-9fe4-0bad62cfc033",
      "name": "Template #7"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.abyssale.com/banner-builder/74a3f34e-943e-4a12-8fd2-c21a214ecf81/generate",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "x-api-key",
              "value": "UvViGZbuex7xLAKWtJAMY19BM4NIo7rlaaoUo4BC"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"template_format_name\": \"instagram-story\",\n  \"elements\": {\n    \"property_image_1\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n    },\n    \"property_image_6\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image1 }}\"\n\n    },\n    \"property_image_2\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n\n    },\n    \"property_image_5\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image2 }}\"\n\n    },\n    \"property_image_3\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image3 }}\"\n\n    },\n    \"property_image_4\": {\n      \"image_url\": \"{{ $('Edit Fields').first().json.image4 }}\"\n\n    },\n    \"beds_baths\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template7.beds_baths }}\"\n\n    },\n    \"property_type\": {\n      \"payload\": \"{{ $('Edit Fields').first().json.template7.property_type }}\"\n\n    }\n  }\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -3600,
        5200
      ],
      "id": "d5db572f-3a90-43b9-90fb-61160b5b07cb",
      "name": "Template #7 Vertical"
    },
    {
      "parameters": {
        "jsCode": "// Code Node: Prepare Tasks Array - Optimized Version\n\n// --- Get Required IDs from Previous Nodes ---\nconst clientRelationId = $('Merge').first().json['notion client id'];\nconst campaignRelationId = $('Create New Listing Ad Campaign').first().json.id;\nconst serviceRequestId = $('Create New Service Request').first().json.id;\n\n// --- Get Address Information ---\nconst address = $('Typeform Trigger').first().json.Address || '';\nconst addressLine2 = $('Typeform Trigger').first().json['Address line 2'] || '';\nconst fullAddress = `${address} ${addressLine2}`.trim();\nconst deliverablesPageUrl = $('Create Client Deliverables Page').first().json.url;\n\n// --- Assignee IDs (Single ID for optimization) ---\nconst assigneeID = \"135d872b-594c-815e-8bb4-0002be26fee3\";\n\n// --- Due Date Calculation ---\nfunction getBusinessDaysDueDate(businessDays) {\n  let d = new Date();\n  let addedDays = 0;\n  \n  while (addedDays < businessDays) {\n    d.setDate(d.getDate() + 1);\n    // Skip weekends (0 = Sunday, 6 = Saturday)\n    if (d.getDay() !== 0 && d.getDay() !== 6) {\n      addedDays++;\n    }\n  }\n  \n  return d.toISOString().split('T')[0]; // Return YYYY-MM-DD format\n}\n\nconst dueDate2Days = getBusinessDaysDueDate(2);\nconst dueDate3Days = getBusinessDaysDueDate(3);\n\n// --- Helper Function for Blocks ---\nfunction formatBlock(type, content, options = {}) {\n  const block = { object: \"block\", type: type };\n  const data = {};\n  \n  // Text-based blocks\n  if (['paragraph', 'heading_1', 'heading_2', 'heading_3', 'bulleted_list_item', \n       'numbered_list_item', 'toggle', 'quote', 'callout'].includes(type)) {\n    \n    if (options.contentRich) {\n      data.rich_text = options.contentRich;\n    } else {\n      data.rich_text = [{ type: \"text\", text: { content: content || \"\" } }];\n      if (options.annotations) {\n        data.rich_text[0].annotations = { ...options.annotations };\n      }\n    }\n    \n    if (options.color) data.color = options.color;\n    if (options.is_toggleable) data.is_toggleable = options.is_toggleable;\n  \n  // To-do blocks\n  } else if (type === 'to_do') {\n    if (typeof content === 'string') {\n      data.rich_text = [{ type: \"text\", text: { content: content } }];\n    } else if (Array.isArray(content)) {\n      data.rich_text = content;\n    } else {\n      data.rich_text = [{ type: \"text\", text: { content: content || \"\" } }];\n    }\n    \n    if (options.annotations && options.at) {\n      if (data.rich_text && data.rich_text[0]?.text?.content) {\n        const originalText = data.rich_text[0].text.content;\n        const firstPart = originalText.substring(0, options.at);\n        const secondPart = originalText.substring(options.at);\n        data.rich_text = [\n          { type: \"text\", text: { content: firstPart }, annotations: { ...options.annotations } },\n          { type: \"text\", text: { content: secondPart } }\n        ];\n      }\n    } else if (options.annotations && data.rich_text && data.rich_text[0]) {\n      data.rich_text[0].annotations = { ...options.annotations };\n    }\n    \n    data.checked = options.checked || false;\n    if (options.color) data.color = options.color;\n    if (options.children && Array.isArray(options.children)) {\n      data.children = options.children.map(child => formatBlock(child.type, child.content, child));\n    }\n  \n  // Image blocks\n  } else if (type === 'image') {\n    data.type = \"external\";\n    data.external = { url: options.url || content || 'https://via.placeholder.com/150' };\n  \n  // Divider blocks (no data needed)\n  } else if (type === 'divider') {\n    // Empty\n  }\n  \n  block[type] = data;\n  return block;\n}\n\n// --- Define Task Content Blocks ---\nconst taskContents = {\n  // Ad Copy\n  finalizeAdCopy: [\n    formatBlock(\"heading_1\", \"Objective: Finalize Ad Copy\"),\n    formatBlock(\"paragraph\", \"AI-generated content will be appended here upon successful generation.\")\n  ],\n  \n  // Creatives \n  designCreatives: [\n    formatBlock(\"heading_1\", \"Objective: Please design the Ad Creatives for this new listing.\"),\n    formatBlock(\"heading_2\", \"These are the images uploaded by the client:\"),\n    formatBlock(\"image\", $('Typeform Trigger').first().json['Upload THE BEST raw listing photo.'] || 'placeholder_url_1'),\n    formatBlock(\"image\", $('Typeform Trigger').first().json['Upload THE SECOND BEST raw listing photos.'] || 'placeholder_url_2'),\n    formatBlock(\"image\", $('Typeform Trigger').first().json['Upload THE THIRD BEST raw listing photo.'] || 'placeholder_url_3'),\n    formatBlock(\"image\", $('Typeform Trigger').first().json['Upload THE FOURTH BEST raw listing photo.'] || 'placeholder_url_4'),\n    formatBlock(\"paragraph\", \"Generated ad creatives will be appended below later.\")\n  ],\n  \n  // Email Sequence\n  finalizeEmail: [\n    formatBlock(\"heading_1\", \"Objective: Finalize Email Sequence\"),\n    formatBlock(\"paragraph\", \"AI-generated emails will be appended here upon successful generation.\")\n  ],\n  \n  // Client Deliverables\n  sendToClient: [\n    formatBlock(\"heading_1\", \"The Client Delivery Page has been created:\"),\n    formatBlock(\"paragraph\", \"\", { \n      contentRich: [{ \n        type: 'text', \n        text: { \n          content: deliverablesPageUrl || 'Deliverables Page URL Not Found', \n          link: deliverablesPageUrl ? { url: deliverablesPageUrl } : null \n        }, \n        annotations: { bold: true } \n      }] \n    }),\n    formatBlock(\"paragraph\", \"Please add the New Client Ad Delivery Template to it and adjust the content and publish to be able to share with client\")\n  ],\n  \n  // CRM Upload\n  addToCRM: [\n    formatBlock(\"heading_1\", \"Objective: Please upload the E-Mail Sequence into client's CRM,\")\n  ],\n  \n  // Meta Launch\n  scheduleAd: [\n    formatBlock(\"heading_1\", \"Objective: Please upload Schedule the Launch in Meta\")\n  ]\n};\n\n// --- Task Definitions ---\nconst taskDefinitions = [\n  {\n    title: `Finalize Ad Copy for ${fullAddress}`,\n    assignee: assigneeID,\n    dueDate: dueDate2Days,\n    blocks: taskContents.finalizeAdCopy,\n    status: \"Ready To-Do\"\n  },\n  {\n    title: `Design the Ad Creatives for ${fullAddress}`,\n    assignee: assigneeID,\n    dueDate: dueDate2Days,\n    blocks: taskContents.designCreatives,\n    status: \"Ready To-Do\"\n  },\n  {\n    title: `Finalize E-Mail Nurture Sequence for ${fullAddress}`,\n    assignee: assigneeID,\n    dueDate: dueDate2Days,\n    blocks: taskContents.finalizeEmail,\n    status: \"Ready To-Do\"\n  },\n  {\n    title: `Send deliverables to the client for review and approval for ${fullAddress}`,\n    assignee: assigneeID,\n    dueDate: dueDate2Days,\n    blocks: taskContents.sendToClient,\n    status: \"BackLog\"\n  },\n  {\n    title: `Add Sequence into client's CRM for ${fullAddress}`,\n    assignee: assigneeID,\n    dueDate: dueDate2Days,\n    blocks: taskContents.addToCRM,\n    status: \"BackLog\"\n  },\n  {\n    title: `Schedule Ad to be Published on Meta for ${fullAddress}`,\n    assignee: assigneeID,\n    dueDate: dueDate3Days,\n    blocks: taskContents.scheduleAd,\n    status: \"BackLog\"\n  }\n];\n\n// --- Create Final Tasks Array ---\nconst tasksToCreate = taskDefinitions.map(def => ({\n  // Task title and content\n  taskTitle: def.title,\n  taskBlocks: def.blocks,\n  \n  // Task properties\n  taskAssignee: [def.assignee],\n  taskDueDate: def.dueDate,\n  taskStatus: def.status,\n  taskPriority: \"Medium\",\n  taskTags: [\"New Listing\"],\n  \n  // Relations\n  taskClientRelationId: [clientRelationId],\n  taskCampaignRelationId: [campaignRelationId],\n  taskServiceRequestRelationId: [serviceRequestId]\n}));\n\n// Return the prepared tasks\nreturn tasksToCreate;"
      },
      "type": "n8n-nodes-base.code",
      "typeVersion": 2,
      "position": [
        -7160,
        2780
      ],
      "id": "676e0899-d65f-496d-9acb-1c5fc96fe2e9",
      "name": "Code - Prepare Tasks Array"
    },
    {
      "parameters": {
        "jsCode": "// Code Node: Aggregate Task IDs\n\nconst results = {\n  adCopyTaskId: null,\n  creativeTaskId: null,\n  emailTaskId: null,\n  sendToClientTaskId: null,\n  addEmailsToCRMTaskId: null,\n  scheduleAdTaskId: null\n};\n\nconst createdTasks = $input.all();\n\nfor (const item of createdTasks) {\n  // Adjust this path based on the ACTUAL output structure of your Notion Create Page node\n  // It might be item.json.properties['Task Title'].title[0].plain_text or just item.json.name\n  // Check the output of 'Notion - Create Tasks Loop' node to be sure.\n  let taskTitle = '';\n  try {\n     taskTitle = item.json?.properties?.['Task Title']?.title?.[0]?.plain_text || item.json?.name || '';\n  } catch (e) {\n     console.warn(\"Error accessing title property for task item:\", JSON.stringify(item.json));\n  }\n\n  if (!taskTitle) {\n      console.warn(\"Task item missing title:\", JSON.stringify(item.json));\n      continue; // Skip if title isn't found\n  }\n\n  // Identify task and store ID\n  if (taskTitle.includes(\"Finalize Ad Copy\")) {\n    results.adCopyTaskId = item.json.id;\n  } else if (taskTitle.includes(\"Design the Ad Creatives\")) {\n    results.creativeTaskId = item.json.id;\n  } else if (taskTitle.includes(\"E-Mail\")) {\n    results.emailTaskId = item.json.id;\n  } else if (taskTitle.includes(\"Send deliverables to the client\")) {\n     results.sendToClientTaskId = item.json.id;\n  } else if (taskTitle.includes(\"Add Sequence into client’s CRM\")) {\n     results.addEmailsToCRMTaskId = item.json.id;\n  } else if (taskTitle.includes(\"Schedule Ad to be Published\")) {\n     results.scheduleAdTaskId = item.json.id;\n  }\n}\n\n// Output a SINGLE item containing all the identified IDs\nreturn [{ json: results }];\n"
      },
      "type": "n8n-nodes-base.code",
      "typeVersion": 2,
      "position": [
        -6720,
        2780
      ],
      "id": "54975c1e-0489-4f48-a794-1680dee87324",
      "name": "Code - Aggregate Task IDs"
    },
    {
      "parameters": {
        "formId": "vujZTuzj"
      },
      "type": "n8n-nodes-base.typeformTrigger",
      "typeVersion": 1.1,
      "position": [
        -10020,
        2880
      ],
      "id": "ef553fa1-6d47-4bb0-95d2-a37e087bdf80",
      "name": "Typeform Trigger",
      "webhookId": "d1ce9a57-8aa4-4f97-a607-8f65ec953cb9",
      "credentials": {
        "typeformApi": {
          "id": "hZKxcP6jseCjV38y",
          "name": "Typeform account"
        }
      }
    },
    {
      "parameters": {
        "jsCode": "// This code transforms the new webhook output format to match the Typeform output format\n// For use in n8n's Function node (JavaScript)\n\n// Return the transformed data\nreturn [\n  {\n    // Basic information\n    \"First name\": $input.first().json.body.first_name,\n    \"Last name\": $input.first().json.body.last_name,\n    \"Email\": $input.first().json.body.email,\n    \"Address\": $input.first().json.body.address_line_1 + ($input.first().json.body.address_line_2 ? `, ${$input.first().json.body.address_line_2}` : \"\"),\n    \"City/Town\": $input.first().json.body.city,\n    \"State/Region/Province\": $input.first().json.body.state_province_region,\n    \"Zip/Post Code\": $input.first().json.body.zip_postal_code,\n    \"Country\": $input.first().json.body.country,\n    \n    // Ad details\n    \"*What Is The Objective Of Your Ad?*\": $input.first().json.body.ad_objective === \"leads\" ? \"I Want To Generate Leads\" : $input.first().json.body.ad_objective,\n    \"Which location would you like to target with the ad? \": $input.first().json.body.ad_target_locations,\n    \"Would you like to run this ad until it's sold or until a specific date? \": $input.first().json.body.ad_duration_type === \"specific\" ? \"Specific Date\" : \"Until Sold\",\n    \"End Date For Ad \": $input.first().json.body.ad_end_date,\n    \n    // Property details\n    \"What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)\": \n      $input.first().json.body.property_type.charAt(0).toUpperCase() + $input.first().json.body.property_type.slice(1),\n    \"What is the listing price? (e.g., $599,000.)\": $input.first().json.body.listing_price,\n    \"Do you want the listing price shown in the ad or only in the email follow-up? (Show In Ad, Only Show In Email Sequence)\": \n      $input.first().json.body.show_price_in_ad ? \"Show In Ad\" : \"Only Show In Email Sequence\",\n    \"How many bedrooms? \": $input.first().json.body.bedrooms,\n    \"How many bathrooms? \": $input.first().json.body.bathrooms,\n    \n    // Feature details\n    \"What are the top 3-5 selling features of this home? (Examples: Open-concept kitchen, large backyard, lake view, school zone, etc.)\": \n      $input.first().json.body.top_features,\n    \"What's the biggest WOW factor about this home?\": $input.first().json.body.wow_factor,\n    \"What's one thing people LOVE when they walk in?\": $input.first().json.body.first_impression,\n    \"What are some things people don't immediately notice but should?\": $input.first().json.body.hidden_gems,\n    \n    // Buyer profiles\n    \"Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)\": \n      $input.first().json.body.ideal_buyer,\n    \"Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)\": $input.first().json.body.lifestyle,\n    \"Buyer Profile #3 (If another type of buyer applies.)\": \"\",\n    \n    // Amenities\n    \"What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)\": \n      $input.first().json.body.local_amenities.map(amenity => amenity.charAt(0).toUpperCase() + amenity.slice(1)),\n    \n    // Selling points\n    \"What makes this home better than similar listings in the area?\": $input.first().json.body.comparison_to_similar_listings,\n    \"Are there any recent upgrades/renovations? (Example: \\\"New roof (2023), updated kitchen, renovated ensuite.\\\")\": \n      $input.first().json.body.recent_upgrades,\n    \"What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)\": \n      $input.first().json.body.ad_target_emotion.charAt(0).toUpperCase() + $input.first().json.body.ad_target_emotion.slice(1),\n    \n    // Investment info\n    \"Is this an investment property?\": $input.first().json.body.is_investment_property,\n    \"What is your total daily budget for ads? \": `${$input.first().json.body.ad_daily_budget}/day`,\n    \n    // Photos\n    \"Upload THE BEST raw listing photo.\": $input.first().json.body.photo_url_1,\n    \"Upload THE SECOND BEST raw listing photos.\": $input.first().json.body.photo_url_2,\n    \"Upload THE THIRD BEST raw listing photo.\": $input.first().json.body.photo_url_3,\n    \"Upload THE FOURTH BEST raw listing photo.\": $input.first().json.body.photo_url_4,\n    \n    // Additional details\n    \"Copy & Paste the current listing description here. (We'll refine and optimize it for ad effectiveness!)\": \"\",\n    \"Any additional details we should know? (Unique selling points, seller situation, or requests.)\": \n      $input.first().json.body.is_investment_property ? \n        `Investment property with potential rental income of ${$input.first().json.body.potential_rental_income}/month. ${$input.first().json.body.upcoming_development_plans || \"\"}` : \"\",\n    \n    // Tour URL\n    \"Enter Branded Photo Tour / 3D Tour URL \": $input.first().json.body.branded_photo_tour_url\n  }\n];"
      },
      "type": "n8n-nodes-base.code",
      "typeVersion": 2,
      "position": [
        -10020,
        2680
      ],
      "id": "9cb08fc3-7bb3-4efd-a52b-122fbf78d8db",
      "name": "Code1"
    },
    {
      "parameters": {
        "httpMethod": "POST",
        "path": "8ebc8e81-fdf6-4ff7-a5cb-322802cea5bd",
        "options": {}
      },
      "type": "n8n-nodes-base.webhook",
      "typeVersion": 2,
      "position": [
        -10240,
        2680
      ],
      "id": "e89f1616-9e35-49c2-986b-1012463a8f0e",
      "name": "Webhook",
      "webhookId": "8ebc8e81-fdf6-4ff7-a5cb-322802cea5bd"
    },
    {
      "parameters": {
        "method": "POST",
        "url": "https://api.notion.com/v1/pages",
        "sendHeaders": true,
        "headerParameters": {
          "parameters": [
            {
              "name": "Authorization",
              "value": "Bearer ntn_y77938235783grxbphRwEazxtixxh4eENsIdl2RRJyW9fy"
            },
            {
              "name": "Notion-Version",
              "value": "2022-06-28"
            }
          ]
        },
        "sendBody": true,
        "specifyBody": "json",
        "jsonBody": "={\n  \"parent\": {\n    \"database_id\": \"1491d08c-4f5a-8010-9e47-c82ce7f1f1ea\"\n  },\n  \"icon\": {\n    \"type\": \"emoji\",\n    \"emoji\": \"📝\"\n  },\n  \"properties\": {\n    \"Task Title\": {\n      \"title\": [\n        {\n          \"text\": {\n            \"content\": \"{{ $json.taskTitle ?? 'Untitled Task' }}\"\n          }\n        }\n      ]\n    },\n    \"Client\": {\n       \"relation\":\n         {{ JSON.stringify($json.taskClientRelationId.map(id => ({ id: id })) ) }}\n    },\n    \"Client Ad Campaigns\": {\n       \"relation\":\n         {{ JSON.stringify($json.taskCampaignRelationId.map(id => ({ id: id })) ) }}\n     },\n     \"Assignee\": {\n        \"people\":\n           {{ JSON.stringify($json.taskAssignee.map(id => ({ id: id })) ) }}\n     },\n    \"Due\": {\n       \"date\": {{ $json.taskDueDate ? JSON.stringify({ start: $json.taskDueDate }) : null }}\n    },\n    \"Tags\": {\n        \"multi_select\":\n           {{ JSON.stringify($json.taskTags.map(tag => ({ name: tag })) ) }}\n    },\n    \"Status\": {\n        \"status\": {\n            \"name\": \"{{ $json.taskStatus }}\"\n        }\n    },\n    \"Priority\": {\n        \"select\": {\n            \"name\": \"{{ $json.taskPriority }}\"\n        }\n    },\n    \"⚠️ Service Portal Requests\": {\n       \"relation\":\n         {{ JSON.stringify($json.taskServiceRequestRelationId.map(id => ({ id: id })) ) }}\n    }\n  },\n  \"children\": {{ JSON.stringify($json.taskBlocks) }}\n}",
        "options": {}
      },
      "type": "n8n-nodes-base.httpRequest",
      "typeVersion": 4.2,
      "position": [
        -6940,
        2780
      ],
      "id": "0c08a278-511f-4a6e-83b7-3274bfec7894",
      "name": "Create Tasks",
      "retryOnFail": true
    },
    {
      "parameters": {
        "resource": "databasePage",
        "databaseId": {
          "__rl": true,
          "value": "1c01d08c-4f5a-80b2-a3ea-c867420dcda2",
          "mode": "list",
          "cachedResultName": "Client Deliverables",
          "cachedResultUrl": "https://www.notion.so/1c01d08c4f5a80b2a3eac867420dcda2"
        },
        "title": "={{ $('Merge').first().json[\"first name\"] }} - {{ $('All Inputs').first().json.Address }} ",
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Our Clients|relation",
              "relationValue": [
                "={{ $('Merge').first().json[\"notion client id\"] }}"
              ]
            },
            {
              "key": "Type|select",
              "selectValue": "New Listing Ad"
            },
            {
              "key": "Client Ad Campaigns|relation",
              "relationValue": [
                "={{ $('Create New Listing Ad Campaign').first().json['id'] }}"
              ]
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -7820,
        2780
      ],
      "id": "2dfdd360-0b41-4cf1-8f25-16fa6e7d3396",
      "name": "Create Client Deliverables Page",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    },
    {
      "parameters": {
        "promptType": "define",
        "text": "=NEW LISTING DATA:\nProperty Essence\nProperty Type: {{ $('All Inputs').first().json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice Point: {{ $('All Inputs').first().json['What is the listing price? (e.g., $599,000.)'] }}[RULE: Only reference if \"Show In Ad\" is selected]\nLocation: {{ $('All Inputs').first().json['City/Town'] }}, {{ $('All Inputs').first().json['State/Region/Province'] }}\nKey Feature: {{ $('All Inputs').first().json['What\\'s the biggest WOW factor about this home?'] }}\nKey Emotion: {{ $('All Inputs').first().json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}\nTarget Audience Composite\nCombined profile of all three buyer personas:\nPrimary: {{ $('All Inputs').first().json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary: {{ $('All Inputs').first().json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary: {{ $('All Inputs').first().json['Buyer Profile #3 (If another type of buyer applies.)'] }}\n\nFull Address: {{ $('All Inputs').first().json['Address'] }}, {{ $('All Inputs').first().json['City/Town'] }}, {{ $('All Inputs').first().json['State/Region/Province'] }}, {{ $('All Inputs').first().json['Zip/Post Code'] }}\nProperty Type: {{ $('All Inputs').first().json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice: {{ $('All Inputs').first().json['What is the listing price? (e.g., $599,000.)'] }} [RULE: Only mention price if \"{{ $('All Inputs').first().json['Do you want the listing price shown in the ad or only in the email follow-up? (Show In Ad, Only Show In Email Sequence)'] }}\" = \"Show In Ad\"]\nBedrooms: {{ $('All Inputs').first().json['How many bedrooms? '] }}\nBathrooms: {{ $('All Inputs').first().json['How many bathrooms? '] }}\nTop Features: {{ $('All Inputs').first().json['What are the top 3-5 selling features of this home? (Examples: Open-concept kitchen, large backyard, lake view, school zone, etc.)'] }}\nWOW Factor: {{ $('All Inputs').first().json['What\\'s the biggest WOW factor about this home?'] }}\nFirst Impression: {{ $('All Inputs').first().json['What\\'s one thing people LOVE when they walk in?'] }}\nHidden Benefits: {{ $('All Inputs').first().json['What are some things people don\\'t immediately notice but should?'] }}\nKey Differentiator: {{ $('All Inputs').first().json['What makes this home better than similar listings in the area?'] }}\nRecent Upgrades: \nInvestment Details: [IF {{ $('All Inputs').first().json['Is this an investment property?'] }} = YES, THEN ]\nListing Description: {{ $('All Inputs').first().json['Copy & Paste the current listing description here'][' (We\\'ll refine and optimize it for ad effectiveness!)'] }}\nAdditional Context: \nBUYER PROFILES\nPrimary Buyer: {{ $('All Inputs').first().json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary Buyer: {{ $('All Inputs').first().json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary Buyer: {{ $('All Inputs').first().json['Buyer Profile #3 (If another type of buyer applies.)'] }}\nLOCAL AMENITIES\nParks: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'][0] == 'Parks' ? 'Yes' : 'No' }}\nSchools: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Schools') ? 'Yes' : 'No' }}\nRestaurants: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Restaurants') ? 'Yes' : 'No' }}\nShopping: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Shopping') ? 'Yes' : 'No' }}\nPublic Transit: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Public Transit') ? 'Yes' : 'No' }}\nHighway Access: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Highway Access') ? 'Yes' : 'No' }}\nWaterfront: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Waterfront') ? 'Yes' : 'No' }}\nCAMPAIGN OBJECTIVE\n{{ $('All Inputs').first().json['*What Is The Objective Of Your Ad?*'] }}\nDESIRED EMOTION\n{{ $('All Inputs').first().json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}",
        "hasOutputParser": true,
        "options": {
          "systemMessage": "# Real Estate Listing Body Copy Generator\n\nI need you to create two distinct styles of real estate listing body copy based on the property information I provide.\n\n## Body Copy Style 1 Examples:\n\n### Example 1:\n```\nImagine summer BBQs in a backyard that actually fits the whole family.\n\nMornings with coffee in your open-concept living space.\nAnd a finished basement that works as your office, gym, or guest suite — without compromising upstairs space.\nWelcome to 35 Rowallan Dr — a rare 4-bed detached in Scarborough's West Hill, where upgrades meet comfort and location.\n✨ Highlights include: \n✅ New flooring + fresh paint throughout\n✅ Huge backyard with potential for garden suite or outdoor haven\n✅ Finished basement with full bathroom = flexible extra space\n✅ Minutes to Lake Ontario, parks, and waterfront trails\n✅ Close to great schools, shopping & transit\nThis home isn't just move-in ready — it's lifestyle ready.\n\n💥 Ideal for growing families who want space and connection to nature, city, and community.\n📍 Click Learn More for private access to the full listing, photo tour & details before it hits more feeds.\n```\n\n### Example 2:\n```\nReady to live above the noise? 🏙️\n\n Welcome to the 41st floor of 55 Mercer — where Lake Ontario, the CN Tower, and the entire Toronto skyline become your personal backdrop 🌇\nThis 3-bed corner unit is what most buyers dream of—but few ever find.\n ✅ Floor-to-ceiling windows\n ✅ Tons of natural light\n ✅ Private balcony with dual exposure views\n ✅ Modern layout designed for work, play, and hosting\nMorning coffee hits different here. ☕\n So do sunsets. 🌅\nSteps to the city's best food, nightlife, and culture.\n Luxury amenities include a gym, concierge, sauna, party room, and more.\n📩 Click \"Learn More\" now for exclusive access to photos, floor plans & current pricing.\n```\n\n### Example 3:\n```\n🚨 BRANTFORD HOME BUYERS – DETACHED FOR $599K?! 🚨\n(Yes, it's real! A move-in-ready detached home in a top neighborhood!)\n📍 58 Hobart Crescent, Brantford – A rare opportunity to own a detached raised bungalow at a price you won't believe!\n🏡 Why This is a Must-See:\n✔ $599K for a DETACHED home in a prime location!\n✔ Bright & Functional Layout – No wasted space.\n✔ Private Backyard – Your own outdoor retreat.\n✔ Move-In Ready – Well cared for & ready for new owners.\n✔ Top North-End Location – Walk to parks, schools, shopping & transit!\n✔ BONUS: Reviewing Offers March 3rd – Act FAST!\n💰 A detached home at this price? In Brantford?! Do NOT miss this!\n👉 Brantford buyers: Want price, photos & full details? Click 'Learn More' and I'll send them instantly!\n```\n\n### Example 4:\n```\n🚨 OTTAWA BUYERS : Want A PENTHOUSE FOR UNDER $400K? 🚨\n(Top-Floor, High Ceilings & No Upstairs Neighbors!)\n📍 190 Rustic Hills Crescent #8, Ottawa – A spacious, move-in-ready 2-bed condo in an unbeatable location!\n🏡 Why This is a No-Brainer for Ottawa Buyers:\n✔ Only $374K – Own for LESS than renting!\n✔ Top-Floor Unit = More Privacy, No Upstairs Noise!\n✔ Soaring Ceilings & Tons of Natural Light.\n✔ Freshly Painted (2025) – Move in with zero hassle!\n✔ Spacious 2-Bed Layout – Perfect for WFH Setup!\n✔ Prime Location – Steps to Parks, Transit & Shopping.\n✔ BONUS: 3 FREE MONTHS of Condo Fees!\n💰 Get a penthouse-style home at an entry-level price—this won't last!\n👉 Want more details, photos & exclusive info? Click 'Learn More' and I'll send them instantly!\n```\n\n### Example 5:\n```\n🚨 JUST LISTED IN VAUGHAN – Fully Upgraded & Move-In Ready!\n(Modern finishes, space for your family & rental income potential!)\n📍 249 Matthew Drive, Vaughan – A spacious, modern home in a prime family-friendly location.\n🏡 Here's what makes it special:\n✔ 3+2 Beds, 4 Baths – More space, more possibilities.\n✔ Fully Renovated Kitchen – New range, custom hood & modern finishes.\n✔ Bright, Open & Stylish – Engineered hardwood, crown molding & updated lighting.\n✔ Finished Basement w/ Kitchen – Perfect for rental income or in-laws!\n✔ Backyard Retreat – New deck, fresh sod & built-in shed (2024).\n✔ Top Vaughan Location – Steps to schools, shopping, transit & highways.\n💰 Why pay Toronto prices? Get more home for less in Vaughan!\n👉 Want the price, photos & full details? Click 'Learn More' and I'll send them instantly!\n```\n\n### Example 6:\n```\n🚨 PROPER 1-BED UNDER $500K? IN DOWNTOWN TORONTO?! 🚨\n\n(Not a micro-condo. A real 1-bedroom with privacy + space. Yes, they still exist.)\n\n📍 51 Trolley Crescent – The best deal downtown (Leslieville border).\n\n🏡 Why This Beats Renting:\n✅ Spacious layout – No glass walls, just real privacy.\n✅ Tons of natural light ☀️ + southeast city views.\n✅ Low fees, well-managed building – No surprise costs.\n✅ Pool, gym, media room, 24/7 security, guest suites.\n✅ Locker + bike storage included (RARE at this price!).\n\n💰 Build your own equity. Stop paying your landlord's mortgage.\n\n👇 Comment 'details' and I'll send you the entire listing package!\n```\n\n### Example 7:\n```\n🏡 Your Next Chapter Starts Here.\n\n✅ Moving out of the city but don't want to leave the action?\n✅ Want a home that's easy to maintain but still feels spacious?\n✅ Looking for a place that keeps you connected—to the city, to your family, to what matters?\n\n📍 28 Ann St #914, Port Credit is where first-time home buyers, smart downsizers & city professionals find balance.\n\n✔ 2 beds, 2 baths – A space designed for comfort, not compromise.\n✔ Floor-to-ceiling windows – Your home should feel bright, open, and welcoming.\n✔ Private balcony – Your personal outdoor retreat.\n✔ Luxury amenities – Gym, rooftop terrace, co-working space & more.\n✔ Zero maintenance hassle – Lock & leave lifestyle = more freedom.\n✔ Walkable, connected, convenient – Steps from transit, dining & the lake.\n\n💡 If you're ready to trade stress for simplicity, this is the home for you.\n\n👉 Your Next Chapter Starts Here – See Inside Today!\n```\n\n### Example 8:\n```\n🏡 WARNING: You're About to Fall in Love with This Home!\n\nOnce you see this 4+1 bed, 4 bath, park-facing stunner in Churchill Meadows, you won't want anything else.\n\n💡 Let's keep it real—homes like this don't last.\nHere's why:\n\n🔥 4+1 bedrooms, 4 bathrooms – Enough space so you're not living on top of each other.\n\n🔥 Directly facing a massive park – No staring at your neighbor's garage.\n\n🔥 Chef's kitchen – Quartz countertops, stainless steel appliances, space to actually cook.\n\n🔥 Finished basement – Home office? Gym? In-law suite? It's got options.\n\n🔥 Backyard with a deck & patio – Finally, a space for BBQ season.\n\n🔥 Move-in ready – No renos. No headaches. Just unpack and live.\n\n📍 Churchill Meadows = Prime real estate, top schools, and everything you need minutes away.\n\n🚀 Serious buyers only. DM us now or Click Learn More to book a private tour before it's gone.\n```\n\n### Example 9:\n```\n\"🎯 Looking for a Profitable, Hands-Off Investment? 📍 Welcome to 253 Lester Street, Unit 204, Waterloo, a fully furnished, 5-bedroom, 2-bathroom ideal student rental condo perfectly located within walking distance to Wilfrid Laurier University and the University of Waterloo. ✔ Gross rental income: ~*$4,308/month (1 vacant room projected at $850). ✔ Tenants pay utilities, keeping your costs low. ✔ This rental has been professionally managed. ✔ Prime location = low vacancy risk year-round. 💡 BONUS: FREE INVESTOR ANALYSIS SPREADSHEET Get a detailed financial breakdown for this property, including: Projected cash flow analysis showing potential income and expenses. ROI and cap rate calculations tailored for smart investors. Insights into Waterloo's high-demand rental market for consistent returns. 💰 Priced at just $595,000, this is the perfect turnkey property for seasoned investors or first-timers. 👉 Click Learn More to explore this opportunity and claim your FREE Investor Analysis Spreadsheet today!\"\n```\n\n### Example 10:\n```\nJust renovated and ready for you! 🏡 This 3+1 bedroom townhome in peaceful Meadowvale won't wait for hesitant buyers.\n\nFresh paint throughout and brand NEW flooring on the main floor make this move-in ready.\n\nSprawling across 1700 sq ft with 3 floors of modern living space – much larger than you'd expect!\n\nImagine stepping onto your private balcony with morning coffee or entertaining in your fenced backyard with gazebo on warm evenings. 🌳\n\nLocated minutes from the GO Station and major highways (403, 401, 407) for easy commutes from Unit #73 in Mississauga.\n\nOther first-time buyers are already booking viewings on this listing. Click 'Learn More' to get instant access to floor plans and additional photos before someone else makes it their home!\n```\n\n### Example 11:\n```\n🚨 RARE FIND: Manhattan-Style Brownstone with CN Tower Views! 🚨\n\nImagine owning a private walk-up townhouse in the heart of downtown Toronto...\n\nThis isn't just a home – it's the urban lifestyle you've been searching for. A rare 3-storey brownstone that feels like Manhattan but with Toronto's iconic skyline as your backdrop.\n\n✅ PRIVATE FRONT DOOR – No elevators, no waiting, no shared hallways\n✅ IN-HOUSE GARAGE – Direct access to your home (unheard of downtown!)\n✅ SPACIOUS LAYOUT – 1,800 sq ft of thoughtfully designed living space\n✅ NATURAL LIGHT FLOOD – East-west exposure means all-day sunshine\n✅ ENTERTAINER'S DREAM – Two balconies plus a sun-drenched back deck\n\nBut the REAL showstopper? Your own private rooftop terrace with:\n• Breathtaking CN Tower views\n• Built-in water hookup for your garden oasis\n• Custom pergola for the perfect blend of privacy and shade\n\n🔑 This is where downtown convenience meets brownstone privacy.\n📍 This is where your morning coffee comes with a skyline view.\n\nLocated steps from U of T, the vibrant restaurants of Baldwin Village, and the AGO, this home delivers the downtown lifestyle without the downtown compromises.\n\nFreshly painted throughout with generous bedrooms, flexible interiors, and thoughtful storage solutions (including two basement storage rooms with potential for an additional bathroom).\n\nSmart buyers know: Downtown walk-up homes with private garages AND rooftop terraces DON'T last.\n\nClick \"Learn More\" for exclusive photos and details before someone else makes this their downtown sanctuary.\n```\n\n### Example 12:\n```\n🏡 LIVE IN A MANHATTAN BROWNSTONE—IN DOWNTOWN TORONTO?!\n\n(Yes, a private walk-up with CN Tower views actually exists!)\n\n📍 182 McCaul — Toronto's rarest home that delivers what downtown condos can't.\n\nMost downtown homes force you to choose: space OR location.\nThis one gives you BOTH.\n\n✅ PRIVATE ENTRANCE — No elevators, no hallways, no waiting\n✅ DRIVE-IN GARAGE — Direct access to your home (UNHEARD OF downtown!)\n✅ 1,800 SQFT ACROSS 3 LEVELS — Room to actually LIVE\n✅ ROOFTOP TERRACE — CN Tower views + water hookup + pergola\n✅ TWO BALCONIES + BACK DECK — Outdoor space in every direction\n✅ SOARING CEILINGS — Walk in and instantly feel the difference\n\n💡 Steps to U of T, Baldwin Village restaurants, and the AGO.\n\nThe moment you walk in: High ceilings and natural light flood every corner.\n\nLook closer: Large bedrooms. Flexible layouts. Gas fireplace. Freshly painted.\n\nWhat others miss: TWO storage rooms in the basement with potential for an additional bathroom.\n\n💰 Downtown brownstones with private garages AND rooftop terraces DON'T last.\n\n👉 Click \"Learn More\" for exclusive photos and full details before someone else claims Toronto's ultimate urban sanctuary!\n```\n\n### Example 13:\n```\n🚨 FIRST-TIME BUYERS: KING WEST 1-BED WITH PARKING FOR $599K?! 🚨\n\n(Yes, it's real! A move-in ready condo where King West, Queen West & Ossington meet!)\n\n📍 1 Shaw Street, Unit 711 – The downtown lifestyle you want at a price you can actually afford!\n\n🏡 Why This Is The Best Deal Downtown:\n\n✅ ONLY $599K WITH PARKING & LOCKER – Own for less than you're paying in rent\n✅ INCREDIBLE LOCATION – King West, Queen West & Ossington all at your doorstep\n✅ ZERO WASTED SPACE – Functional layout that maximizes every square foot\n✅ MOVE-IN READY – New vinyl floors (2022) & freshly painted everything (2025)\n✅ SOUTH-FACING WINDOWS – Natural light floods the entire unit all day\n✅ PRIVATE BALCONY – With turf & built-in tabletop for your morning coffee or evening drinks\n✅ ROOFTOP TERRACE – Stunning city views, BBQs & brand-new patio furniture (2023)\n\nThe moment you walk in: Fresh paint, new floors, and an updated kitchen that FEELS different from other units.\n\nWhat others miss: Spacious bedroom that easily fits a king-size bed + walk-in closet for all your storage needs!\n\n💡 No Frills across the street, Trinity Bellwoods Park nearby, and TTC at your doorstep = the perfect downtown lifestyle.\n\nThis isn't just another cookie-cutter condo. It's priced at only $966/sqft in one of the city's hottest neighborhoods!\n\n👉 Click \"Learn More\" for exclusive photos and full details before another first-time buyer snatches it up!\n```\n\n### Example 14:\n```\n🏀 FIND ME ANOTHER VAUGHAN HOME WITH A BACKYARD BASKETBALL COURT! 🏀\n\n(Spoiler alert: You can't. This 5+1 bed, 6 bath masterpiece stands alone.)\n\n📍 52 Keatley Drive — Where luxury meets functionality in Vaughan's most sought-after school district.\n\nFORGET everything you've seen in this neighborhood. This isn't another cookie-cutter luxury home.\n\n✅ MASSIVE 4300+ SQFT ABOVE GRADE — Larger than virtually every comparable\n✅ BACKYARD OASIS — Custom basketball court + large wood deck + hammock lounge\n✅ $115K BASEMENT RENOVATION — Separate entrance nanny/in-law suite = rental income potential\n✅ $40K CHEF'S KITCHEN — Wolf appliances + quartz counters + butler's pantry with wine fridge\n✅ 8-CAR DRIVEWAY — Unheard of in Vaughan subdivisions\n✅ VIOLA DESMOND SCHOOL DISTRICT — The address smart parents fight for\n\nThe moment you walk in: Soaring ceilings, custom millwork, and an open-concept layout that FEELS different.\n\nWhat others miss: New furnace, AC, and tankless water heater = zero mechanical headaches after moving in.\n\n💡 Steps to Clearview Park, Mackenzie Health Hospital, golf courses, and minutes to Highway 407.\n\nThis isn't just another luxury home. It's built for real life—entertaining, multigenerational living, work-from-home, and active families who need SPACE to thrive.\n\n👉 Click \"Learn More\" for exclusive photos and full details before someone else claims Vaughan's ultimate family sanctuary!\n```\n\n## Body Copy Style 2 Examples:\n\n### Example 1:\n```\nThe \"crown jewel\" of Langley's luxury real estate market... \n\nThis isn't just a home. It's a masterpiece of design brilliance by Rose & Funk.\nImagine stepping into a 2.5-storey vaulted great room that literally takes your breath away.\nWhere a custom Fond Du Lac Fieldstone fireplace with a 2200-pound hand-sculptured Indiana limestone hearth becomes the conversation piece at every gathering.\nWhere Calacatta Vagli Marble, white oak finishes, and brass accents whisper \"luxury\" in every room.\n6 bedrooms. 5 bathrooms. 1.39 pristine acres.\nThis isn't just square footage – it's a statement.\nThe kind of home that doesn't just impress – it transforms how you experience life.\nAnd with Control 4 Automation, power window shades, and whole-home sound system, technology meets timeless elegance.\nThe cherry on top? A garage that fits 4 vehicles plus storage, with space designed for a future pool and detached building.\nClick 'Learn More' to discover the full story behind this one-of-a-kind Langley estate.\n```\n\n### Example 2:\n```\n🏡 BRANFOD FIRST-TIME BUYERS: WHY RENT WHEN YOU CAN OWN THIS?!\n📍 58 Hobart Crescent, Brantford – You don't need a condo. You don't need a townhouse. You can afford a detached home.\n🏡 What makes this a no-brainer:\n✅ Only $599K – That's less than some Brantford townhouses!\n✅ Spacious, Bright & Functional – Feels like home from Day 1.\n✅ Private Backyard – Your space, your rules.\n✅ Move-In Ready – No renos, no headaches.\n✅ Steps to Parks, Schools & Shopping.\n💰 You said you wanted space. You said you wanted privacy. This is it.\n👉 Want price, photos & full details? Click 'Learn More' and I'll send them instantly!\n```\n\n### Example 3:\n```\nTORONTO BUYERS: Need more space? This King George Square 1+1 delivers what others don't.\nReal usable square footage. Not the tiny boxes typical downtown.\nA den that fits a desk. Not a closet they call a den.\nTwo full bathrooms. No more morning lineups.\nLarge balcony with east downtown views. Nothing blocking your sight lines.\nNatural light floods in all day. Floor-to-ceiling windows make the space feel even larger.\nRooftop garden. Gym. Sauna. Hot tub. 24-hour concierge. One parking spot and one locker included.Click \"Learn More\" immediately to see all photos and secure your private viewing of this premium downtown space.\n```\n\n### Example 4:\n```\nThe $5.7M Langley manor everyone is talking about…\nWhat if you could live in absolute serenity just minutes from everything you need?\nNestled on a quiet no-thru road sits 1.39 acres of meticulously designed English-style gardens and mature trees.\nMost luxury homes compromise on space or privacy. This one offers both.\nPicture morning coffee overlooking your private estate while the kids have endless room to play.\nA cobblestone paver driveway welcomes you home to 6 bedrooms and 5 bathrooms spanning across European-inspired architecture.\nEvery detail – from the hand-tumbled limestone foyer to the brass fixtures throughout – was chosen with intention and craftsmanship.\nThis isn't just another big house. It's a sanctuary designed for those who understand that true luxury is found in the details.\nThe main floor primary retreat offers convenience while four upstairs bedrooms ensure everyone has their own personal space.\nAnd that basement? A moody, sophisticated entertainment zone with classic bar and antique mirrors.\nThis is more than a home. It's the lifestyle upgrade you've been searching for.\nClick 'Learn More' to discover the full story behind this one-of-a-kind Langley estate.\n```\n\n### Example 5:\n```\nRefined townhome offering in exclusive Meadowvale – completely renovated with sophisticated modern finishes throughout.\n\nThis 3+1 bedroom residence features approximately 1700 square feet of thoughtfully designed living space across three distinct levels.\n\nThe property distinguishes itself with efficient gas furnace heating rather than standard electric baseboard systems found in comparable properties.\n\nThe second floor presents an elegant open concept with direct walkout access to a private fenced yard with gazebo, ideal for both relaxation and entertaining colleagues.\n\nPositioned for the discerning professional at Unit #73, Mississauga, offering exceptional convenience to the GO Station and strategic highway connections (403, 401, 407 & QEW) for seamless regional mobility.\n\nThis listing represents a limited opportunity in a rapidly appreciating neighborhood. Request access to the complete property portfolio by clicking below.\n```\n\n### Example 6:\n```\nManhattan-style living meets Toronto skyline views.\n\nImagine mornings with coffee on your private rooftop terrace, the CN Tower framing your view.\n\nEvenings entertaining on multiple outdoor spaces—two balconies plus a sun-drenched back deck for the perfect urban retreat.\n\nWelcome to 182 McCaul—a rare 3-storey brownstone where downtown convenience meets walk-up privacy in Toronto's vibrant arts district.\n\n✨ What makes this property exceptional:\n\n✅ Private front door entry—no elevators, no shared hallways, just direct access to your sanctuary\n✅ In-house garage with direct interior access—unheard of downtown\n✅ Approximately 1,800 sq ft of thoughtfully designed living space across three levels\n✅ East-west exposure flooding interiors with natural light throughout the day\n✅ Exceptional rooftop terrace with CN Tower views, built-in water hookup, and custom pergola\n\nThe soaring ceilings and natural light hit you the moment you walk in. But look closer—spacious bedrooms, flexible living spaces, and smart storage solutions provide what downtown condos rarely offer: room to breathe.\n\nLocated steps from U of T, Baldwin Village restaurants, and the AGO, this home delivers the perfect balance of location and livability.\n\nThis isn't just another downtown option—it's downtown living without compromise.\n\n→ TAP \"LEARN MORE\" NOW ←\n\nGet exclusive access to photos, floor plans and neighborhood details before this rare opportunity disappears.\n```\n\n### Example 7:\n```\nThe $599K downtown condo that lets you have it all...\n\nCan't decide between King West nightlife, Queen West shopping, or Ossington's restaurant scene?\n\nAt 1 Shaw Street, Unit 711, you don't have to choose.\n\nImagine morning coffee on your private south-facing balcony, evening drinks on the stunning rooftop terrace, and weekends exploring the city's most vibrant neighborhoods—all from your doorstep.\n\nWHY THIS CHANGES EVERYTHING FOR FIRST-TIME BUYERS:\n\n✅ Price Point Freedom: At just $599K including parking AND locker, you'll finally escape the rental trap without breaking the bank\n\n✅ Location Triple Threat: Living at the intersection of King West, Queen West and Ossington means you're always at the center of what's happening\n\n✅ Morning Simplicity: No Frills directly across the street and Woolshed Coffee around the corner transforms your daily routine from stressful to seamless\n\n✅ Weekend Lifestyle: Trinity Bellwoods Park, biking trails by the Lakeshore, and the city's best restaurants (Mamakas Taverna, Bar Piquet) just steps away\n\n✅ Zero Renovation Stress: New vinyl floors (2022), refreshed kitchen cabinets and fresh paint throughout (2025) means move in and immediately enjoy your new home\n\n✅ Unbeatable Value: Priced at only $966/sqft in a premium building with 24/7 concierge, gym, and rooftop terrace - significantly below market for this location\n\nThis thoughtfully designed south-facing unit offers what downtown buyers rarely find: functional space, natural light, and prime location without the premium price tag.\n\n→ TAP \"LEARN MORE\" NOW ←\n\nGet the photos, floor plan and exclusive details before this rare opportunity disappears!\n```\n\n### Example 8:\n```\nThe \"crown jewel\" of Vaughan's luxury real estate market...\n\nThis isn't just a home. It's 4300+ square feet of family legacy in the making.\n\nNestled in the prestigious Viola Desmond school district, 52 Keatley Drive gives your family the life they've been searching for.\n\nWHY THIS HOME TRANSFORMS YOUR FAMILY'S LIFESTYLE:\n\n✅ For Sports Enthusiasts: Your own professional basketball court means weekend tournaments, skill-building for the kids, and active family bonding without ever leaving home\n\n✅ For Serious Entertainers: The massive wood deck, 8-car driveway, and hammock lounge create the perfect backdrop for legendary neighborhood BBQs and holiday gatherings\n\n✅ For Culinary Masters: $40K custom kitchen with Wolf appliances, quartz countertops, and butler's pantry turns everyday meals into extraordinary experiences\n\n✅ For Growing Families: 5+1 bedrooms and 6 bathrooms means everyone gets their space without compromise - no more fighting over bathrooms in the morning rush\n\n✅ For Smart Investors: $115K basement renovation with separate entrance creates rental income potential or the perfect in-law/nanny suite for multigenerational living\n\n✅ For Education-Focused Parents: The coveted Viola Desmond school district puts your children's future first - the address smart parents compete to secure\n\nThis meticulously upgraded estate offers what discerning families demand: space, luxury, and functionality in Vaughan's most desirable neighborhood.\n\n→ TAP \"LEARN MORE\" NOW ←\n\nGet the photos, price, floor plan and exclusive details before this rare opportunity disappears!\n```"
        }
      },
      "type": "@n8n/n8n-nodes-langchain.agent",
      "typeVersion": 1.8,
      "position": [
        -6500,
        2780
      ],
      "id": "dc4d9eee-2d35-4877-b169-a0ec1cf4a91b",
      "name": "Body Copy Agent"
    },
    {
      "parameters": {
        "jsonSchemaExample": "{\n \"ad_body_copies\": [\n   {\n     \"body_copy\": \"\"\n   },\n   {\n     \"body_copy\": \"\"\n   }\n ]\n}"
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserStructured",
      "typeVersion": 1.2,
      "position": [
        -6352,
        3000
      ],
      "id": "f2946f8a-0560-48db-9b33-0d946e630e37",
      "name": "ad body copies"
    },
    {
      "parameters": {
        "modelName": "models/gemini-2.0-flash-001",
        "options": {}
      },
      "type": "@n8n/n8n-nodes-langchain.lmChatGoogleGemini",
      "typeVersion": 1,
      "position": [
        -6472,
        3000
      ],
      "id": "48e6de9c-10ad-4652-93f4-81e383ddde4a",
      "name": "Google Gemini Chat Model",
      "credentials": {
        "googlePalmApi": {
          "id": "vAGPZIKKEemfw5Kl",
          "name": "Google Gemini(PaLM) Api account"
        }
      }
    },
    {
      "parameters": {
        "promptType": "define",
        "text": "=NEW LISTING DATA:\nProperty Essence\nProperty Type: {{ $('All Inputs').first().json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice Point: {{ $('All Inputs').first().json['What is the listing price? (e.g., $599,000.)'] }}[RULE: Only reference if \"Show In Ad\" is selected]\nLocation: {{ $('All Inputs').first().json['City/Town'] }}, {{ $('All Inputs').first().json['State/Region/Province'] }}\nKey Feature: {{ $('All Inputs').first().json['What\\'s the biggest WOW factor about this home?'] }}\nKey Emotion: {{ $('All Inputs').first().json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}\nTarget Audience Composite\nCombined profile of all three buyer personas:\nPrimary: {{ $('All Inputs').first().json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary: {{ $('All Inputs').first().json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary: {{ $('All Inputs').first().json['Buyer Profile #3 (If another type of buyer applies.)'] }}\n\nFull Address: {{ $('All Inputs').first().json['Address'] }}, {{ $('All Inputs').first().json['City/Town'] }}, {{ $('All Inputs').first().json['State/Region/Province'] }}, {{ $('All Inputs').first().json['Zip/Post Code'] }}\nProperty Type: {{ $('All Inputs').first().json['What type of property is this? (Condo, Freehold, Townhouse, Multi-Unit, Other – Please specify.)'] }}\nPrice: {{ $('All Inputs').first().json['What is the listing price? (e.g., $599,000.)'] }} [RULE: Only mention price if \"{{ $('All Inputs').first().json['Do you want the listing price shown in the ad or only in the email follow-up? (Show In Ad, Only Show In Email Sequence)'] }}\" = \"Show In Ad\"]\nBedrooms: {{ $('All Inputs').first().json['How many bedrooms? '] }}\nBathrooms: {{ $('All Inputs').first().json['How many bathrooms? '] }}\nTop Features: {{ $('All Inputs').first().json['What are the top 3-5 selling features of this home? (Examples: Open-concept kitchen, large backyard, lake view, school zone, etc.)'] }}\nWOW Factor: {{ $('All Inputs').first().json['What\\'s the biggest WOW factor about this home?'] }}\nFirst Impression: {{ $('All Inputs').first().json['What\\'s one thing people LOVE when they walk in?'] }}\nHidden Benefits: {{ $('All Inputs').first().json['What are some things people don\\'t immediately notice but should?'] }}\nKey Differentiator: {{ $('All Inputs').first().json['What makes this home better than similar listings in the area?'] }}\nRecent Upgrades: \nInvestment Details: [IF {{ $('All Inputs').first().json['Is this an investment property?'] }} = YES, THEN ]\nListing Description: {{ $('All Inputs').first().json['Copy & Paste the current listing description here'][' (We\\'ll refine and optimize it for ad effectiveness!)'] }}\nAdditional Context: \nBUYER PROFILES\nPrimary Buyer: {{ $('All Inputs').first().json['Who do you think the perfect buyer is? (Buyer Profile #1) (Examples: Young professionals, first-time buyers, retirees, investors, growing families, etc.)'] }}\nSecondary Buyer: {{ $('All Inputs').first().json['Buyer Profile #2 (Golfers, Skiers, Dog Owners, Etc.)'] }}\nTertiary Buyer: {{ $('All Inputs').first().json['Buyer Profile #3 (If another type of buyer applies.)'] }}\nLOCAL AMENITIES\nParks: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'][0] == 'Parks' ? 'Yes' : 'No' }}\nSchools: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Schools') ? 'Yes' : 'No' }}\nRestaurants: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Restaurants') ? 'Yes' : 'No' }}\nShopping: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Shopping') ? 'Yes' : 'No' }}\nPublic Transit: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Public Transit') ? 'Yes' : 'No' }}\nHighway Access: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Highway Access') ? 'Yes' : 'No' }}\nWaterfront: {{ $('All Inputs').first().json['What local amenities would attract buyers? (Choose up to 3: Parks, Schools, Restaurants, Shopping, Public Transit, Highway Access, Waterfront, Other – Please Specify.)'].includes('Waterfront') ? 'Yes' : 'No' }}\nCAMPAIGN OBJECTIVE\n{{ $('All Inputs').first().json['*What Is The Objective Of Your Ad?*'] }}\nDESIRED EMOTION\n{{ $('All Inputs').first().json['What emotions do you want potential buyers to feel when they see this ad? (Excited, Curious, Urgency, Trust, Luxury, Other – Please Specify.)'] }}\n\nAd Body Copy 1:\n{{ $json.output.ad_body_copies[0].body_copy }}\n\nAd Body Copy 2:\n{{ $json.output.ad_body_copies[1].body_copy }}\n",
        "hasOutputParser": true,
        "options": {
          "systemMessage": "# Real Estate Headline Generator\n\nI need you to create compelling headlines for the real estate listing I'm providing. Please generate:\n\n1. Two headline options in Style 1\n2. Two headline options in Style 2 \n\n## Property Details:\n[I'll fill in the details for my property here, including address, price, bedrooms/bathrooms, features, target buyers, etc.]\n\n## I've already created two body copy versions:\n\n### Body Copy 1:\n[I'll paste the first body copy here]\n\n### Body Copy 2:\n[I'll paste the second body copy here]\n\n## Style Guidelines:\n\n### Headline Style 1:\nDirect, value-driven headlines that use emojis, specific selling points, and create excitement. These headlines should immediately grab attention and highlight what makes the property special.\n\n### Headline Style 2:\nMore narrative-focused headlines that emphasize rarity, location, or unique features. These can be framed as questions or statements that speak to lifestyle benefits.\n\n## Headline Examples:\n\n### Headline Style 1 Examples:\n\n```\n🏡 Big Backyard, 4 Bedrooms & Minutes from the Lake? West Hill Has It All\n\n• Young, Thriving, and Outgrowing Your Condo? Let's Fix That\n\n\"Hidden Resort\" Style Home In Thornhill Woods\n\nToronto's 1370 sqft 'Unicorn Property' \n\nThe King Street Address Buyers FIGHT For \n\nInside Langley's Most Coveted $5.7M Residence\n\n$599K for a Detached Home in North-End Brantford!\n\nOttawa Penthouse for $374K!\n\nLive Upstairs, Rent the Basement - Live for Less Than Rent.\n\nBest $500K Condo Downtown\n\n💰 Live in Port Credit for $100K Less – Steps to the GO & Lake!\n\n🏡 Warning: This Home Will Ruin Every Other House for You.\n\nAttention Investors: High-Demand Rental Property Near Waterloo's Top Universities!\n\nMississauga Professionals FIGHT Over This Fresh-Painted Townhome\n\n🚨 $599K for a King West 1-Bed WITH Parking & Locker?!\n\n🏡 First-Time Buyers: Downtown Condo at $966/sqft with Parking Included!\n\n🏡 Manhattan-Style Brownstone with CN Tower Views & Private Garage!\n\n🚨 Downtown Townhouse with Private Entrance, Garage & Rooftop Terrace!\n\n🏀 Luxury Vaughan Home with Private Basketball Court & Wolf Kitchen!\n\n🏡 5+1 Bedrooms, 6 Baths & Backyard Basketball Court in Viola Desmond District!\n```\n\n### Headline Style 2 Examples:\n\n```\n👨‍👩‍👧‍👦 Growing Family? This Detached 4-Bed in Scarborough Has Room for Everyone\n\n• Finally… a Downtown Condo That Fits Your Lifestyle (and Your Friends)\n\nVaughan's Ultimate Backyard Escape\n\nRare 1370 sqft 'Giant Condo' \n\nKing George Square's RARE Corner Unit\n\nLangley's Most Extravagant $5.7M Manor\n\nDetached Home For $599K In Brantford\n\n3 FREE Months of Condo Fees\n\nFully Upgraded w/ Built-In Rental Income\n\nA Real 1-Bed Downtown You Can Afford!\n\n💡 Rare Deal: $100K Off a High-Demand Port Credit Condo!\n\n🚀 Homes Like This Get Snatched Up Fast – Act Now.\n\nInvest in Waterloo's Hottest Student Rental Property!\n\nFresh Paint + New Floors = 24 Hour Countdown\n\n👀 Rare Find: South-Facing King West Condo Under $600K!\n\n💰 Live in a Downtown Brownstone WITHOUT Elevators or High Condo Fees!\n\n💎 Vaughan's Ultimate Family Estate with 4300+ Square Feet Above Grade!\n\n👨‍👩‍👧‍👦 Growing Family? This Renovated Vaughan Home Has Room for Everyone + Basketball Court!\n```\n\nBased on the property details and body copy I've provided, please generate headlines that align with these styles while highlighting the unique selling points of my property."
        }
      },
      "type": "@n8n/n8n-nodes-langchain.agent",
      "typeVersion": 1.8,
      "position": [
        -6124,
        2780
      ],
      "id": "c003eb7b-47ef-45b3-b9c6-25612d155720",
      "name": "Headline Agent1"
    },
    {
      "parameters": {
        "jsonSchemaExample": "{\n \"ad_headlines\": [\n   {\n     \"headline\": \"\"\n   },\n   {\n     \"headline\": \"\"\n   },\n   {\n     \"headline\": \"\"\n   }\n ]\n}"
      },
      "type": "@n8n/n8n-nodes-langchain.outputParserStructured",
      "typeVersion": 1.2,
      "position": [
        -6036,
        3000
      ],
      "id": "03144b82-bf2d-48af-895e-fa25664e0ad7",
      "name": "ad headlines1"
    },
    {
      "parameters": {
        "resource": "databasePage",
        "operation": "update",
        "pageId": {
          "__rl": true,
          "value": "={{ $('Create New Listing Ad Campaign').first().json.id }}",
          "mode": "id"
        },
        "propertiesUi": {
          "propertyValues": [
            {
              "key": "Body Copy 1|rich_text",
              "textContent": "={{ $('Body Copy Agent').first().json.output.ad_body_copies[0].body_copy }}"
            },
            {
              "key": "Body Copy 2|rich_text",
              "textContent": "={{ $('Body Copy Agent').first().json.output.ad_body_copies[1].body_copy }}"
            },
            {
              "key": "Headline 1|rich_text",
              "textContent": "={{ $json.output.ad_headlines[0].headline }}"
            },
            {
              "key": "Headline 2|rich_text",
              "textContent": "={{ $json.output.ad_headlines[1].headline }}"
            },
            {
              "key": "Headline 3|rich_text",
              "textContent": "={{ $json.output.ad_headlines[2].headline }}"
            },
            {
              "key": "Headline 4|rich_text",
              "textContent": "={{ $json.output.ad_headlines[3].headline }}"
            }
          ]
        },
        "options": {}
      },
      "type": "n8n-nodes-base.notion",
      "typeVersion": 2.2,
      "position": [
        -5740,
        2780
      ],
      "id": "1b0302ef-6673-4b64-8030-fe202304913e",
      "name": "Update Listing Ad Campaign with Copy1",
      "credentials": {
        "notionApi": {
          "id": "3EhNxVoPGBbOY9vC",
          "name": "Notion account"
        }
      }
    }
  ],
  "settings": {
    "executionOrder": "v1",
    "timezone": "America/Toronto",
    "callerPolicy": "workflowsFromSameOwner",
    "executionTimeout": 300
  },
  "shared": [
    {
      "createdAt": "2025-05-01T14:29:56.792Z",
      "updatedAt": "2025-05-01T14:29:56.792Z",
      "role": "workflow:owner",
      "workflowId": "m9ePaOw1Y5JGcKMk",
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
  "staticData": {
    "node:Typeform Trigger": {
      "webhookId": "n8n-7it5ziwttq"
    }
  },
  "tags": [
    {
      "createdAt": "2025-02-21T17:21:41.750Z",
      "updatedAt": "2025-02-21T17:21:41.750Z",
      "id": "hCxs00bYB7kqJnEo",
      "name": "WORKING"
    }
  ],
  "triggerCount": 2,
  "updatedAt": "2025-05-01T20:18:34.000Z",
  "versionId": "9b69f82d-aa5d-4dc6-845b-ade69df36e75"
}