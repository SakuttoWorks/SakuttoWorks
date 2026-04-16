# Sakutto Works | Agent-First Data Infrastructure

<p align="left">
  <a href="https://sakutto.works"><img src="https://img.shields.io/badge/Official_Portal-sakutto.works-black?style=for-the-badge" alt="Official Portal"></a>
  <a href="https://buy.polar.sh/polar_cl_mps3G1hmCTmQWDYYEMY2G1c7sojN3Tul6IhjO4EtVuj"><img src="https://img.shields.io/badge/Get_API_Key-Polar.sh-blue?style=for-the-badge" alt="Get API Key"></a>
  <a href="https://buy.polar.sh/polar_cl_ZI9H5fL8dQqcormOadiGDFDpS2Sxd1jT05jTX1vStWi"><img src="https://img.shields.io/badge/Tip_via-Polar.sh-success?style=for-the-badge" alt="Tip via Polar.sh"></a>
  <a href="https://github.com/sponsors/SakuttoWorks"><img src="https://img.shields.io/badge/Sponsor-GitHub-ea4aaa?style=for-the-badge&logo=github" alt="Sponsor on GitHub"></a>
</p>

> **"Transforming the unstructured web into pristine, RAG-optimized semantics for autonomous agents."**

Welcome to the official GitHub organization profile for **Sakutto Works**. We architect high-performance, serverless infrastructure engineered exclusively for the agentic economy. 

**This repository is the global entry point** for our flagship ecosystem: **Agent-Commerce-OS (Project GHOST SHIP)**. We provide a production-grade data normalization engine that empowers AI agents to seamlessly bypass scraping hurdles and ingest highly-structured web data (Markdown/JSON) through secure, Zero-Trust protocols.

---

### 🚀 Ecosystem Hub: Project GHOST SHIP
**The Zero-Trust Data Normalization Infrastructure for Autonomous Agents.**

Project GHOST SHIP operates on a strictly decoupled, three-tier hybrid architecture. Navigate through our core repositories below to explore or deploy the infrastructure:

