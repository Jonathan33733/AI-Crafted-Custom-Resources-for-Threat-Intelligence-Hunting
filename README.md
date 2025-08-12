# AI-Crafted-Custom-Resources-for-Threat-Intelligence-Hunting

An automated threat intelligence system built with n8n that scrapes cybersecurity news from TheHackerNews, uses AI (OpenRouter/ChatGPT) to analyze content for threat indicators like CVEs and domains, and automatically generates structured outputs including MITRE ATT&CK mappings and KQL hunting queries. The system filters duplicate content, processes articles through Jina AI for content extraction, and stores all results in Google Sheets for easy access by security teams and threat hunters.

# n8n workflow

![image alt](https://github.com/Jonathan33733/AI-Crafted-Custom-Resources-for-Threat-Intelligence-Hunting/blob/main/Workflow.JPG?raw=true)
