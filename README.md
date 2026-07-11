# › Mohamed Azahrioui

**Backend & AI-security developer — I build deterministic, auditable guardrails for AI agents.**

The idea behind everything I build: let a deterministic rule engine make the
decision, and let the model only *explain* it. The moment the model gets to
decide, you've traded a verifiable answer for a confident guess — and in
security and agent actions, that trade isn't worth it. So every decision ships
as proof you can verify yourself.

`backend developer` · `The Hague, NL` · `CS @ Leiden` · shipping production code at `CodeHive` + `Kojac`

---

### Selected work

**[ReachGate](https://github.com/MoAz06/ReachGate)** — vulnerability-reachability triage on GitLab Orbit

Walks the code graph with a bounded BFS to answer what scanners can't: *can this
vulnerability actually be reached from the app's entry points?* On the codebases
I tested ~80% of "critical" findings came back not reachable. Deterministic
verdicts, `UNKNOWN` when unproven, OpenVEX/SARIF exports, an sha256 manifest +
optional Ed25519 signature, and an offline verifier that needs no token and no network.

`Python` · `BFS` · `OpenVEX` · `SARIF` · `Ed25519` · `MCP` · `pytest`

**[TrustGate](https://github.com/MoAz06/trustgate-ai-agents)** — runtime authorization gate for AI agents

Sits between an agent and a risky action (like a refund) and checks live business
evidence before it runs: `ALLOW`, `APPROVAL_REQUIRED`, or `BLOCK`, each with an
auditable receipt. The model proposes; the policy engine decides.

`Node.js` · `Google Cloud Run` · `Vertex AI / Gemini` · `BigQuery` · `Fivetran` · `MCP` · `React`

---

### Writing

I write about agent governance, reachability, and data-supply-chain trust — the
questions that show up once agents meet real operational data.

- [Most of your critical vulnerabilities cannot be reached](https://moaz06.com/writing/reachgate-reachability-deterministic-verdicts)
- [What Microsoft's Agent Governance Toolkit doesn't cover: data supply chain trust](https://moaz06.com/writing/data-supply-chain-trust-agent-governance)

---

### Stack

**Languages** Python · TypeScript · JavaScript/Node · C++ · SQL
**AI & security** agent guardrails · RAG · MCP · policy engines · reachability analysis · OpenVEX · SARIF · Ed25519
**Backend** FastAPI · Flask · Node · REST · WebSockets · JWT/OAuth2 · SQLAlchemy · Alembic
**Cloud & data** Azure OpenAI · Azure AI Search · Google Cloud Run · BigQuery · Docker · PostgreSQL

---

🌐 [moaz06.com](https://moaz06.com) · 💼 [LinkedIn](https://www.linkedin.com/in/mohamed-azahrioui-481100252/) · ✉️ mohamedazahrioui2006@gmail.com
