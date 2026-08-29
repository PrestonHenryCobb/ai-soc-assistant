>> # Tier 1 SOC Assistant AI Agent
  *An AI agent built in Azure AI Foundry that assists Tier 1 SOC analysts with alert triage and MITRE ATT&CK mapping*
> ## Overview 
Made using Azure's no-code Foundry service. This AI agent is a Tier 1 SOC analyst assistant, used to assist in alert triaging and MITRE ATT&CK mapping. Rather than being an autonomous prevention device, this agent is designed for strictly as a decision-support tool that ***only has value when paired with a Human analyst making the judgement call***. It analyzes given alerts and essentially composes a report containing the following:
- a report of the assumed MITRE ATT&CK technique
- severity level
- recommended next steps
---
> ## Configuration
Built with Microsoft Azure's AI Foundry, no-code agent builder 
- gpt model 5 via Foundry
- a SOC knowledge base including 9 areas of information:
1. MITRE ATT&CK technique summaries
2. Incident response procedures
3. Phishing investigation procedures
4. Windows Event ID reference
5. Common attack indicators
6. SOC escalation procedures
7. Severity classification guidelines
8. Incident response playbooks
---
