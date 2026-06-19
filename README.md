# Zexu Jin / 靳泽旭

Backend engineer focused on production-grade AI Agent infrastructure:
Agent Harness, runtime reliability, tool use, context/state, MCP, and evaluation loops.

- Nearly 6 years of backend and infrastructure engineering experience.
- Around 3 years building LLM applications and AI Agent systems in production.
- Led a 5-person backend team and built the runtime foundation around multi-agent products.
- Contributed merged upstream fixes to LangChain / LangGraph / LangChainJS and other open-source projects.

## Available: Agent/MCP Audit Sprint

I offer a $1,000 fixed-price audit for one agent, MCP server, or tool-using product slice:
tool boundaries, secrets, auth, write actions, prompt/tool injection paths, tests, and deployment assumptions.

- Landing page: [Agent/MCP Audit Sprint](https://jackjin1997.github.io/agent-audit-sprint/)
- Browser scanner: [paste a public GitHub URL or scan private local files](https://jackjin1997.github.io/agent-audit-sprint/scan.html)
- MCP server security scan entry point: [run the focused scan page](https://jackjin1997.github.io/agent-audit-sprint/mcp-server-security-scan.html)
- MCP Security Radar: [public no-execution scan snapshot of popular MCP repos](https://jackjin1997.github.io/agent-audit-sprint/mcp-security-radar.html)
- Selected Radar scan briefs: [Playwright MCP](https://jackjin1997.github.io/agent-audit-sprint/reports/playwright-mcp-security-scan.html), [Chrome DevTools MCP](https://jackjin1997.github.io/agent-audit-sprint/reports/chrome-devtools-mcp-security-scan.html), [GitHub MCP Server](https://jackjin1997.github.io/agent-audit-sprint/reports/github-mcp-server-security-scan.html), [BrowserMCP](https://jackjin1997.github.io/agent-audit-sprint/reports/browsermcp-mcp-security-scan.html)
- Shareable scan link format: `https://jackjin1997.github.io/agent-audit-sprint/scan.html?repo=https://github.com/org/repo`
- Audit request packet: generated after each browser scan for copy/paste into a paid audit intake.
- GitHub Code Scanning/SARIF: [copy the workflow](https://jackjin1997.github.io/agent-audit-sprint/mcp-code-scanning-github-action.html) or use `jackjin1997/agent-mcp-code-scan-action@v1` with `sarif: "true"`.
- Public GitHub repo intakes get an automated no-execution scanner triage comment before paid scope acceptance.
- Standalone GitHub Action: [agent-mcp-code-scan-action](https://github.com/jackjin1997/agent-mcp-code-scan-action) with passing `@v1` Markdown/SARIF smoke test.
- Vertical pages:
  - [Trading MCP security audit](https://jackjin1997.github.io/agent-audit-sprint/trading-mcp-security-audit.html)
  - [Workspace MCP security audit](https://jackjin1997.github.io/agent-audit-sprint/workspace-mcp-security-audit.html)
  - [Cloud and database MCP security audit](https://jackjin1997.github.io/agent-audit-sprint/cloud-database-mcp-security-audit.html)
  - [Browser automation MCP security audit](https://jackjin1997.github.io/agent-audit-sprint/browser-automation-mcp-security-audit.html)
- Sample report index: [real public audit samples](https://jackjin1997.github.io/agent-audit-sprint/samples.html)
- Individual samples:
  - [douban-mcp audit sample](https://jackjin1997.github.io/agent-audit-sprint/reports/douban-mcp-sample-audit.html)
  - [firecrawl-mcp-server audit sample](https://jackjin1997.github.io/agent-audit-sprint/reports/firecrawl-mcp-sample-audit.html)
  - [browserbase/mcp-server-browserbase audit sample](https://jackjin1997.github.io/agent-audit-sprint/reports/browserbase-mcp-sample-audit.html)
- Intake: [start an audit request](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=audit-request.yml)

## What I Work On

| Area | Focus |
| --- | --- |
| Agent Harness | Agent Loop, ReAct, tool-call protocol, dynamic tool selection, state/checkpoint, multi-agent orchestration |
| Tool Use / MCP | Tool schema validation, timeout/fallback/degradation, MCP-based tool registration, permission boundaries |
| Context / State | LangGraph checkpoint, time travel, long-context compression, durable conversation state |
| Evals / Observability | LangSmith trace, LLM-as-Judge, offline eval datasets, trace-based failure attribution |
| Backend Infrastructure | TypeScript, Python, FastAPI, Hono, Redis, etcd, RabbitMQ, Docker, Kubernetes |

## Open Source Evidence

Merged upstream PRs around agent runtime, checkpoint consistency, tool-use edge cases, streaming, and deployment infrastructure.

| Project | Representative merged PRs |
| --- | --- |
| LangGraph JS | [#2516](https://github.com/langchain-ai/langgraphjs/pull/2516), [#2517](https://github.com/langchain-ai/langgraphjs/pull/2517), [#2518](https://github.com/langchain-ai/langgraphjs/pull/2518), [#2208](https://github.com/langchain-ai/langgraphjs/pull/2208), [#2186](https://github.com/langchain-ai/langgraphjs/pull/2186) |
| LangChain JS / LangChain | [langchainjs #10676](https://github.com/langchain-ai/langchainjs/pull/10676), [langchain #36108](https://github.com/langchain-ai/langchain/pull/36108), [langchain #34943](https://github.com/langchain-ai/langchain/pull/34943) |
| OpenViking | [#800 Kubernetes Helm Chart](https://github.com/volcengine/OpenViking/pull/800) |
| openclaw | [#47465 Markdown parsing fix](https://github.com/openclaw/openclaw/pull/47465) |
| Antigravity Awesome Skills | [#61](https://github.com/sickn33/antigravity-awesome-skills/pull/61), [#69](https://github.com/sickn33/antigravity-awesome-skills/pull/69) |
| Cosmos SDK | [#25863 proto file fix](https://github.com/cosmos/cosmos-sdk/pull/25863) |

## Selected Work

### IMEANAI-Coyage: multi-agent travel assistant

Built the engineering harness around a production multi-agent travel assistant:

- Supervisor plus 6 expert agents for hotel, flight, restaurant, attraction, itinerary, and currency domains.
- Dynamic Tool Selection to inject only relevant tool descriptions into the context window.
- Robust tool-call handling to prevent invalid message sequences, missing tool results, and agent dead loops.
- LangGraph Checkpoint and Time Travel for long-running conversations and node-level recovery.
- Multi-LLM fallback, tool timeout/circuit breaking, Redis buffering, prompt cache, and SSE streaming.
- LangSmith trace plus offline LLM-as-Judge eval loop to iterate prompt, harness, and tool descriptions.

### AI online service framework

Designed a lightweight runtime foundation for Agent and AI microservices:

- Decorator-based API definition with typed actions.
- RPC plus AsyncIterator streaming for Agent SSE inference flows.
- Zod validation for request and response contracts.
- etcd-based method-level leader election for distributed scheduled tasks.
- Dynamic config hot updates for model, temperature, and prompt templates without redeployment.
- Generated typed SDKs to reduce service-to-service glue code.

## Working Style

- I use AI coding tools heavily, but keep architecture, constraints, and quality gates under human control.
- I prefer traceable engineering evidence: merged PRs, runnable code, failure cases, logs, eval results, and design notes.
- I care about the space between model behavior and production reliability: where tools, state, context, evals, and product constraints meet.

## Links

- GitHub: [github.com/jackjin1997](https://github.com/jackjin1997)
- Site: [jzxwiki.com](https://jzxwiki.com)
- Email: [jackjin1997@gmail.com](mailto:jackjin1997@gmail.com)
