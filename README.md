# Hi, I'm Aari

**Agent runtime & memory engineer** · MSc AI, researching agent memory systems · Shenzhen, China

Collaborator on [bytedance/deer-flow](https://github.com/bytedance/deer-flow) (82k★) · [100+ merged upstream PRs](https://github.com/search?q=is%3Apr+author%3AAnnaSuSu+is%3Amerged+-user%3AAnnaSuSu&type=pullrequests) · Open to AI agent / LLM infra internships

> I work on the layer under the agent — the harness, the sandbox, the memory, the parts that break in production.

## What I work on

In DeerFlow, a LangGraph-based long-horizon agent harness, I've designed and shipped:

- **Long-running agents** — a durable task runtime that lets tool work outlive the agent turn, and managed subagents with bounded, recoverable fan-out. ([design](https://github.com/bytedance/deer-flow/issues/4652#issuecomment-5174089301))
- **Sandbox & agent security** — controlled network egress with human approval, plus prompt-injection and secret-containment hardening across the harness. ([egress](https://github.com/bytedance/deer-flow/pull/5152))
- **Memory & context** — long-term memory hygiene and eviction, and context compaction for the lead agent. ([RFC](https://github.com/bytedance/deer-flow/issues/4346))
- **Streaming performance** — found and removed the main-thread bottlenecks behind long streamed runs. ([analysis](https://github.com/bytedance/deer-flow/issues/4409))

Also contributing to [infiniflow/ragflow](https://github.com/infiniflow/ragflow) · [Canner/WrenAI](https://github.com/Canner/WrenAI) · [Effect-TS/effect](https://github.com/Effect-TS/effect) · [mem0ai/mem0](https://github.com/mem0ai/mem0)

## Own projects

- **[TechSpar](https://github.com/AnnaSuSu/TechSpar)** ![stars](https://img.shields.io/github/stars/AnnaSuSu/TechSpar?style=social) — memory-driven adaptive interview coach: one candidate profile drives training, resume/JD prep, a real-time copilot and review in a self-improving loop (LangGraph + 3-tier memory). [Live](https://techspar.cn)
- [arxiv-mcp](https://github.com/AnnaSuSu/arxiv-mcp) — MCP server for searching and reading arXiv papers ([PyPI](https://pypi.org/project/arxiv-paper-mcp-server/))
- [EvoGraph](https://github.com/AnnaSuSu/EvoGraph) — minimalist graph-based long-term conversational memory
- [MemRepo](https://github.com/AnnaSuSu/MemRepo) — incremental, hierarchical codebase memory for AI coding assistants

## Honors

- Patent — *Microkernel-architecture context manager for large language models*
- 2nd Prize — ASC25 Student Supercomputer Challenge
- Kaggle Bronze — Jigsaw Agile Community Rules Classification (SFT track)
- 3rd Prize — China Postgraduate Mathematical Contest in Modeling (2025)

📫 ansusu1025@gmail.com · [Kaggle](https://kaggle.com/tremorix)
