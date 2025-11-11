# AI Agent Projects using Google ADK

This repository contains end-to-end implementations of five advanced AI agents built using the Google Agent Development Kit (ADK). Each project demonstrates how to design, implement, and deploy production-quality AI agents for various real-world applications.  
All agents are built following Google Cloud ADK best practices and include setup, execution steps, and deployment guides.

---

## a) Deep Research Agent for Lead Generation

Description:  
This agent performs deep research to automatically generate leads by leveraging the Google ADK framework. It collects, analyzes, and structures potential business leads from public sources, improving sales pipeline efficiency. The agent uses data enrichment, web intelligence, and context-aware entity extraction to enhance lead quality.

Features:
- Intelligent web search and data gathering  
- Lead scoring and prioritization  
- Integration-ready for CRM or marketing pipelines  

Source:  
https://github.com/MagnIeeT/leadGenerationAgentADK  
Reference Guide:  
https://cloud.google.com/blog/products/ai-machine-learning/build-a-deep-research-agent-with-google-adk

---

## b) Advanced Tool Agent using Gemini CLI inside ADK Pipeline

Description:  
This agent demonstrates how to integrate the Gemini CLI as a functional tool within an ADK pipeline. It can execute tasks using Gemini’s LLM capabilities (e.g., summarization, code generation, or analysis) while maintaining ADK’s modular and scalable architecture. The project illustrates how to chain Gemini CLI actions with other ADK services for hybrid automation.

Features:
- Gemini CLI integrated tool workflow  
- ADK orchestration with custom tool handlers  
- Cloud Run deployment example  

Source:  
https://github.com/derrickchwong/gemini-cli-on-adk  
Reference Guide:  
https://medium.com/@derrickchwong/combine-adk-gemini-cli-and-cloud-run-c5dea5118853

---

## c) MCP Tools-Based Agent for Bug Assistance

Description:  
This agent leverages Model Context Protocol (MCP) tools and ADK to create a software bug assistant. It can detect, analyze, and suggest fixes for common code issues using a combination of static code analysis and AI-driven recommendations. The project illustrates building an agent from scratch using the MCP model integration.

Features:
- Bug detection and contextual explanation  
- Code snippet reasoning using ADK + MCP  
- Interactive debugging flow  

Source:  
https://github.com/google/adk-samples/tree/main/python/agents/software-bug-assistant  
Reference Guide:  
https://cloud.google.com/blog/topics/developers-practitioners/tools-make-an-agent-from-zero-to-assistant-with-adk

---

## d) Production-Quality Code Review Assistant

Description:  
A production-grade Code Review Assistant built using ADK. It automates code review workflows by analyzing pull requests, identifying issues, and suggesting improvements in readability, maintainability, and security. The system integrates seamlessly with GitHub or GitLab CI/CD environments for real-time feedback.

Features:
- Automated code review comments  
- Context-aware quality and style evaluation  
- GitHub integration for PR workflows

  Deployed agent image
<img width="1268" height="412" alt="image" src="https://github.com/user-attachments/assets/6106c6a4-b550-4b7e-b4e9-3e6a3a883228" />

Source:  
https://github.com/ayoisio/adk-code-review-assistant  
Reference Guide:  
https://codelabs.developers.google.com/adk-code-reviewer-assistant/instructions?hl=en#0

---

## e) Production-Quality E-Commerce Agent with ADK

Description:  
This project builds a production-grade E-Commerce Agent using ADK integrated with MCP and AlloyDB. The agent handles product search, recommendations, and personalized shopping assistance. It demonstrates how to connect conversational AI agents with structured data sources for enterprise use.

Features:
- Product discovery and personalized recommendations  
- Integration with AlloyDB for structured data  
- End-to-end conversational e-commerce workflow  

Source:  
https://github.com/mtoscano84/sports-agent-adk-mcp-alloydb  
Reference Guide:  
https://codelabs.developers.google.com/codelabs/sports-agent-adk-mcp-alloydb?hl=en#8

---

## Video Walkthrough Playlist

A detailed execution walkthrough for all agents (including setup, configuration, and demo) will be available on YouTube:

[Video Playlist](https://www.youtube.com/playlist?list=PLGHkLcp2I_S_b_5QPEfa_m4_mqjUFeRBC)
