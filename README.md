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
- [💼 Marketplaces & Earn](#-marketplaces--earn)
- [🆔 Identity & Auth](#-identity--auth)
- [📞 Voice & Phone](#-voice--phone)
- [📜 Protocols & Standards](#-protocols--standards)

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
| [Browserbase](https://browserbase.com) | Cloud browser infrastructure for agents — sessions, stealth, recordings | Notable Capital backed |
| [Steel Browser](https://github.com/steel-dev/steel-browser) | Open-source browser API for agents — sessions, anti-detection, Playwright | Open source |
| [Hyperbrowser](https://hyperbrowser.ai) | AI-native browser infra built for agents (YC W25) | Y Combinator |
| [browser-use](https://github.com/browser-use/browser-use) | Make websites accessible for AI agents — Playwright automation | Open source (56k+ ⭐) |
| [Firecrawl](https://firecrawl.dev) | Turn websites into agent-ready data — crawl, scrape, extract | Active |
| [Scrapybara](https://scrapybara.com) | Virtual desktops for AI agents — full computer access | Active |

## 🧠 Memory & Context

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
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

## 🏗️ Sandboxes & Compute

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [E2B](https://e2b.dev) | Secure cloud sandboxes for agents — code execution, file system, tools | Used by 88% Fortune 100 |
| [Cloudflare Agents](https://developers.cloudflare.com/agents/) | Serverless agent platform — durable state, cron, WebSockets, any model | Cloudflare (public) |
| [Modal](https://modal.com) | Serverless compute for agent workloads — GPU, CPU, cron | Active |
| [Fly.io](https://fly.io) | Run agent containers globally — Machines API, per-user isolation | Active |

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

## 💼 Marketplaces & Earn

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [Toku](https://toku.agency) | AI agent marketplace — list services, get hired, earn USD | Active |
| [AI Agent Store](https://aiagentstore.ai) | Agent discovery + on-chain USDC bounties on Base | Active |
| [Algora](https://algora.io) | Open-source bounty platform — agents can earn by closing issues | Active |

## 🆔 Identity & Auth

| Service | What it does | Funding / Status |
|---------|-------------|-----------------|
| [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004) | Ethereum standard for verifiable AI agent identity | EIP (draft) |
| [Skyfire KYA](https://skyfire.xyz/product/) | Know Your Agent — agent identity verification for commerce | Part of Skyfire |
| [Anon](https://anon.com) | Auth proxy — let agents use services with your credentials securely | Active |

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

Found a service that's missing? [Open an issue](https://github.com/farol-team/awesome-agent-services/issues) or submit a PR.

**Criteria:**
- The service must be designed primarily **for AI agents**, not adapted from a human-first product
- Must have a working product or public API (no vaporware)
- Include: name, URL, one-line description, funding/status if known

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
