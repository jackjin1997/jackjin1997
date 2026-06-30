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
- LLM/agent summary: [machine-readable service map](https://jackjin1997.github.io/agent-audit-sprint/llms.txt)
- AI agent security audit: [tool calls, prompt/tool injection, browser sessions, memory/state, and launch risk](https://jackjin1997.github.io/agent-audit-sprint/ai-agent-security-audit-service.html)
- AI cost spike emergency sprint: [USD $1,000 emergency review for runaway LLM bills, agent loops, RAG over-retrieval, retry storms, model-routing drift, cache misses, and launch-pricing risk](https://jackjin1997.github.io/agent-audit-sprint/ai-cost-spike-emergency.html); [open the emergency intake](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ai-cost-spike-emergency.yml) to request scope before any payment.
- AI agent cost leak review: [USD $299 focused review for token spend, context bloat, RAG over-retrieval, model-routing drift, retry loops, cache misses, and coding-agent tool-call loops](https://jackjin1997.github.io/agent-audit-sprint/ai-agent-cost-leak-review.html); [open the Cost Leak intake](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=agent-cost-leak-review.yml) to request scope before any payment.
- Agent auth and cookie vault review: [USD $299 focused review for token brokers, cookie vaults, site_login, OAuth/HITL consent, authenticated scraping, and cache isolation](https://jackjin1997.github.io/agent-audit-sprint/agent-auth-security-review.html); [open the Agent Auth intake](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=agent-auth-review.yml) to request scope before any payment.
- MCP SSRF review: [USD $299 focused review for dynamic URL fetch, pagination URL, callback, redirect, webhook, proxy, and SSRF-with-credentials boundaries](https://jackjin1997.github.io/agent-audit-sprint/mcp-ssrf-security-review.html); [open the MCP SSRF intake](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=mcp-ssrf-review.yml) to request scope before any payment.
- AI Agent Security Radar: [no-execution scan snapshot of browser-use, OpenHands, AutoGen, CrewAI, Agno, LangGraph, smolagents, and OpenAI Agents Python](https://jackjin1997.github.io/agent-audit-sprint/ai-agent-security-radar.html)
- AI Agent Radar scan briefs: [browser-use](https://jackjin1997.github.io/agent-audit-sprint/reports/browser-use-ai-agent-security-scan.html), [OpenHands](https://jackjin1997.github.io/agent-audit-sprint/reports/openhands-ai-agent-security-scan.html), [smolagents](https://jackjin1997.github.io/agent-audit-sprint/reports/smolagents-ai-agent-security-scan.html), [OpenAI Agents Python](https://jackjin1997.github.io/agent-audit-sprint/reports/openai-agents-python-security-scan.html)
- Browser scanner: [paste a public GitHub URL or scan private local files](https://jackjin1997.github.io/agent-audit-sprint/scan.html)
- MCP server security scan entry point: [run the focused scan page](https://jackjin1997.github.io/agent-audit-sprint/mcp-server-security-scan.html)
- MCP Security Radar: [public no-execution scan snapshot of popular MCP repos](https://jackjin1997.github.io/agent-audit-sprint/mcp-security-radar.html)
- Selected Radar scan briefs: [Playwright MCP](https://jackjin1997.github.io/agent-audit-sprint/reports/playwright-mcp-security-scan.html), [Chrome DevTools MCP](https://jackjin1997.github.io/agent-audit-sprint/reports/chrome-devtools-mcp-security-scan.html), [GitHub MCP Server](https://jackjin1997.github.io/agent-audit-sprint/reports/github-mcp-server-security-scan.html), [BrowserMCP](https://jackjin1997.github.io/agent-audit-sprint/reports/browsermcp-mcp-security-scan.html)
- Shareable scan link format: `https://jackjin1997.github.io/agent-audit-sprint/scan.html?repo=https://github.com/org/repo`
- Audit request packet: generated after each browser scan for copy/paste into a paid audit intake.
- GitHub Code Scanning/SARIF: [copy the workflow](https://jackjin1997.github.io/agent-audit-sprint/mcp-code-scanning-github-action.html) or use `jackjin1997/agent-mcp-code-scan-action@v1` with `sarif: "true"`; current `@v1` flags dynamic URL fetch and SSRF-with-credentials evidence and routes it to the [USD $299 MCP SSRF review](https://jackjin1997.github.io/agent-audit-sprint/mcp-ssrf-security-review.html).
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

## Available: AI Jingle / Podcast Sponsor Audio Packs

I am also testing fixed-price AI-assisted short brand audio packages for podcasts, sponsor reads, SaaS/Product Hunt launch videos, ecommerce product videos, local ads, UGC agency approval packets, radio IDs, and creator intros. The lowest-friction first test is a $29 founding hook sketch; the fastest-fit full offer is a $149 podcast sponsor jingle pack for media-kit owners who already sell host-read ads or branded segments.

- AI music generator storefront: [choose a USD $29 short music sketch for SaaS/Product Hunt launch videos, ecommerce product videos, ads, listing videos, wedding highlights, podcasts, sponsor cues, or creator intros](https://jackjin1997.github.io/agent-audit-sprint/ai-music-generator.html)
- AI music samples and order packets: [hear Product Demo Hook, Coffee Shop 30s Hook, Business Show Intro, and Radio ID And Drop, then copy or email a matching USD $29 brief packet](https://jackjin1997.github.io/agent-audit-sprint/ai-music-samples.html) before opening a general or product-video order.
- $29 hook sketch: [USD $29 Founding Hook Sketch for one 8-12 second branded hook direction](https://jackjin1997.github.io/agent-audit-sprint/ai-jingle-hook-sketch.html)
- Commercial jingle generator: [USD $29 local ad hook for small business audio ads and social promos](https://jackjin1997.github.io/agent-audit-sprint/ai-commercial-jingle-generator.html)
- SaaS launch video music generator: [USD $29 Product Hunt launch / SaaS demo music hook with dedicated order form](https://jackjin1997.github.io/agent-audit-sprint/ai-saas-launch-video-music.html); [open the SaaS launch order form](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ai-saas-launch-video-music-order.yml) after the brief is ready.
- Product video music generator: [USD $29 ecommerce product demo / Shopify / TikTok Shop music hook with dedicated order form](https://jackjin1997.github.io/agent-audit-sprint/ai-product-video-music.html)
- Product video sample-to-order: [listen to Product Demo Hook](https://jackjin1997.github.io/agent-audit-sprint/assets/audio/product-demo-hook.wav), then [copy the sample-to-order packet](https://jackjin1997.github.io/agent-audit-sprint/ai-product-video-music.html#samples) or [open the product video order form](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ai-product-video-music-order.yml) with the reference-sample selector.
- Short-form ad music generator: [USD $29 TikTok/Reels/Shorts/UGC hook packet with email handoff, order link, acceptance/payment text, WAV sketch, source-rights brief, and commercial-use memo](https://jackjin1997.github.io/agent-audit-sprint/ai-short-form-ad-music.html)
- UGC agency music hooks: [USD $29 client approval audio hook sketch for paid-social teams, with source-rights memo and $149 agency ad music pack upsell](https://jackjin1997.github.io/agent-audit-sprint/ugc-agency-ai-music-hooks.html); [open the dedicated UGC agency order form](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ugc-agency-music-hook-order.yml) after the brief is ready.
- Real estate listing music generator: [USD $29 listing video soundtrack sketch for property reels and walkthrough clips](https://jackjin1997.github.io/agent-audit-sprint/ai-real-estate-listing-music.html)
- Wedding video music generator: [USD $29 wedding highlight soundtrack sketch for teaser reels and filmmaker edits](https://jackjin1997.github.io/agent-audit-sprint/ai-wedding-video-music.html)
- Podcast intro generator: [USD $29 podcast intro hook for show openers, outro bumps, and segment stings](https://jackjin1997.github.io/agent-audit-sprint/ai-podcast-intro-generator.html)
- Podcast sponsor pack: [USD $149 sponsor-safe audio hook for host-read ads and media-kit upsells](https://jackjin1997.github.io/agent-audit-sprint/podcast-sponsor-jingle.html)
- AI jingle generator page: [USD $29 / $79 / $149 / $399 packages with samples and local brief builder](https://jackjin1997.github.io/agent-audit-sprint/ai-jingle-generator.html)
- Quote/payment packet: [fixed AI jingle package quotes](https://jackjin1997.github.io/agent-audit-sprint/ai-jingle-quote.html)
- Email brief: [jackjin1997@gmail.com](mailto:jackjin1997@gmail.com) for podcast, business, radio, or agency buyers who do not use GitHub; the sample page now opens email-ready packets with the selected public reference included.
- AI music discussion: [SaaS launch, product video, short-form, and UGC agency music hook announcement](https://github.com/jackjin1997/agent-audit-sprint/discussions/7)
- Intake: [start a general AI jingle order](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ai-jingle-order.yml), [start a SaaS launch video music order](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ai-saas-launch-video-music-order.yml), [start a product video music order](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ai-product-video-music-order.yml), or [start a UGC agency music hook order](https://github.com/jackjin1997/agent-audit-sprint/issues/new?template=ugc-agency-music-hook-order.yml) if a tracked issue is easier.

Payment is requested only after a written brief/package is accepted. No known-artist soundalikes, living voice clones, or third-party lyrics without rights.

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
