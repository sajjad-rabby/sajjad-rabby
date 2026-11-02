<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1E3A,50:1E4FD8,100:06B6D4&height=200&section=header&text=Sajjad%20Rabby&fontSize=56&fontColor=ffffff&animation=fadeIn&desc=AI%20Systems%20Architect%20%C2%B7%20Project%20%26%20Operations%20Lead&descSize=20&descAlignY=70" width="100%" alt="Sajjad Rabby — AI Systems Architect" />
</div>

<div align="center">
  <a href="https://github.com/sajjad-rabby">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=720&lines=AI+Systems+Architect;Project+%26+Operations+Lead;Stdlib-first+Python+for+production+LLM+systems;Governance+%C2%B7+Drift+monitoring+%C2%B7+Agent+guardrails+%C2%B7+RAG" alt="AI Systems Architect · Project & Operations Lead" />
  </a>
</div>

I build production Python systems for the parts of AI that break under real
load: model governance, drift monitoring, agent safety, and retrieval. I care
about software that a colleague can run at 2am without a phone call - which
usually means **zero mandatory dependencies** and **tests that run offline**.

---

## Featured work

Five complete, MIT-licensed Python libraries. Every one is stdlib-only at
runtime, fully type-hinted, documented, and ships with an offline test suite.

| Project | What it does | Tests |
|---|---|---|
| **[enterprise-llm-gateway](https://github.com/sajjad-rabby/enterprise-llm-gateway)** | One OpenAI-compatible API in front of many model providers, with response caching, strategy-driven routing, automatic failover, and an auditable spend ledger. | **145** passing |
| **[ai-governance-kit](https://github.com/sajjad-rabby/ai-governance-kit)** | AI governance workflow in one CLI: model cards, risk registers, EU AI Act classification, 21 CFR Part 11 / ALCOA+ checklists, and a hash-chained audit log. | **180** passing |
| **[drift-sentinel](https://github.com/sajjad-rabby/drift-sentinel)** | Production drift and LLM monitoring: PSI / KS / JS distance statistics, threshold alerting, Prometheus metrics export, and JSON + Markdown reports. | **178** passing |
| **[agent-guardrails](https://github.com/sajjad-rabby/agent-guardrails)** | Safety layer for tool-calling LLM agents: policy rules, human-in-the-loop approvals, tool/spend/time budgets, and a tamper-evident audit log. | **179** passing |
| **[rag-foundry](https://github.com/sajjad-rabby/rag-foundry)** | Modular retrieval-augmented generation pipeline: chunking, embedding, indexing, retrieval, grounded generation, and retrieval evaluation. | **101** passing |

**783 tests passing. Zero skipped. Zero runtime dependencies.**

Also: **[vet-checkin](https://github.com/sajjad-rabby/vet-checkin)** - a
multi-tenant veterinary clinic app on Next.js 15 / React 19 / TypeScript with
a typed Supabase data layer.

---

## Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js 15](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

![Tests](https://img.shields.io/badge/tests-783_passing-2EA043?style=for-the-badge)
![Runtime dependencies](https://img.shields.io/badge/runtime_dependencies-0-2EA043?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-2EA043?style=for-the-badge)

</div>

---

## GitHub stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=sajjad-rabby&show_icons=true&hide_border=true&theme=dark&count_private=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=sajjad-rabby&show_icons=true&hide_border=true&theme=default&count_private=true" />
    <img src="https://github-readme-stats.vercel.app/api?username=sajjad-rabby&show_icons=true&hide_border=true" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=sajjad-rabby&layout=compact&hide_border=true&theme=dark&langs_count=8" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=sajjad-rabby&layout=compact&hide_border=true&theme=default&langs_count=8" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sajjad-rabby&layout=compact&hide_border=true" alt="Top languages" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=sajjad-rabby&hide_border=true&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=sajjad-rabby&hide_border=true&theme=default" />
    <img src="https://streak-stats.demolab.com?user=sajjad-rabby&hide_border=true" alt="GitHub streak" />
  </picture>
</p>

---

## What I build

```mermaid
flowchart LR
    A[LLM applications] --> B[Retrieval]
    A --> C[Agents]
    A --> D[Governance]
    B --> E[drift-sentinel]
    C --> F[agent-guardrails]
    D --> G[ai-governance-kit]
    A --> H[enterprise-llm-gateway]
```

- **Reliability** - caching, retries, failover, timeouts, and budgets that
  actually stop runaway spend.
- **Observability** - drift metrics, Prometheus endpoints, and audit trails
  that are tamper-evident rather than merely present.
- **Compliance** - EU AI Act risk triage, NIST AI RMF risk registers, and
  21 CFR Part 11 style audit chains.
- **Security** - allow/deny policy, human approval for sensitive actions, and
  schema validation on every tool call.

---

## Engineering principles

**No mandatory dependencies.** Standard library only at runtime. A Python tool
that needs `pip install` before it can say hello is a tool that fails on the
machines where you need it most.

**Offline by default.** The whole test suite runs with no network and no
credentials. That makes it fast, deterministic, and safe in a locked-down
environment.

**Typed and documented.** Every public function carries type hints and a
docstring. `pyproject.toml`, MIT licence, and a README with a real architecture
diagram come with every project, not as an afterthought.

**Explain the numbers.** Monitoring tools are only useful if a human can read
the output and know what to do next. Reports are Markdown first, JSON second.

**Fail loudly, fail usefully.** Errors carry the context needed to act on them,
and the audit log records what was attempted - not just what succeeded.

---

## Current focus

- AI systems architecture and operational reliability for production LLM workloads
- Project and operations leadership
- Building evaluation and governance into AI delivery pipelines early, not at audit time

---

## Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-sajjad.sunyaad%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sajjad.sunyaad@gmail.com)
[![Website](https://img.shields.io/badge/Website-symcora.com-1E4FD8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://symcora.com/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--4410--8728-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0006-4410-8728)

</div>

Open to new roles in AI systems architecture and LLM engineering.

*Every project above is MIT licensed and maintained by me - pull requests and
issues are welcome.*
