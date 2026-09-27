# Awesome Agent Services [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of services, APIs, and infrastructure built for AI agents — not humans.

Humans have Gmail, Chrome, Stripe, and Slack. Agents need their own.

**Not a list of agents. A list of services agents use.**

Looking for agents themselves? See [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) (26k ⭐).
This list covers the **infrastructure layer** — services where the primary user is an AI agent, not a human clicking buttons.

---

## Contents

- [📧 Communication](#-communication)
- [💳 Payments & Wallets](#-payments--wallets)
- [🌐 Browser & Web](#-browser--web)
- [🧠 Memory & Context](#-memory--context)
- [🔧 Tools & Integrations](#-tools--integrations)
- [🏗️ Sandboxes & Compute](#️-sandboxes--compute)
- [📊 Observability & Monitoring](#-observability--monitoring)
- [🤝 Coordination & Orchestration](#-coordination--orchestration)
- [🚀 Orchestration Frameworks](#-orchestration-frameworks)
- [💼 Marketplaces & Earn](#-marketplaces--earn)
- [🆔 Identity & Auth](#-identity--auth)
- [📞 Voice & Phone](#-voice--phone)
- [📜 Protocols & Standards](#-protocols--standards)
- [KubeStellar Console](https://github.com/kubestellar/console) — Kubernetes multi-cluster management console with built-in AI agent for infrastructure queries; deploy and manage agent workloads across clouds with observability and policy enforcement.

---

## 📧 Communication

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [AgentMail](https://agentmail.to) | Email inboxes for agents — create, send, receive, thread, search via API | $6M seed (General Catalyst, Mar 2026) |
| [DropMail](https://dropmail.me/api/) | Ephemeral email inboxes via GraphQL — designed for AI agents and automation, MCP server available | Open source / Free |
| [MoltMail](https://moltmail.io) | Email + crypto wallet identity for agents (by EtherMail) | Launched Mar 2026 |

## 💳 Payments & Wallets

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [Skyfire](https://skyfire.xyz) | Payment network for AI agents — KYA (Know Your Agent), wallet, checkout | $8.5M seed |
| [Coinbase Agentic Wallets](https://www.coinbase.com/developer-platform/discover/launches/agentic-wallets) | Crypto wallets for agents with x402 payments, session caps, tx controls | Coinbase (public) |
| [Payman](https://paymanai.com) | Let AI agents pay humans for tasks (Fiverr for agents) | Active |
| [InFlow](https://inflow.finance) | Autonomous payments for agents — "PayPal for agents" | Active |
| [AgentsPay](https://agentspay.dev) | Crypto-native agent wallets, MCP-native, no humans required | Active |
| [Chimoney](https://chimoney.io/products/ai-agent-wallets/) | Agent wallets with Interledger — bulk disbursements, cross-border | Active |
| [Walta](https://walta.ai) | Financial infrastructure for agents — identity, programmable wallets, KYA | Active |
| [Nevermined](https://nevermined.io) | Agent payment rails with metering, DIDs, x402 integration | Active |
| [Stripe Agent Toolkit](https://github.com/stripe/agent-toolkit) | Official Stripe toolkit for AI agents — create payments, invoices, customers | Open source |

## 🌐 Browser & Web

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [Lightpanda](https://lightpanda.io) | Headless browser for AI agents — 11x faster than Chrome, 9x less memory, CDP compatible | Open source (13.7k ⭐, Zig, AGPL-3.0) |
| [Agent-Browser](https://github.com/vercel/agent-browser) | Real Chromium browser for agents by Vercel — navigate pages, click buttons, fill forms, take screenshots | Vercel (open source) |
| [Browserbase](https://browserbase.com) | Cloud browser infrastructure for agents — sessions, stealth, recordings | Notable Capital backed |
| [Steel Browser](https://github.com/steel-dev/steel-browser) | Open-source browser API for agents — sessions, anti-detection, Playwright | Open source |
| [Hyperbrowser](https://hyperbrowser.ai) | AI-native browser infra built for agents (YC W25) | Y Combinator |
| [browser-use](https://github.com/browser-use/browser-use) | Make websites accessible for AI agents — Playwright automation | Open source (56k+ ⭐) |
| [Firecrawl](https://firecrawl.dev) | Turn websites into agent-ready data — crawl, scrape, extract | Active |
| [Scrapybara](https://scrapybara.com) | Virtual desktops for AI agents — full computer access | Active |
| [cua](https://github.com/trycua/cua) | Open-source Docker container for computer-use agents — macOS VMs, GUI automation, keyboard/mouse control | Y Combinator (YC X25, 172 HN pts) |

## 🧠 Memory & Context

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [QMD](https://github.com/tobi/qmd) | Local hybrid search for markdown files by Shopify CEO Tobias Lütke — BM25 + vector search + LLM re-ranking, zero API keys; connect Notion for real agent memory | Open source |
| [Mem0](https://mem0.ai) | Memory layer for agents — extract, store, retrieve across sessions | Open source + cloud |
| [Zep](https://getzep.com) | Context engineering platform — temporal knowledge graph, 200ms retrieval | Active |
| [Letta](https://letta.com) | Stateful agents with self-editing memory (formerly MemGPT) | Open source + cloud |
| [Graphlit](https://graphlit.com) | Knowledge management & RAG infrastructure for agents | Active |
| [Wolfram LLM API](https://products.wolframalpha.com/llm-api/documentation) | Computational knowledge API optimized for LLMs — math, science, real-world data in structured format | Wolfram (commercial) |
| [Dolt](https://github.com/dolthub/dolt) | Git for data — MySQL-compatible database with branch, merge, diff and commit on SQL tables; built-in agent memory server | Open source (21k ⭐) |

## 🔧 Tools & Integrations

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [Composio](https://composio.dev) | 400+ tool integrations for agents — auth, execute, manage via MCP/API | Active |
| [Toolhouse](https://toolhouse.ai) | Cloud tool infrastructure for agents — run tools without managing servers | Active |
| [StackOne](https://stackone.com) | Unified API for agent integrations — HR, CRM, ATS | Active |
| [Merge](https://merge.dev) | Unified API for agent-accessible integrations (HRIS, ATS, CRM, etc.) | Active |
| [Airweave](https://airweave.ai) | Context retrieval layer for agents — search any SaaS app or database (Salesforce, GitHub, Slack, 100+ connectors) | Y Combinator (YC X25, 176 HN pts) |
| [Metorial](https://metorial.com) | Vercel for MCP — deploy, host, and version MCP servers with one command | Y Combinator (YC F25, 59 HN pts) |
| [AgentServices](https://agentservices.to) | 54 paid data APIs for AI agents — crypto market data, forex, stocks, AI inference, news. x402-enabled, 37 MCP tools. | Active |
| [APIClaw](https://apiclaw.biz) | Flat-rate OpenAI-compatible AI API gateway for Claude, GPT, Kimi, Qwen, DeepSeek, and GLM; 50-request free trial | Commercial ($19-$129/mo) |

## 🏗️ Sandboxes & Compute

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [E2B](https://e2b.dev) | Secure cloud sandboxes for agents — code execution, file system, tools | Used by 88% Fortune 100 |
| [Cloudflare Agents](https://developers.cloudflare.com/agents/) | Serverless agent platform — durable state, cron, WebSockets, any model | Cloudflare (public) |
| [Modal](https://modal.com) | Serverless compute for agent workloads — GPU, CPU, cron | Active |
| [Fly.io](https://fly.io) | Run agent containers globally — Machines API, per-user isolation | Active |
| [Amazon Bedrock AgentCore](https://aws.amazon.com/bedrock/agentcore/) | Managed production runtime for AI agents at any scale — memory, auth, code interpreter, gateway, observability | AWS (public, 663 GitHub stars) |

## 📊 Observability & Monitoring

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [Langfuse](https://langfuse.com) | Open-source observability for agents — traces, evals, metrics | Acquired by ClickHouse (Jan 2026) |
| [AgentOps](https://agentops.ai) | Session replays, cost tracking, debugging for agents | Active |
| [LangSmith](https://smith.langchain.com) | Tracing, evaluation, monitoring for LangChain agents | LangChain |
| [Arize Phoenix](https://phoenix.arize.com) | Open-source observability for LLM apps and agents | Open source |
| [Braintrust](https://braintrust.dev) | Eval, logging, prompt management for agents | Active |

## 🤝 Coordination & Orchestration

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [GNAP](https://github.com/farol-team/gnap) | Git-Native Agent Protocol — coordinate agent teams with just git, no servers | Open source |
| [HiClaw](https://hiclaw.io) | Open-source Multi-Agent OS by Alibaba — Manager-Worker architecture over Matrix protocol, human-in-the-loop, agents never hold real credentials | Open source (Alibaba, Apache 2.0) |
| [Google A2A](https://github.com/google/A2A) | Agent-to-Agent protocol by Google — discovery, task management, streaming | Google (open spec) |
| [Anthropic MCP](https://modelcontextprotocol.io) | Model Context Protocol — standard for connecting agents to tools & data | Anthropic (open spec) |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Agent orchestration with handoffs, guardrails, tracing | OpenAI (open source) |

## 🚀 Orchestration Frameworks

> Frameworks for building, running, and coordinating multi-agent systems.

### Company / OS-level

| Framework | Stars | What it does |
|-----------|-------|-------------|
| [Paperclip](https://github.com/paperclipai/paperclip) | 23K | "Paperclip = company, OpenClaw = employee" — org charts, budgets, governance for AI teams | Open source |
| [Spacebot](https://github.com/spacedriveapp/spacebot) | 1.8K | Multi-user agent platform — 8-tier memory, circuit breakers, Cortex bulletin system | Open source (Rust) |

### Multi-agent frameworks

| Framework | Stars | What it does |
|-----------|-------|-------------|
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 182K | The original autonomous agent — spawned the entire genre | Open source |
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 65K | Multi-role software company: PM → Architect → Dev → QA in one pipeline | Open source |
| [AutoGen](https://github.com/microsoft/autogen) | 55K | Conversational multi-agent coordination by Microsoft | Open source |
| [CrewAI](https://github.com/crewAIInc/crewAI) | 46K | Role-playing autonomous agents with task delegation | Open source |
| [Agno](https://github.com/agno-agi/agno) | 38K | Build, run, manage agentic software at scale | Open source |
| [ChatDev](https://github.com/OpenBMB/ChatDev) | 31K | Virtual software company via LLM multi-agent collaboration | Open source |
| [Camel](https://github.com/camel-ai/camel) | 16K | First multi-agent framework — role-playing, communicative agents | Open source |
| [Swarms](https://github.com/kyegomez/swarms) | 5.9K | Enterprise-grade production multi-agent orchestration | Open source |
| [Agency Swarm](https://github.com/VRSEN/agency-swarm) | 4K | Reliable role-based agent teams | Open source |

### Graph / pipeline frameworks

| Framework | Stars | What it does |
|-----------|-------|-------------|
| [LangGraph](https://github.com/langchain-ai/langgraph) | 26K | Stateful agents as graphs with built-in checkpointing | Open source |
| [Flowise](https://github.com/FlowiseAI/Flowise) | 50K | Visual drag-and-drop agent builder | Open source |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | 27K | Microsoft SDK for agent apps (.NET, Python, Java) | Open source |
| [PydanticAI](https://github.com/pydantic/pydantic-ai) | 15K | Type-safe agent framework | Open source |

### Workflow engines (AI-ready)

| Framework | Stars | What it does |
|-----------|-------|-------------|
| [n8n](https://github.com/n8n-io/n8n) | 179K | No-code workflow automation with native AI nodes | Fair-code |
| [Conductor](https://github.com/conductor-oss/conductor) | 31K | Event-driven agentic orchestration, durable execution | Open source |
| [Temporal](https://github.com/temporalio/temporal) | 18K | Durable workflow execution — survives crashes, retries | Open source |
| [Prefect](https://github.com/PrefectHQ/prefect) | 21K | Python workflow orchestration with observability | Open source |
| [Inngest](https://github.com/inngest/inngest) | 5K | Durable step functions and AI agents, serverless | Open source |

### Git-native coordination

| Framework | Stars | What it does |
|-----------|-------|-------------|
| [GNAP](https://github.com/farol-team/gnap) | 20 | Git-Native Agent Protocol — coordinate agents via git push/pull, zero infrastructure | Open source |
| [GitClaw](https://github.com/open-gitagent/gitclaw) | 140 | Agent-as-repo: identity, memory, tools, skills all version-controlled | Open source |
| [jj-mailbox](https://github.com/MiaoDX/jj-mailbox) | 2 | Maildir for agents — structured message passing via jj VCS | Open source |

## 💼 Marketplaces & Earn

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [Toku](https://toku.agency) | AI agent marketplace — list services, get hired, earn USD | Active |
| [AI Agent Store](https://aiagentstore.ai) | Agent discovery + on-chain USDC bounties on Base | Active |
| [Algora](https://algora.io) | Open-source bounty platform — agents can earn by closing issues | Active |
| [Cog Depot](https://cogdepot.com) | Peer-to-peer marketplace where buyer and seller agents discover listings, negotiate, and settle in BTC/stablecoins - A2A Agent Card + JSON-RPC `message/send`, no human in the deal path | Active |

## 🆔 Identity & Auth

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004) | Ethereum standard for verifiable AI agent identity | EIP (draft) |
| [Skyfire KYA](https://skyfire.xyz/product/) | Know Your Agent — agent identity verification for commerce | Part of Skyfire |
| [Anon](https://anon.com) | Auth proxy — let agents use services with your credentials securely | Active |
| [Kontext](https://kontext.dev) | Identity infrastructure for AI agents — runtime credentials, act on behalf of users with full audit trail | Launched Mar 2026 |

## 📞 Voice & Phone

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [Vapi](https://vapi.ai) | Voice AI agent platform — phone calls, real-time, any model | Active |
| [LiveKit Agents](https://docs.livekit.io/agents/) | Real-time audio/video infrastructure for agents | Open source + cloud |
| [Synthflow](https://synthflow.ai) | AI voice agents for phone calls — SOC2, HIPAA, PCI DSS | Active |
| [Bland AI](https://bland.ai) | AI phone calls at scale — enterprise voice agents | Active |

## 📜 Protocols & Standards

| Protocol | What it does | By |
|----------|-------------|---|
| [x402](https://www.x402.org/) | HTTP-native payment protocol for AI agents (revived HTTP 402) | Coinbase + Cloudflare |
| [MCP](https://modelcontextprotocol.io) | Model Context Protocol — connect agents to tools & data sources | Anthropic |
| [A2A](https://github.com/google/A2A) | Agent-to-Agent protocol — agent discovery, task delegation | Google |
| [AP2](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol) | Agents-to-Payments protocol — secure agent commerce | Google |
| [GNAP](https://github.com/farol-team/gnap) | Git-Native Agent Protocol — coordinate via git push/pull | Farol Team |

---

## Contributing

Found a service that's missing? [Open an issue](https://github.com/farol-team/awesome-agent-services/issues) or submit a PR. See [contributing.md](contributing.md) for guidelines.
