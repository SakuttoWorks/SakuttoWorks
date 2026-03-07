# Sakutto Works | Agent-First Data Infrastructure

<p align="left">
  <img src="https://img.shields.io/badge/Architecture-Hybrid_Edge_Core-blue?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/Protocol-MCP_%26_SSE-orange?style=for-the-badge" alt="Protocol">
  <img src="https://img.shields.io/badge/Infrastructure-Data_Normalization-green?style=for-the-badge" alt="Infrastructure">
</p>

> **"Bridging the gap between Unstructured Web and LLM Context."**

Technical Co-founder and Senior Lead Architect specializing in high-performance serverless ecosystems. I build **"Agent-Commerce-OS"**, a production-ready **BaaS (Backend-as-a-Service)** that allows AI agents to securely access, format, and ingest structured web data via standardized protocols.

---

### 🚀 Flagship Project: [Project GHOST SHIP](https://github.com/SakuttoWorks/agent-commerce-portal)
**The Secure MCP Gateway for Autonomous Data Retrieval.**

Project GHOST SHIP serves as a middleware layer that normalizes external web content into RAG-optimized formats (Markdown/JSON) for LLMs.

- **Layer A: The Edge Gateway ([agent-commerce-gateway](https://github.com/SakuttoWorks/agent-commerce-gateway))**
  - Low-latency SSE/MCP aggregation on Cloudflare Workers.
  - **Security & Validation:** Request sanitization, schema validation, and rate-limiting via Polar.sh infrastructure.
- **Layer B: The Normalization Engine ([agent-commerce-core](https://github.com/SakuttoWorks/agent-commerce-core))**
  - **Semantic Extraction:** Python 3.13+ environment on Google Cloud Run for parsing complex HTML.
  - **LLM-Native Output:** Converts raw HTML into clean Markdown using Jina Reader/Firecrawl logic.
- **Layer C: The Data Vault (Supabase/R2)**
  - Structured logging of tool execution results and transient cache storage.

### 🌍 Developer Hubs:
- 👉 **[Access API Portal (Lemon Squeezy)](https://sakuttoworks.lemonsqueezy.com/)**
- 👉 **[RapidAPI Documentation (Coming Soon)](#)**
- 👉 **[Polar.sh (infrastructure Access)](#)**

---

### 🛠 Active MCP & API Assets

| Component | Protocol | Description |
| :--- | :---: | :--- |
| **GHOST-SHIP-GATEWAY** | MCP / SSE | Secure proxy for handling tool execution requests and schema validation. |
| **AGENT-COMMERCE-CORE** | REST / JSON | Core engine for web-to-markdown conversion and data structuring. |
| **SEMANTIC-EXTRACTOR** | MCP / REST | **(Formerly V3)** Domain-agnostic scraper for technical documentation and static sites. |

---

### 🤖 Machine-Readable Resources
Optimized for AI Agents (AEO - Agent Engine Optimization).

- [**llms.txt**](./llms.txt) : Context definitions for LLM crawlers.
- [**mcp.json**](./mcp.json) : Dynamic tool definitions and endpoint discovery for MCP clients.

---

### 🛡 Engineering Principles (2026 Standard)
- **Zero-Trust Logic:** Strict input validation at the edge; execution in isolated environments.
- **Semantic Naming:** Every variable and endpoint is optimized for LLM self-documentation.
- **Schema Compliance:** Strict adherence to predefined JSON schemas to prevent hallucinations.

<p align="center">
  © 2026 Sakutto Works - Building the Semantic Web for Agents
</p>
