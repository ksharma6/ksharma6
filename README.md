# Hi, I'm Kishen — ML Engineer
**Applied AI · Agent Systems · LLM Reliability**

I build production-ready AI systems that combine LLM reasoning, structured tool-calling, and human-in-the-loop workflows. Based in Daly City, CA.

---

## 🔥 Featured Project

### [Inbox0](https://github.com/ksharma6/Inbox0)
AI email agent that triages, summarizes, and drafts replies using LangGraph.

- LangGraph agents with structured tool-calling (Pydantic schemas) and deterministic execution
- Tiered RAG retrieval: **Redis** (hot storage for active threads) + **SQLite** (cold storage for archived context)
- Stateful workflows with checkpointing, retry logic, and execution logging
- Gmail + Slack Bolt integrations with interactive modals
- Human-in-the-loop approval system
- Productionized as a Flask service with modular routes and environment-scoped secrets

---

## 🧩 How I think about AI systems

- Treat LLMs as **unreliable components** → enforce structure, validation, and fallback paths
- Prefer **deterministic execution layers** (schemas, tool constraints) over prompt-only control
- Design for **observability**: logging, replayability, execution tracing, and failure inspection
- Optimize for iteration speed via **eval loops** and real-user feedback

---

## 💼 Experience

**ML Engineer (Applied AI) · Inbox0** *(May 2025 – Present)*
- Architected production LangGraph agents with schema-validated tool-calling and HITL approval
- Built tiered RAG system reducing context-lookup latency while keeping full email history queryable
- Implemented evaluation infrastructure: execution logging, retry logic, and state checkpointing

**Open-source Developer · [sktime](https://www.sktime.net)** *(Mar – Oct 2024)*
- Decoupled GridSearch from scikit-learn, reducing user-reported issues by 20%
- Shipped `MultiplexerRegressor` AutoML component — cuts model-selection time by 30%

**AI Training Engineer (RLHF) · Self-Employed** *(Feb – Nov 2024)*
- **OpenAI (ChatGPT)** — evaluated reasoning, tool use, and prompt adherence across multi-turn conversations; wrote Python tests to verify generated code matched user intent
- **Google (Gemini)** — rewrote chain-of-thought traces to compress agentic turn counts; validated tool-calling schemas for Maps, Search, Calendar, and Purchasing
- **Meta (Llama)** — scored output quality, penalized hallucinations, and re-evaluated downstream responses after failure-point regeneration

**Data Scientist · Acorn Analytics** *(Aug 2020 – Mar 2021)*
- Built Python/MySQL AWS ETL pipelines; ran 10K Monte Carlo simulations for headcount planning
- Collaborated on a logistic regression fraud-detection model → $250K cost savings

**Staff Consultant · Celerity Consulting Group** *(Mar 2016 – May 2018)*
- Led team of 5 analysts; built Tableau dashboards via MySQL on SharePoint ETL pipelines

---

## 🎓 Education

**Stanford University** *(2022 – 2024)*
CS229 (Machine Learning) · CS224N (NLP) · CS231N (Computer Vision) · CS336 (LLMs) · CS236 (GANs)

**UC San Diego** *(B.A. Cognitive Science, 2015)*

---

## 🚧 Current focus

- Building more reliable agent workflows — retry strategies and state recovery
- Exploring lightweight models to reduce cost in agent pipelines
- Improving evaluation frameworks for agent behavior

---

## 🛠 Tech

`Python` `LangGraph` `Pydantic AI` `PyTorch` `OpenAI APIs` `RAG` `RLHF` `Flask` `AWS` `GCP` `SQL` `Redis` `Linux`

---

## 🤝 Open to opportunities

ML / AI engineering roles focused on agent systems, LLM applications, and evaluation.

📫 [ksharma06@pm.me](mailto:ksharma06@pm.me) · [LinkedIn](https://linkedin.com/in/kishen-sharma/)
