# Watsonx Orcestrate Hindi & French Content Generator
Content Generator which translate blog content English along with French and Hindi.
There are 3 agents-
1. Supervisor Agent:
- Understand User's Question
- Call French & Hindi Agents to reponse in respective language. 

2. Collaborator Agents:
- Hindi Content Generator
- French Content Generator

## Import Agents via YAML
First collaborator to be imported and then Supervisor agent to be imported.

orchestrate agents import -f /Users/prashantsharma/Documents/GitHub/wxoadk_hindi_french_content_generator/agents/hindi_translation_agent.yaml

orchestrate agents import -f /Users/prashantsharma/Documents/GitHub/wxoadk_hindi_french_content_generator/agents/french_translation_agent.yaml

orchestrate agents import -f /Users/prashantsharma/Documents/GitHub/wxoadk_hindi_french_content_generator/agents/hindi_french_contentgen_agent.yaml
