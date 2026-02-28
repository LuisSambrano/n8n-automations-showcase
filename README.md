# ⚙️ High-Performance Workflows & AI Lab

Professional automation ecosystem for orchestrating complex business processes and AI agentic logic.

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

_Managed with excellence by **Luis Sambrano**_
