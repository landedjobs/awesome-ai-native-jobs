<a name="top"></a>

<div align="center">

<a href="https://landed.jobs"><img src="https://static.b100x.ai/email/landed-wordmark.png" alt="Landed" width="200"></a>

<img src="https://static.b100x.ai/github-repos/images/awesome-ai-native-jobs/banner.svg" alt="Awesome AI-Native Jobs" width="100%">

[![Stars](https://img.shields.io/github/stars/landedjobs/awesome-ai-native-jobs?style=social)](https://github.com/landedjobs/awesome-ai-native-jobs)
[![License: MIT](https://img.shields.io/badge/License-MIT-6C2BD9.svg)](LICENSE)
[![Updated](https://img.shields.io/badge/updated-weekly-00A86B)](https://github.com/landedjobs)
[![Visit Landed](https://img.shields.io/badge/Visit-Landed-6C2BD9?logo=rocket&logoColor=white)](https://landed.jobs)

**A curated map of the new generation of AI-native jobs** — the roles, real salaries, skills, interview prep, and projects to land them.

*Maintained by [Landed](https://landed.jobs) — daily AI-native job matches, agent help with every application, and mock-interview prep.*

</div>

---

The job market is being rewritten. "Product Manager" is becoming **AI Product Engineer**. "Marketer" is becoming **GTM Engineer**. Whole new titles — **Forward-Deployed Engineer, RAG Engineer, Context Engineer** — barely existed two years ago, and roles needing AI skills now carry a **~56% wage premium**. This repo maps that shift and gives you everything to break in.

> ⭐ **Star this repo** — it's the umbrella for a whole set of curated job lists, interview guides, and roadmaps, refreshed regularly.

```mermaid
flowchart LR
    PM["📋 Product Manager"] --> APE["🤖 AI Product Engineer"]
    MKT["📣 Marketer / SDR"] --> GTM["🚀 GTM Engineer"]
    DA["📊 Data Analyst"] --> RAG["🔎 RAG / Analytics Engineer"]
    SE["🛠️ Solutions Engineer"] --> FDE["🤝 Forward-Deployed Engineer"]
    style APE fill:#6C2BD9,color:#fff
    style GTM fill:#6C2BD9,color:#fff
    style RAG fill:#6C2BD9,color:#fff
    style FDE fill:#6C2BD9,color:#fff
```

## Contents

- [The new AI-native roles](#the-new-ai-native-roles) (with real salaries + skills)
- [The full family](#the-full-family) — every repo we maintain
- [The data](#the-data)
- [FAQ](#faq)
- [Contributing](#contributing)

---

## The new AI-native roles

> Comp = approximate 2026 ranges (base, US unless noted; India where relevant), aggregated from public salary reports. Total comp runs higher with equity, especially at frontier labs.

### 🤖 AI Engineer
Builds products on top of LLMs — RAG, agents, evals, inference. Most roles want shipping ability, **not** an ML PhD.
- **Skills:** Python, LLM APIs, RAG, agents/tool-use, evals, vector DBs, some TypeScript.
- **Comp:** US base **$145K–$310K** (senior SF/NY $400K+ TC). India **₹12–18L** entry → **₹55L–₹1.1Cr** senior at top product cos.
- **Hiring:** frontier labs, applied-AI startups, enterprise AI teams. → [job list](https://github.com/landedjobs/ai-engineer-jobs)

### 🤝 Forward-Deployed Engineer (FDE)
Customer-embedded builder — part engineer, part consultant, shipping custom solutions on the company's platform.
- **Skills:** Python, integrations, solutions design, customer-facing communication, data.
- **Comp:** base **$175K–$260K**, OTE **$230K–$360K**; median TC mid-level ~**$385K**, staff ~**$610K**, principal **$1.2M+** at frontier labs.
- **Hiring:** Palantir, OpenAI, Anthropic, applied-AI startups. → [job list](https://github.com/landedjobs/forward-deployed-engineer-jobs)

### 🚀 GTM Engineer
Automates go-to-market with code + AI — outbound, enrichment, lead scoring, revenue workflows. The technical evolution of the marketer/SDR.
- **Skills:** Clay + enrichment, APIs/webhooks, SQL, LLM-personalized outbound, CRM data.
- **Comp:** base **$180K–$240K**, OTE **$230K–$310K** (25–30% variable); broader range **$132K–$241K**.
- **Hiring:** Clay, Vapi, fast-growing B2B SaaS. → [job list](https://github.com/landedjobs/gtm-engineer-jobs)

### 🔎 RAG Engineer
Connects LLMs to trusted data so answers are accurate and grounded — retrieval pipelines, embeddings, re-ranking, evals. ~10–20% premium over general AI engineering.
- **Skills:** vector DBs (Pinecone/Weaviate/pgvector/Chroma), chunking, hybrid search + BM25, re-ranking, retrieval evals (recall@k, MRR, nDCG), caching/cost, MLOps.
- **Comp:** US entry **$120K–$160K**, mid **$160K–$220K**, senior **$200K–$280K+**. India mid **₹4–20L**, senior **₹20–58L+**.
- **Hiring:** every company with an AI feature that must be *right*. → [interview prep](https://github.com/landedjobs/rag-engineer-interview-questions)

### 🧩 AI Product Engineer
The new "PM who ships" — owns product *and* builds the AI features. Prompts, evals, and prototyping matter as much as roadmaps.
- **Skills:** product sense, prompting, evals, rapid prototyping, React/Next.js, APIs.
- **Comp:** roughly **$150K–$300K** US depending on the AI-eng/PM blend.
- **Hiring:** product-led startups (Linear, Vercel, Cursor). → [job list](https://github.com/landedjobs/ai-product-engineer-jobs) · [roadmap](https://github.com/landedjobs/ai-product-engineer-roadmap)

---

## The full family

> Every open-source repo we maintain — live job lists, opportunities, interview prep, roadmaps, and tools. **[Get fresh AI-native roles matched to you daily on Landed →](https://landed.jobs)**

<!-- FAMILY:START (generated by _shared/gen_index.py — do not edit by hand) -->

### 🔴 Live job lists — auto-updated from our job corpus

- 🤖 [AI Engineer](https://github.com/landedjobs/ai-engineer-jobs) — build products on top of LLMs — RAG, agents, evals, inference
- 🧠 [LLM Engineer](https://github.com/landedjobs/llm-engineer-jobs) — fine-tuning, inference, and LLM product engineering
- 🕹️ [AI Agent Engineer](https://github.com/landedjobs/ai-agent-engineer-jobs) — planning, tool-use, orchestration, guardrails
- 🧩 [AI Product Engineer](https://github.com/landedjobs/ai-product-engineer-jobs) — the PM who ships — owns product and builds AI features
- 🤝 [Forward-Deployed Engineer](https://github.com/landedjobs/forward-deployed-engineer-jobs) — customer-embedded builder; part engineer, part consultant
- 🛠️ [Solutions Engineer / Architect](https://github.com/landedjobs/solutions-engineer-and-architect-jobs) — technical pre-sales, integrations, deployment
- 🚀 [GTM Engineer](https://github.com/landedjobs/gtm-engineer-jobs) — automate go-to-market with code + AI
- 🔬 [Applied Scientist / Research Eng](https://github.com/landedjobs/applied-scientist-and-research-engineer-jobs) — applied research, training, evaluation
- 🛢️ [Data Engineer](https://github.com/landedjobs/data-engineer-jobs) — pipelines and platforms that power AI
- 📊 [Data Scientist](https://github.com/landedjobs/data-scientist-jobs) — analytics, experimentation, ML at AI-native companies
- 🦾 [AI Robotics & Embedded](https://github.com/landedjobs/ai-robotics-and-embedded-jobs) — perception, control, embedded ML
- 💼 [Freelance & Advisory AI](https://github.com/landedjobs/ai-freelance-and-advisory-jobs) — fractional, contract, and advisory AI work

### 🎯 More ways in — opportunities beyond the job boards

- 🔥 [Who's Hiring in AI](https://github.com/landedjobs/whos-hiring-in-ai) — real hiring posts from founders on X, sorted by role
- 💸 [Recently-Funded AI Startups](https://github.com/landedjobs/recently-funded-ai-startups-hiring) — fresh-capital startups staffing up now
- 🎓 [AI Fellowships & Residencies](https://github.com/landedjobs/ai-fellowships-and-residencies) — 75 fellowships, residencies & programs with stipends and deadlines

### 🧠 Interview prep

- 📘 [AI Interview Guides](https://github.com/landedjobs/ai-interview-guides) — 33 company-by-company guides: process, questions, comp
- ❓ [AI Interview Questions](https://github.com/landedjobs/ai-interview-questions) — 331 real questions with sources and ideal answers
- 🧠 [Awesome AI Engineer Interview](https://github.com/landedjobs/awesome-ai-engineer-interview) — questions, worked system designs, company guides
- 🔎 [RAG Engineer Interview Questions](https://github.com/landedjobs/rag-engineer-interview-questions) — the definitive RAG/retrieval question bank
- 📦 [AI PM Interview Prep](https://github.com/landedjobs/ai-pm-interview-prep) — product sense, AI fluency, frameworks, real questions

### 🏗️ Build & learn

- 🧪 [Projects to Land an AI Job](https://github.com/landedjobs/projects-to-land-an-ai-job) — deep, buildable briefs with evals and a deploy path
- 📦 [AI Engineer Portfolio Projects](https://github.com/landedjobs/ai-engineer-portfolio-projects) — 80+ buildable projects by theme
- 🗺️ [AI Product Engineer Roadmap](https://github.com/landedjobs/ai-product-engineer-roadmap) — skills, tools, milestones for the role
- 🎯 [Become a GTM Engineer](https://github.com/landedjobs/become-a-gtm-engineer) — the technical go-to-market roadmap

### 🧰 Tools

- 🧰 [Landed MCP Server](https://github.com/landedjobs/landed-mcp) — search jobs, prep applications, study — from any MCP client

<!-- FAMILY:END -->

---

## The data

- **AI Engineer** was a **#1 fastest-growing** US job title; postings up **~143% YoY**.
- AI/ML job postings rose **~163%** from 2024 → 2025.
- Roles requiring AI skills carry a **~56% wage premium** (up from ~25% a year earlier).
- Forward-Deployed comp can swing **4–5×** across frontier labs vs enterprise AI teams.

> Skills that show up most across these roles: **Python · LLM APIs · RAG · agents/tool-use · evals · vector DBs · prompting · rapid prototyping**. Bonus: TypeScript/Next.js, cloud, observability.

---

## FAQ

**Do I need an ML PhD to get an AI-native job?**
No. Most AI Engineer / AI Product Engineer roles want people who can **ship** with LLMs and APIs (RAG, agents, evals) — not researchers. Demonstrated projects beat credentials.

**What's the fastest way to stand out?**
Build 2–3 real projects (see [projects](https://github.com/landedjobs/projects-to-land-an-ai-job)) and get **referred** instead of applying cold — referrals convert far better than the application pile.

**Are these roles remote / available in India?**
Yes — the job lists include US, remote, and India-based roles, with India comp noted above.

---

## Contributing

PRs and issues welcome — add roles, questions, projects, or resources. See [CONTRIBUTING.md](CONTRIBUTING.md). This is a community map of a fast-moving market; help keep it current.

---

<div align="center">

### Stop spraying. Get **matched**, get **prepped**, get **Landed**.

[![Get Started](https://img.shields.io/badge/Get%20Started%20Free-→-6C2BD9?style=for-the-badge)](https://landed.jobs)

<sub>Maintained by [Landed](https://landed.jobs) · Comp figures aggregated from public 2026 salary reports; ranges are approximate.</sub>

</div>
