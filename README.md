<img src="https://capsule-render.vercel.app/api?type=rect&color=0d1117&height=1&section=header" width="100%" />

<h1 align="center">Mansi Patil</h1>

<p align="center">
  <strong>Forward Deployed Engineer</strong>&nbsp;&nbsp;·&nbsp;&nbsp;GenAI @ IBM&nbsp;&nbsp;·&nbsp;&nbsp;MS Business Analytics, Purdue '26
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=16&duration=3000&pause=2000&color=58A6FF&center=true&vCenter=true&width=600&lines=I+ship+AI+into+customer+environments+%E2%80%94+not+demos;60%2B+merged+PRs+across+LlamaIndex+%C2%B7+DSPy+%C2%B7+CrewAI+%C2%B7+LangChain;4+GitHub+Actions+on+the+Marketplace;Multi-agent+systems+%C2%B7+RAG+%C2%B7+Guardrails+%C2%B7+LLM+Eval" alt="typing" />
</p>

<p align="center">
  <a href="mailto:mansianilpatil2425@gmail.com"><img src="https://img.shields.io/badge/email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/mansipatil22"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>&nbsp;
  <a href="https://ask-mansi.vercel.app"><img src="https://img.shields.io/badge/ask_my_portfolio-58A6FF?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI+PHBhdGggZD0iTTIxIDE1YTIgMiAwIDAgMS0yIDJINWwtNCA0VjVhMiAyIDAgMCAxIDItMmgxNGEyIDIgMCAwIDEgMiAyeiI+PC9wYXRoPjwvc3ZnPg==&logoColor=white" /></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=Mansi2221&color=555555&style=flat-square&label=views" />
</p>

---

I build production AI systems directly with customers — scope the problem, build the full stack, deploy into their environment, iterate until it runs at 3 AM without anyone watching. At IBM, I take GenAI products from prototype to production. Before that: multi-agent systems, RAG pipelines, guardrail engines, and full-stack AI apps.

