# Mohamed Azahrioui

**Software engineering · Backend & data systems · C++ / Linux performance**

`Computer Science @ Leiden University (2025–2028)` · `The Hague, Netherlands` · `Software developer @ CodeHive + Kojac`

I build software that has to work beyond the happy path: databases shaped by messy real-world data, integrations that can fail halfway through, and jobs that must recover without losing work.

I'm moving deeper into systems and performance engineering. Building production backends made me curious about what happens underneath them: memory layout, allocations, CPU caches, concurrency, and tail latency. I like testing assumptions, measuring results, and understanding *why* a system behaves the way it does.

---

### Production engineering

Most of my professional work lives in private client repositories. Some representative work:

- **Operations & data platform:** Sole developer of a production-deployed platform replacing a spreadsheet-based order process. Built a 22-table PostgreSQL model, FastAPI/React workflows, external API integrations, and Azure deployment. Added CI checks that verify database migrations can be applied, rolled back, and reapplied.
- **Engineering knowledge platform:** Built a bilingual search and retrieval system largely independently, using FastAPI, PostgreSQL/pgvector, and React. Developed a resumable private Linux indexing worker for 11 document formats, with quota-aware batching and duplicate-embedding reuse. Delivered 70 merged PRs; the project has 475 automated tests.
- **Medical AI software:** Built production review and recording workflows, including transcript-grounded notes, immutable note versions, recoverable audio uploads, and concurrency fixes for data-loss scenarios.

### Public projects

**[P99KV](https://github.com/MoAz06/P99KV)** · C++20 / Linux / performance

An in-memory key-value store for learning systems engineering from first principles. I'm exploring allocation costs, memory layout, CPU behavior, benchmarking, and latency. Removing an allocation-producing GET copy improved measured throughput by 59% in controlled interleaved runs, and investigating timing overhead exposed a benchmark measurement flaw.

**[ReachGate](https://github.com/MoAz06/ReachGate)** · Python / graph algorithms / software security

A deterministic vulnerability-reachability engine built around bounded graph traversal. It distinguishes reachable, not reachable, and **UNKNOWN** when the available evidence cannot support a conclusion. Produces OpenVEX/SARIF evidence, with offline verification.

**[FetchGate](https://github.com/MoAz06/FetchGate)** · Python / MCP / retrieval reliability

A fetch-boundary guardrail for AI agents. An HTTP 200 response is not proof that a page was actually read. FetchGate checks that distinction and prevents an agent from treating missing content as retrieved evidence.

**[TrustGate](https://github.com/MoAz06/TrustGate)** · Node.js / Google Cloud / BigQuery / Fivetran

A proof of concept for runtime AI-agent authorization using data freshness, schema checks, and connection evidence. The agent proposes an action; a deterministic policy engine decides whether to allow, require approval, or block it.

### Writing

I write about trustworthy software, AI failure modes, and how to make technical decisions verifiable.

- [The most dangerous AI error is the one nobody has to notice](https://moaz06.com/writing/the-most-dangerous-ai-error-is-the-one-nobody-has-to-notice)
- [A 200 Is Not a Read](https://moaz06.com/writing/a-200-is-not-a-read)
- [Most of your critical vulnerabilities cannot be reached](https://moaz06.com/writing/reachgate-reachability-deterministic-verdicts)
- [What Microsoft's Agent Governance Toolkit doesn't cover: data supply chain trust](https://moaz06.com/writing/data-supply-chain-trust-agent-governance)

### Tools I use

**Languages:** Python · C++ · TypeScript/JavaScript · SQL  
**Backend & data:** FastAPI · Django REST · PostgreSQL · SQLAlchemy · Alembic · pgvector · REST APIs  
**Systems & cloud:** Linux · Docker · Azure · Google Cloud · Git · CI/CD  
**Engineering:** data structures & algorithms · concurrency · failure recovery · testing · profiling & benchmarking

---

Interested in **summer 2027 software engineering internships**, especially backend, infrastructure, databases, and systems/performance.

[Portfolio](https://moaz06.com) · [Writing](https://moaz06.com/writing) · [LinkedIn](https://www.linkedin.com/in/mohamed-azahrioui-481100252/) · [Email](mailto:mohamedazahrioui2006@gmail.com)
