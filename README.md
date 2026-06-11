# Hi, I'm Mohsin 👋

I build AI agents and RAG systems for production.
Most of my time goes into the unglamorous parts: keeping token spend predictable, catching regressions in CI before users do, and making agent failures debuggable instead of mysterious.

**What I work on**

- AI Agents: single-agent, multi-agent, MCP-based, browser agents
- Evals: failure taxonomies built from reading real traces, deterministic code-graders, LLM-as-judge with measured TPR/TNR, regression gates wired into CI
- Cost: prompt caching, Redis semantic cache, context audits that cut 30-40% token waste, routing cheap models before expensive ones
- Agent reliability: retries with backoff, graceful degradation, approval gates before anything irreversible
- RAG: hybrid search and reranking on Qdrant, faithfulness evals on every prompt change
- Agent memory: consolidation pipelines, not just vector stores. What to write, what to refuse to write, how facts get superseded, how deletion actually sticks (Mem0, Zep)
- MCP servers done properly: per-user identity, tool-level permissions, audit logging
- Multi-tenant isolation: OpenFGA, Postgres RLS, cross-tenant attack tests that run in CI

**Stack**

Python · TypeScript · LangChain · LangGraph · OpenAI SDK · Google ADK
FastAPI · MCP · Redis · DeepEval · RAGAS · Langfuse · AWS  · DSPy

---

🌱 Building agents or RAG systems and hitting the messy parts (evals, memory, cost, multi-tenancy)? Happy to compare notes. DMs open.
