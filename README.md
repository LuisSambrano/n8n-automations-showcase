<div align="center">

<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,6,11&height=200&section=header&text=n8n%20Automations&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=35&desc=AI%20Workflows%20%7C%20Business%20Logic%20%7C%20Open%20Source&descSize=18&descAlignY=55"/>

<!-- BADGES -->
<p>
  <img src="https://img.shields.io/badge/Type-AI_Lab-blueviolet?style=for-the-badge" alt="Type: AI Lab"/>
  <img src="https://img.shields.io/badge/n8n-Orchestrator-ff6600?style=for-the-badge&logo=n8n" alt="n8n" />
  <img src="https://img.shields.io/badge/Flowise-Reasoning-8b5cf6?style=for-the-badge" alt="Flowise" />
  <img src="https://img.shields.io/badge/Ollama-Local_LLM-white?style=for-the-badge&logo=ollama&logoColor=black" alt="Ollama" />
  <img src="https://img.shields.io/badge/MCP-Integration-green?style=for-the-badge" alt="MCP Integration" />
</p>

<!-- LANGUAGE SWITCHER -->
<p>
  <a href="./README.md"><img src="https://img.shields.io/badge/🇺🇸_English-Selected-blue?style=flat-square" alt="English"/></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/🇪🇸_Español-Available-lightgrey?style=flat-square" alt="Español"/></a>
  <a href="./README.pt.md"><img src="https://img.shields.io/badge/🇧🇷_Português-Available-lightgrey?style=flat-square" alt="Português"/></a>
</p>

</div>

---

**Professional automation ecosystem for orchestrating complex business processes and AI agentic logic using n8n and MCP.**

---

## 🛠️ System Architecture

- **n8n:** Orchestrator (`http://localhost:5678`)
- **Flowise:** Reasoning Layer (`http://localhost:3002`)
- **Ollama:** Local LLM Engine (`llama3.2`)

---

## 🛠️ Operational Instructions

### 1. Unified Startup

To initialize the full R&D stack, run from their respective directories:

```bash
# Terminal 1: n8n Engine
./start_local.sh

# Terminal 2: Flowise Reasoning Layer
./start_flowise.sh
```

## 📂 Workspace Layout

| Directory           | Domain               | Examples                                                                          |
| :------------------ | :------------------- | :-------------------------------------------------------------------------------- |
| **`/chatbots`**     | AI Assistants & RAG  | • RAG with OpenAI + Pinecone<br>• Telegram Support Bot<br>• Voice AI Integrations |
| **`/social-media`** | Content Distribution | • YouTube ➡️ Blog ➡️ Tweet<br>• Auto-Engagement Monitoring<br>• Lead Enrichment   |
| **`/dev-ops`**      | Technical Automation | • GitHub Issue Triaging<br>• Auto-Deployment Notifications<br>• Server Monitoring |
| **`/productivity`** | Business Logic       | • Email Drafting<br>• Meeting Summaries<br>• Finance Tracking                     |

---

## 🔌 Protocol Integration (MCP)

This lab supports the **Model Context Protocol (MCP)**, enabling advanced interoperability with LLMs like Gemini or Claude.

### 1. n8n as MCP Client

Use the `HTTP Request` node to consume external MCP servers via SSE endpoints.

### 2. n8n as MCP Server

Enable Claude to execute workflows or read data directly from this environment using the `n8n-mcp` bridge.

---

## 🔐 Security & Governance

- Secrets are managed via **Internal Credentials** and never exported in raw files.
- This repository is for local R&D only; no sensitive production data is stored here.

---

<div align="center">

_Architected by **Luis Sambrano**_

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,6,11&height=100&section=footer"/>

</div>
