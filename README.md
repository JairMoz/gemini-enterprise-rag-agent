# Vertex AI Agent: Intelligent RAG & Tooling System

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Google Cloud Agents](https://img.shields.io/badge/Google%20Cloud%20Agents-Certificate-blue?style=for-the-badge)
![GenAI](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

This repository contains the full implementation and configuration for an AI Agent built using **Vertex AI Agent Builder**. The project demonstrates the integration of Large Language Models (LLMs) with enterprise data through RAG (Retrieval-Augmented Generation) and external API orchestration.

🎯 **Project Goal**
The primary goal was to architect an autonomous agent capable of resolving complex user queries by grounding its responses in a verified Knowledge Base and executing actions via specialized Tools.

💡 **Key Skills Demonstrated**
* **Agentic Workflow Design:** Configured Playbooks with step-by-step reasoning paths to guide the LLM through complex support scenarios.
* **RAG & Grounding:** Implemented a Data Store connection to provide factual, source-cited answers, reducing model hallucinations to near zero.
* **Tool & API Integration:** Defined OpenAPI 3.0 specifications to enable the agent to interact with live backend systems.
* **Advanced Prompting:** Utilized system instructions and few-shot examples within the Agent Builder environment to ensure brand-aligned responses.

📂 **Files Info:**
* `agent-configs/playbook-steps.md` — Detailed reasoning instructions and goal definitions for the agent.
* `tools/inventory-api-spec.json` — OpenAPI specification for the agent's external tool capabilities.
* `data-sources/support-manual.md` — Sample unstructured data used to populate the RAG Data Store.
