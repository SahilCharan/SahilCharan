# Kumar Sahil

**Forward Deployed AI Engineer.** I build production LLM systems inside real businesses: agents with evals, data pipelines, and the infrastructure that keeps them cheap and safe. New Delhi, working remote with US and EU teams.

Head of AI Automation at [WorkinX Digital](https://workinxdigital.com) · Embedded AI/GTM engineer for [Kodify](https://kodify.eu) (Netherlands) · Founder, Dwary Intech

---

### What I've shipped (2026)

**VirtualPhotography.ai** · AI product-photography platform used by WorkinX's 20-designer creative team
- A product's full image set in ~20 minutes instead of ~2 days of design work
- Next.js + 6 TypeScript services + a Python/FastAPI AI pipeline, 19 Render services, 975 of 994 commits
- Vision-LLM QC gate with hard identity and label floors; GPT Image cost $0.094 → $0.030 per image (-69%)
- Vendor exit of ~25 LLM call sites to a provider-neutral gateway: vision-call cost ~12x lower, one-flag rollback

**WorkinX SEO** · multi-tenant AI SEO and content platform, publishing live to 4 sites
- 15-queue BullMQ pipeline with job leases and idempotent claims; sole engineer through launch (692 of 765 commits)
- Tenant isolation proven across 199 routes / 229 probes with 0 failures; ~1,000 tests, 74/74 Playwright e2e

**Amazon lead-gen pipeline** · 4.56M SmartScout rows (832K brands, 3.7M products) across US, UK, CA, AU
- 8 stages from load and dedupe to ICP tiering, AI domain verification, title-gated contact discovery and email finding
- Every count reconciled to source by audit gates; a paid-call ledger means no record is ever charged twice

**Kodify (embedded)** · production GTM backend on the client's own Scaleway cloud
- Root-caused a silent HubSpot write failure; rebuilt reply handling as a 6-layer classifier cascade: deal precision 67% → 100%
- Claude Code agent that edits the company website from click annotations, gated by allowlist, build check and human preview

**SIGNAL** · Claude agent that turns news, YouTube and LinkedIn signals into founder-voiced posts (853 drafts in 4 months)

**Quote agent** · tool-calling agent that cannot invent prices; a 100-case live eval suite in nightly CI caught 3 real defects pre-launch

---

### Open source

| Repo | What it shows |
|---|---|
| [llm-eval-gauntlet](https://github.com/SahilCharan/llm-eval-gauntlet) | Invariant-checked eval suites for tool-calling agents, run as a CI gate |
| [llm-gateway](https://github.com/SahilCharan/llm-gateway) | Job-routed multi-provider LLM gateway with safe failover and a cost ledger |
| [reply-classifier-cascade](https://github.com/SahilCharan/reply-classifier-cascade) | Cost-ordered EN/NL reply classifier: synthetic training, real held-out evals |
| [workinx-pm-intelligence](https://github.com/SahilCharan/workinx-pm-intelligence) | Scheduled Claude routine over ClickUp and Slack via MCP |

---

**Stack:** Python · TypeScript · FastAPI · Next.js · Postgres/pgvector · Redis/BullMQ · Docker · Render · Cloudflare Workers · Scaleway · Modal · Claude / OpenAI / Gemini / DeepSeek · n8n · Clay · HubSpot

**How I work:** AI-native. I run Claude Code and Codex agent teams with file ownership and test-gated merges, and I back every model choice with measured cost, latency and quality.

[LinkedIn](https://www.linkedin.com/in/sahil-dwary) · sahilcharandwary@gmail.com