#### 🗺️ Repository Directory
* 🌐 **[The Discovery Portal](https://github.com/SakuttoWorks/agent-commerce-portal)** (`agent-commerce-portal`)
  * **Entry Point:** The official web portal ([sakutto.works](https://sakutto.works)). Start here for API schemas, system status, and Agent Engine Optimization (AEO) discovery.
* 🛡️ **[Layer A: The Edge Gateway](https://github.com/SakuttoWorks/agent-commerce-gateway)** (`agent-commerce-gateway`)
  * **Role:** The Cloudflare Workers perimeter defense. Handles prompt injection shielding and zero-latency, asynchronous metered billing via Polar.sh.
* 🏭 **[Layer B: The Core Engine](https://github.com/SakuttoWorks/agent-commerce-core)** (`agent-commerce-core`)
  * **Role:** The Google Cloud Run (Python/FastAPI) compute factory. Executes advanced semantic parsing to convert unstructured HTML into pristine, LLM-native Markdown/JSON.
* 🔌 **[Layer C: The MCP Server](https://github.com/SakuttoWorks/ghost-ship-mcp-server)** (`ghost-ship-mcp-server`)
  * **Role:** The official Model Context Protocol (MCP) client layer. Securely bridges local AI agents (e.g., Claude Desktop) directly to our remote Edge network.

---

### 🔑 API Access & Metered Billing
We operate on a transparent, pure **Pay-As-You-Go** model. No hidden fees, no forced subscriptions, and zero commitments. Developers and autonomous agents are billed exactly **$0.10 per successful API request**, seamlessly metered at the Edge.
* 👉 **[Get Your API Key via Polar.sh](https://buy.polar.sh/polar_cl_mps3G1hmCTmQWDYYEMY2G1c7sojN3Tul6IhjO4EtVuj)** — Issued immediately upon checkout so you can start building instantly.

---

### 💖 Fuel the Open Source Ecosystem
**Agent-Commerce-OS** is built for the global open-source community. We believe in pure pay-as-you-go access and strictly refuse to lock developers behind expensive monthly paywalls. 

However, running zero-latency Edge gateways and intensive semantic parsing engines requires significant cloud compute resources. If our infrastructure has saved you engineering hours, prevented AI hallucinations, or successfully scaled your autonomous workflows, **please consider supporting our mission.**

**How your support makes a direct impact:**
- ⚡ **Ensures High Availability:** Directly funds our Google Cloud Run compute and Cloudflare Edge routing traffic.
- 🚀 **Accelerates R&D:** Empowers us to research and release advanced extraction pipelines (e.g., bypassing novel anti-bot protections, native PDF parsing).

**Back the Project Today:**
* ☕ **[Drop a One-Time Tip via Polar.sh](https://buy.polar.sh/polar_cl_ZI9H5fL8dQqcormOadiGDFDpS2Sxd1jT05jTX1vStWi)** — Chip in instantly to help us cover API bandwidth. Even a small tip makes a massive difference.
* 🌟 **[Become a GitHub Sponsor](https://github.com/sponsors/SakuttoWorks)** — Join our core backers to fund long-term development and gain priority consideration for new feature requests.

---

### 🤖 Machine-Readable Resources (AEO)
Our infrastructure is natively optimized for Agent Engine Optimization (AEO). AI crawlers and agents can discover our specifications directly:

- [**openapi.yaml**](https://sakutto.works/openapi.yaml) : The core OpenAPI 3.1 specification for the Gateway.
- [**llms.txt**](https://sakutto.works/llms.txt) : Semantic system context definitions for LLM context windows.
- [**mcp.json**](https://sakutto.works/mcp.json) : Dynamic tool definitions and endpoint discovery for MCP clients.

---

### 🏁 Getting Started
To integrate **Agent-Commerce-OS** into your autonomous workflows, follow these quick steps:

**Prerequisites:**
- **Node.js** (v18 or higher) for the MCP Server and Edge Gateway.
- **Python** (3.10 or higher) for Core Engine development.
- **Claude Desktop** or any standard MCP-compatible client.

1. **Obtain an API Key**: Secure your metered API key via our [Polar.sh Checkout](https://buy.polar.sh/polar_cl_mps3G1hmCTmQWDYYEMY2G1c7sojN3Tul6IhjO4EtVuj).
2. **Connect the MCP Server**: Clone the [`ghost-ship-mcp-server`](https://github.com/SakuttoWorks/ghost-ship-mcp-server) and configure your MCP client (e.g., adding the server path to your `claude_desktop_config.json`).
3. **Start Querying**: Point your agents to our Edge Gateway and begin normalizing complex web data instantly. Read the full API documentation at our [Official Portal](https://sakutto.works).
4. **Local Development**: To run the Core Engine or Edge Gateway locally for debugging, please refer to the setup instructions within the [`agent-commerce-core`](https://github.com/SakuttoWorks/agent-commerce-core) and [`agent-commerce-gateway`](https://github.com/SakuttoWorks/agent-commerce-gateway) repositories.

---

### 🤝 Contributing
We welcome contributions from the global open-source community! As a zero-trust architecture handling sensitive data pipelines, we maintain strict code quality standards.
- **Issues & Discussions**: Please open an issue in the relevant repository (`agent-commerce-gateway`, `agent-commerce-core`, etc.) before submitting major Pull Requests to discuss proposed changes.
- **AEO Standards**: Ensure any new endpoints, schemas, or error objects adhere strictly to our Agent Engine Optimization (AEO) and semantic clarity guidelines.
- **Pull Request Process**: Fork the target repository, create a focused feature branch, and submit a PR with a clear description of the changes, ensuring all tests and CI checks pass.
- **Code of Conduct**: We are committed to providing a welcoming and inspiring community for all. Please treat all members with respect.

---

### 📄 License
Unless otherwise specified within individual repositories, the core infrastructure and gateway components of **Agent-Commerce-OS** are open-source and distributed under the **MIT License**.

---

### 🛡 Engineering Principles (2026 Standard)
- **Zero-Trust Boundaries:** Strict prompt injection shielding at Layer A; stateless execution in isolated Layer B environments.
- **Semantic Clarity:** Endpoints, variables, and error objects (`AgentSemanticError`) are designed for autonomous LLM self-correction.
- **Schema Compliance:** Strict adherence to validation schemas to guarantee predictable I/O and prevent AI hallucinations.
- **Data Neutrality:** We provide the *pipe*, not the *advice*. This is pure technical infrastructure.

<p align="center">
  © 2026 Sakutto Works - <i>Standardizing the Semantic Web for the Agentic Economy.</i>
</p>