**Currently:** shipping daily OSS contributions to [LlamaIndex](https://github.com/run-llama/llama_index), [DSPy](https://github.com/stanfordnlp/dspy), [CrewAI](https://github.com/crewAIInc/crewAI), [LangChain](https://github.com/langchain-ai/langchain), [Pydantic](https://github.com/pydantic/pydantic) — fixing real bugs in the AI infrastructure I deploy with.

---

### GitHub Actions — Marketplace

| Action | What it does | Install |
|--------|-------------|---------|
| **[ai-pr-summary](https://github.com/Mansi2221/ai-pr-summary)** | Auto-generates PR descriptions from diffs using Claude or GPT | `Mansi2221/ai-pr-summary@v1` |
| **[deploy-guard](https://github.com/Mansi2221/deploy-guard)** | Blocks deploys on missing env vars, Docker issues, leaked secrets | `Mansi2221/deploy-guard@v1` |
| **[llm-cost-check](https://github.com/Mansi2221/llm-cost-check)** | Estimates LLM API cost changes when PRs modify prompts or models | `Mansi2221/llm-cost-check@v1` |
| **[repo-health-score](https://github.com/Mansi2221/repo-health-score)** | Scores repo health across testing, docs, deps, security, CI/CD | `Mansi2221/repo-health-score@v1` |

---

### What I've Built

<table>
<tr>
<td width="50%" valign="top">

**[forge](https://github.com/Mansi2221/forge)** — AI Agent Evaluation Platform &nbsp; [![Live](https://img.shields.io/badge/live-58A6FF?style=flat-square)](https://web-lyart-gamma-37.vercel.app)

Multi-agent workflows, RAG with vector search, LLM eval with Claude-as-Judge, guardrails (injection, PII, toxicity, hallucination), rate limiting, model fallback, cost tracking.

`Python` `FastAPI` `Next.js` `Claude API` `LangGraph` `Docker`

</td>
<td width="50%" valign="top">

**[deploykit](https://github.com/Mansi2221/deploykit)** — Production Readiness Scanner &nbsp; [![Live](https://img.shields.io/badge/live-39d353?style=flat-square)](https://deploykit.vercel.app)

Paste a GitHub repo URL → instant production readiness report. Auto-detects project type, runs checks across security, LLM config, infra, cost, reliability. 52 tests, pip-installable.

`Python` `Next.js` `Pydantic` `Click` `Rich`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[eligible](https://github.com/Mansi2221/eligible)** — Clinical Trial Matching System

Patient-to-trial matching on OMOP-harmonized clinical data. Agentic eligibility matching, PHI redaction, tamper-evident audit chain, FHIR output, human-in-the-loop review.

`Python` `LangGraph` `dbt` `FastAPI` `Next.js`

</td>
<td width="50%" valign="top">

**[talent-rag](https://github.com/Mansi2221/talent-rag)** — Production RAG for Talent Intelligence

Hybrid retrieval (sparse + dense), cross-encoder reranking, ensemble generation with LLM judge, async indexing, full eval suite. Built for real recruiter workflows.

`Python` `FastAPI` `FAISS` `Streamlit` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[gitpulse](https://github.com/Mansi2221/gitpulse)** — Developer Intelligence Dashboard &nbsp; [![Live](https://img.shields.io/badge/live-A371F7?style=flat-square)](https://gitpulse-ruddy.vercel.app)

Paste any GitHub username → contribution heatmap, language distribution, coding patterns, repo quality. Side-by-side developer comparison.

`Next.js` `TypeScript` `Recharts` `GitHub API`

</td>
<td width="50%" valign="top">

**[clarify](https://github.com/Mansi2221/clarify)** — AI Business Analyst Agent &nbsp; [![Live](https://img.shields.io/badge/live-F97316?style=flat-square)](https://clarify-alpha.vercel.app)

Brief in, full BA deliverable pack out: requirements doc, RTM, test cases, RACI. Asks clarifying questions first — no hallucinated requirements.

`Next.js 16` `React 19` `TypeScript` `Vercel AI SDK`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[travelmind](https://github.com/Mansi2221/travelmind)** — Real-time AI Travel Agent &nbsp; [![Live](https://img.shields.io/badge/live-10B981?style=flat-square)](https://travelmind-ten.vercel.app)

5 parallel tool calls, real-time web search, structured travel briefings in under 10s. Streaming responses on Vercel.

`Next.js` `Groq` `Tavily` `Vercel`

</td>
<td width="50%" valign="top">

**[keystone](https://github.com/Mansi2221/keystone)** — Enterprise AI Agent with RBAC

Permission-aware enterprise AI agent with ablation study. Role-based access control over tool execution.

`Python` `FastAPI`

</td>
</tr>
</table>

---

### Open Source Contributions

I contribute to the AI infrastructure I deploy with — and review others' code too.

<details>
<summary><strong>60+ PRs across 10 repos</strong> — click to expand full list</summary>

| Repo | Fix | PR |
|------|-----|-----|
| **run-llama/llama_index** | SimpleVectorStore TypeError on heterogeneous range filters | [#24488](https://github.com/run-llama/llama_index/pull/24488) |
| **run-llama/llama_index** | SimpleVectorStore conflates bool and int in EQ/NE filters | [#24487](https://github.com/run-llama/llama_index/pull/24487) |
| **run-llama/llama_index** | VoyageEmbedding drops output dimension/dtype in multimodal | [#24486](https://github.com/run-llama/llama_index/pull/24486) |
| **run-llama/llama_index** | ChatPromptHelper ignores tokenizer in async methods | [#24441](https://github.com/run-llama/llama_index/pull/24441) |
| **run-llama/llama_index** | UnstructuredReader.from_api positional arg TypeError | [#24440](https://github.com/run-llama/llama_index/pull/24440) |
| **run-llama/llama_index** | ZendeskReader ignores HTTP errors, no timeout | [#24422](https://github.com/run-llama/llama_index/pull/24422) |
| **run-llama/llama_index** | Hardcoded API key in Vercel AI Gateway notebook | [#24421](https://github.com/run-llama/llama_index/pull/24421) |
| **run-llama/llama_index** | legacy_json_to_doc crashes on null relationships | [#24420](https://github.com/run-llama/llama_index/pull/24420) |
| **run-llama/llama_index** | OpenAIResponses stream_chat reports failed as empty success | [#24384](https://github.com/run-llama/llama_index/pull/24384) |
| **run-llama/llama_index** | FunctionTool drops Field(pattern=...) from schema | [#24383](https://github.com/run-llama/llama_index/pull/24383) |
| **run-llama/llama_index** | AutoMergingRetriever missing one-chunk context gap | [#24382](https://github.com/run-llama/llama_index/pull/24382) |
| **run-llama/llama_index** | Memory flush wiping nearly all history on small token_limit | [#24381](https://github.com/run-llama/llama_index/pull/24381) |
| **run-llama/llama_index** | NLTK cache permissions — nltk 3.10.4 rejects group-writable | [#24380](https://github.com/run-llama/llama_index/pull/24380) |
| **run-llama/llama_index** | Triplet parser fails on nested parentheses | [#24361](https://github.com/run-llama/llama_index/pull/24361) |
| **run-llama/llama_index** | 9 incorrect Colab badge links in LLM notebooks | [#24301](https://github.com/run-llama/llama_index/pull/24301) |
| **run-llama/llama_index** | Local OpenAILike server docs — vLLM, LM Studio | [#24110](https://github.com/run-llama/llama_index/pull/24110) |
| **stanfordnlp/dspy** | ChatAdapter completed marker regex | [#10967](https://github.com/stanfordnlp/dspy/pull/10967) |
| **stanfordnlp/dspy** | JSONAdapter alphabetising Pydantic property names | [#10940](https://github.com/stanfordnlp/dspy/pull/10940) |
| **stanfordnlp/dspy** | Semantic judge metrics turning NaN into perfect scores | [#10939](https://github.com/stanfordnlp/dspy/pull/10939) |
| **stanfordnlp/dspy** | ReAct packing tool erasing item list from history | [#10938](https://github.com/stanfordnlp/dspy/pull/10938) |
| **stanfordnlp/dspy** | Empty signature instructions replaced with default | [#10937](https://github.com/stanfordnlp/dspy/pull/10937) |
| **stanfordnlp/dspy** | COPRO.compile crash on Evaluate constructor-only params | [#10936](https://github.com/stanfordnlp/dspy/pull/10936) |
| **crewAIInc/crewAI** | Azure completion params missing seed | [#9809](https://github.com/crewAIInc/crewAI/pull/9809) |
| **crewAIInc/crewAI** | Gemini completion params missing seed | [#9748](https://github.com/crewAIInc/crewAI/pull/9748) |
| **crewAIInc/crewAI** | Offline custom LLM quick-start docs | [#9700](https://github.com/crewAIInc/crewAI/pull/9700) |
| **crewAIInc/crewAI** | save_artifact missing image format check | [#9652](https://github.com/crewAIInc/crewAI/pull/9652) |
| **crewAIInc/crewAI** | Offline custom LLM example | [#9651](https://github.com/crewAIInc/crewAI/pull/9651) |
| **crewAIInc/crewAI** | Agent.copy() sharing mutable LLM dicts | [#9650](https://github.com/crewAIInc/crewAI/pull/9650) |
| **crewAIInc/crewAI** | Token usage double-counting on shared LLM | [#9644](https://github.com/crewAIInc/crewAI/pull/9644) |
| **langchain-ai/langchain** | MCP tool args named config/run_manager silently swallowed | [#42023](https://github.com/langchain-ai/langchain/pull/42023) |
| **pydantic/pydantic** | Negative indices in include/exclude on Sequence fields | [#14380](https://github.com/pydantic/pydantic/pull/14380) |
| **BerriAI/litellm** | max_parallel_requests admitting 2x after cache expiry | [#53577](https://github.com/BerriAI/litellm/pull/53577) |
| **microsoft/agent-governance-toolkit** | PII false positives in MCP Security Gateway — 27 tests | [#4608](https://github.com/microsoft/agent-governance-toolkit/pull/4608) |
| **anthropics/anthropic-cookbook** | Scenario analysis state leak | [#983](https://github.com/anthropics/anthropic-cookbook/pull/983) |
| **anthropics/anthropic-cookbook** | Stale cache bug in DCF projections | [#982](https://github.com/anthropics/anthropic-cookbook/pull/982) |
| **anthropics/anthropic-cookbook** | Ratio trend zero baseline inf handling | [#981](https://github.com/anthropics/anthropic-cookbook/pull/981) |
| **anthropics/anthropic-cookbook** | Tornado analysis ZeroDivisionError | [#980](https://github.com/anthropics/anthropic-cookbook/pull/980) |
| **anthropics/anthropic-cookbook** | Stray = in evals grader prompt | [#973](https://github.com/anthropics/anthropic-cookbook/pull/973) |
| **anthropics/anthropic-cookbook** | Session browser blank lines | [#972](https://github.com/anthropics/anthropic-cookbook/pull/972) |
| **anthropics/anthropic-cookbook** | Updated supported models in memory cookbook | [#966](https://github.com/anthropics/anthropic-cookbook/pull/966) |
| **AI4Finance/FinRL** | UTC-aware timestamps in CCXT processor | [#1488](https://github.com/AI4Finance-Foundation/FinRL/pull/1488) |

</details>

<details>
<summary><strong>Code Reviews</strong> — 3 PR authors implemented changes based on my feedback</summary>

| Repo | PR Reviewed | Feedback |
|------|------------|----------|
| **BerriAI/litellm** | [#53578](https://github.com/BerriAI/litellm/pull/53578) | Bedrock rerank config — nested dict traversal |
| **langchain-ai/langchain** | [#42011](https://github.com/langchain-ai/langchain/pull/42011) | Auth token provider — exception path |
| **run-llama/llama_index** | [#24391](https://github.com/run-llama/llama_index/pull/24391) | Embedding batch perf — flagged unrelated commit |
| **run-llama/llama_index** | [#24386](https://github.com/run-llama/llama_index/pull/24386) | Tool schema required field handling |
| **crewAIInc/crewAI** | [#9656](https://github.com/crewAIInc/crewAI/pull/9656) | Foreign model schema validation |
| **crewAIInc/crewAI** | [#9653](https://github.com/crewAIInc/crewAI/pull/9653) | Guardrail retry context preservation |
| **stanfordnlp/dspy** | [#10943](https://github.com/stanfordnlp/dspy/pull/10943) | Variadic tuple Ellipsis rendering |
| **stanfordnlp/dspy** | [#10942](https://github.com/stanfordnlp/dspy/pull/10942) | UTF-8 encoding for Evaluate results |
| **pydantic/pydantic** | [#14374](https://github.com/pydantic/pydantic/pull/14374) | ImportString TypeError for relative paths |

</details>

<details>
<summary><strong>Community Answers</strong> — GitHub Discussions</summary>

| Repo | Topic | Link |
|------|-------|------|
| **run-llama/llama_index** | VertexAI Gemini structured output with LLMReranker | [#17576](https://github.com/run-llama/llama_index/discussions/17576) |
| **run-llama/llama_index** | Rate limiting LLM pipelines | [#17697](https://github.com/run-llama/llama_index/discussions/17697) |
| **run-llama/llama_index** | PGVector hybrid search — hybrid_top_k not implemented | [#19606](https://github.com/run-llama/llama_index/discussions/19606) |
| **run-llama/llama_index** | Source nodes missing after FunctionAgent migration | [#20494](https://github.com/run-llama/llama_index/discussions/20494) |
| **run-llama/llama_index** | MetadataFilter NOT condition semantics | [#19112](https://github.com/run-llama/llama_index/discussions/19112) |
| **run-llama/llama_index** | OpenAILike for vLLM local inference | [#16899](https://github.com/run-llama/llama_index/discussions/16899) |
| **run-llama/llama_index** | NLSQLTableQueryEngine debugging | [#14007](https://github.com/run-llama/llama_index/discussions/14007) |

</details>

---

### Tech Stack

```
Languages       Python · TypeScript · SQL
AI/ML           Claude API · LangChain · LangGraph · DSPy · CrewAI · LiteLLM · Vercel AI SDK · FAISS · HuggingFace
Backend         FastAPI · Node.js · Supabase · PostgreSQL · Redis
Frontend        Next.js (App Router) · React · Tailwind CSS · shadcn/ui
Infrastructure  Docker · Vercel · AWS · GitHub Actions
Specialization  Multi-agent systems · RAG · Guardrails · LLM Evaluation · Production AI
```

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mansi2221&theme=transparent&hide_border=true&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" width="48%" alt="streak" />
  <img src="https://github-readme-stats.vercel.app/api?username=Mansi2221&show_icons=true&theme=transparent&hide_border=true&icon_color=58A6FF&title_color=58A6FF&include_all_commits=true&count_private=true" width="48%" alt="stats" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Mansi2221&theme=github-compact&hide_border=true&area=true" width="95%" alt="activity" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Mansi2221&theme=github_dark" height="160" alt="repos per language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Mansi2221&theme=github_dark" height="160" alt="most commit language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Mansi2221&theme=github_dark&utcOffset=-5" height="160" alt="productive time" />
</p>

---

<p align="center">
  <strong>Open to Forward Deployed Engineer roles</strong><br/>
  <sub>I want to sit with your customers, understand their problems, build the system, and ship it into their environment.</sub><br/><br/>
  <a href="mailto:mansianilpatil2425@gmail.com"><img src="https://img.shields.io/badge/Get_in_touch-mansianilpatil2425@gmail.com-58A6FF?style=flat-square" /></a>&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/mansipatil22"><img src="https://img.shields.io/badge/LinkedIn-mansipatil22-58A6FF?style=flat-square" /></a>
</p>
