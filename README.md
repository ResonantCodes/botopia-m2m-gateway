# 🌐 Botopia: M2M Data Gateway | API Deprecation Intelligence Feeds

> **Real-time, structured API deprecation & breaking change intelligence feeds for autonomous AI agents, SecOps bots, and enterprise dev pipelines.**

Welcome to the official Machine-to-Machine (M2M) gateway for **Botopia**. Our automated loot farmers sweep major cloud and AI platforms daily to deliver clean, structured, early-warning JSON feeds detailing **affected components, dynamic 2026 severity levels, required action items, and direct documentation links**.

---
##  System Architecture

mermaid
flowchart TD
    subgraph Clients
        H["Human Developer"]
        A["Autonomous Agent"]
    end

    subgraph Botopia Gateway
        M["Manifests: llms.txt / agent.json / MCP"]
        P["Payment Guard: x402 / Credit Top-Up"]
        R["REST API Routers"]
    end

    subgraph Data Layer
        V[("Active Intelligence Vaults")]
    end

    H -->|"$10 Credits"| P
    A -->|"Auto-Discover"| M
    A -->|"x402 Micropayment"| P
    P --> R
    R --> V

---

## 🎁 Claim $0.21 Starter Grant (3 Free Queries for Bots & Devs)

Test our live multi-vault feeds instantly with zero friction! Generate a dynamic starter key loaded with $0.21 in query credits:

👉 **[Claim Instant 3-Query Starter Key](https://agents.lilaonthegrid.com/api/v1/auth/claim-starter-key)** *(HTTP POST / GET — Returns dynamic `botopia_live_` key)*

---

## 💳 Pre-Fund Query Credits (Human Developers & Agencies)

Ready to top up your M2M key balance for high-frequency agent pipelines? Pre-fund custom query credits directly via our Stripe portal:

👉 **[Buy Botopia M2M Data Query Credits](https://buy.stripe.com/3cI14o6ZD50W6ykfDs0Ba00)** *(Pay-what-you-want starting at $1.00 USD)*

---

## 🤖 Machine-to-Machine Access (Autonomous Bots & LLM Orchestrators)

Autonomous agents can query our live intelligence vaults directly via standard HTTP headers or Model Context Protocol (MCP) tool invocations ($0.07 USD per query).

* 🌐 **Master Intelligence Feed:** https://agents.lilaonthegrid.com/api/v1/m2m/feed
* 🔌 **Native MCP Discovery Endpoint:** https://agents.lilaonthegrid.com/mcp
* 📚 **Interactive OpenAPI Portal & Sandbox:** https://agents.lilaonthegrid.com/docs
* 🔑 **Accepted Auth Headers:** `X-API-Key: <key>` OR `Authorization: Bearer <key>`

---

## ⚡ Active Intelligence Vaults (11-Platform Fleet)

Our automated farmers sweep official changelogs daily at **5:00 PM** to harvest breaking API deprecations, parameter sunsets, and endpoint EOL notices into standardized JSON payloads:

| Platform | Monitored Data | Update Frequency | Status |
| :--- | :--- | :--- | :--- |
| **Anthropic** | Claude API, Tool Use, Model Sunsets | Daily (5:00 PM) | 🟢 Active |
| **AWS** | AWS Cloud Infrastructure & Service APIs | Daily (5:00 PM) | 🟢 Active |
| **Azure** | Azure Service Updates & Cloud Infrastructure | Daily (5:00 PM) | 🟢 Active |
| **Cloudflare** | Workers AI, Security, DNS & API Endpoints | Daily (5:00 PM) | 🟢 Active |
| **GCP** | Google Cloud Platform APIs & Terms | Daily (5:00 PM) | 🟢 Active |
| **Gemini** | Google AI Models & Endpoints | Daily (5:00 PM) | 🟢 Active |
| **GitHub** | REST/GraphQL APIs & Webhooks | Daily (5:00 PM) | 🟢 Active |
| **OpenAI** | GPT Models, Endpoints & Fine-Tuning | Daily (5:00 PM) | 🟢 Active |
| **Stripe** | Payment APIs & Webhook Versions | Daily (5:00 PM) | 🟢 Active |
| **Tenable** | Vulnerability Management & Cyber Exposure APIs | Daily (5:00 PM) | 🟢 Active |
| **Vercel** | Edge Functions & Deployment APIs | Daily (5:00 PM) | 🟢 Active |

---

## 🤖 Discovery & Machine Manifests

Autonomous agents can discover and inspect our endpoints dynamically:

* 📜 **LLM Indexer Terms & Spec:** https://agents.lilaonthegrid.com/llms.txt
* 🔌 **MCP Tool Card:** https://agents.lilaonthegrid.com/mcp
* 🎴 **Agent Card Manifest:** https://agents.lilaonthegrid.com/.well-known/agent-card.json
* ⚡ **x402 Spec Discovery:** https://agents.lilaonthegrid.com/.well-known/x402
* 🤖 **Crawler Policy:** https://agents.lilaonthegrid.com/robots.txt

---

## 🔌 Quick Integration

### Agent Config (Claude Desktop / Cursor / LangChain / AutoGPT)
```json
{
  "mcpServers": {
    "botopia-m2m": {
      "url": "[https://agents.lilaonthegrid.com/mcp](https://agents.lilaonthegrid.com/mcp)",
      "headers": {
        "X-API-Key": "YOUR_BOTOPIA_KEY"
      }
    }
  }
}
```

---

## ⚖️ Terms, Micropayments & Legal Shield

* 💳 **Pay-Per-Query Pricing:** $0.07 USD per query accessed via `X-API-Key` or `X-PAYMENT` headers.
* 🛑 **Non-Refundable Policy:** All $0.07 query deductions and credit top-ups are strictly non-refundable once an API request or MCP tool call is executed.
* 📜 **Terms of Service:** Full machine-readable specifications and agent policies are published at [`llms.txt`](https://agents.lilaonthegrid.com/llms.txt).
* 🛡️ **Limitation of Liability:** All feeds and JSON payloads are provided strictly on an **"AS-IS"** and **"AS-AVAILABLE"** basis. Total aggregate liability for any claim is strictly capped at the total amount paid to Botopia during the preceding 30 days. Always verify critical deprecation timelines using the provided `documentation_url` fields before applying breaking code updates.

---

*Powered by LOTG Labs (Lila On The Grid) 🚀🌾*
