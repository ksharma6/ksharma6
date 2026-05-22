# Hi, I'm Kishen — ML Engineer  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px" alt="wave">

**Applied AI · Agent Systems · LLM Reliability**

I build production-ready AI systems that combine LLM reasoning, structured tool-calling, and human-in-the-loop workflows, with evaluation built in from the start. Based in Daly City, CA.

---

## 🔥 Featured Project

### [Inbox0](https://github.com/ksharma6/Inbox0)
An open-source AI email agent that triages inbound threads, drafts replies in the user's voice, and routes every send through human review, built on the principle that each component must beat a measured baseline before it ships.

- LangGraph agents with structured tool-calling (Pydantic-validated schemas), state checkpointing, retry logic, and deterministic, replayable execution
- Pipeline evaluation harness anchored on three implementation-independent gold metrics (send rate, latency, cost per draft) that score user outcomes, not component internals
- LLM-as-judge pairwise comparison that gates regressions before they ship, fed by implicit signal from Slack actions and Gmail folder state
- Golden dataset for system baselining, with production failure modes folded back in as labeled cases
- Designing tiered semantic retrieval (Redis hot cache + SQLite-vec cold store) in response to diagnosed exponential token growth on deep quoted-reply threads
- Gmail + Slack Bolt integrations with human-in-the-loop approval on every send
- Productionized as a Flask service with modular routes and environment-scoped secrets

---

## 🧩 How I think about AI systems

- Treat LLMs as **unreliable components** → enforce structure, validation, and fallback paths
- Prefer **deterministic execution layers** (schemas, tool constraints) over prompt-only control
- Design for **observability**: logging, replayability, execution tracing, and failure inspection
- Measure before building: a feature ships when it **beats a baseline**, not when it feels done

---

## 💼 Experience

**ML Engineer (Applied AI) · Inbox0** *(May 2025 – Present)*
- Built and operate a production LangGraph agent with schema-validated tool-calling, state checkpointing, retry logic, and human-in-the-loop approval on every send
- Architected an evaluation harness on three implementation-independent gold metrics that score user outcomes, with LLM-as-judge pairwise comparison and regression gating
- Diagnosed exponential prompt-token growth with thread depth (739 to 56K tokens from depth 5 to 40); designing tiered semantic retrieval in response
- Curating a golden dataset (sanitized inbox, synthetic edge cases, extending to the Enron corpus) to prove each feature delivers measurable end-to-end improvement

**Open-source Developer · [sktime](https://www.sktime.net)** *(Mar – Oct 2024)*
- Decoupled GridSearch from scikit-learn, reducing user-reported issues by 20%
- Shipped a `MultiplexerRegressor` AutoML component that cuts model-selection time by 30%

**AI Training Engineer (RLHF) · Self-Employed** *(Feb – Nov 2024)*
- **OpenAI (ChatGPT)** — evaluated reasoning, tool use, and prompt adherence across multi-turn conversations; wrote Python tests to verify generated code matched user intent
- **Google (Gemini)** — rewrote chain-of-thought traces to compress agentic turn counts; validated tool-calling schemas for Maps, Search, Calendar, and Purchasing
- **Meta (Llama)** — scored output quality on computer science tasks, penalized hallucinations and factual errors, and produced preference data from failure-point regeneration

**Data Scientist · Acorn Analytics** *(Aug 2020 – Mar 2021)*
- Developed lightweight Python/MySQL data pipelines on AWS; ran 10K Monte Carlo simulations for headcount planning
- Collaborated on a logistic regression fraud-detection model → $250K cost savings

**Staff Consultant · Celerity Consulting Group** *(Mar 2016 – May 2018)*
- Led a team of 5 analysts; built Tableau dashboards via MySQL on SharePoint ETL pipelines

---

## 🎓 Education

**Stanford University** *(2022 – 2024)*
CS229 (Machine Learning) · CS224N (NLP) · CS231N (Computer Vision) · CS336 (Language Modeling from Scratch) · CS236 (Deep Generative Models)

**UC San Diego** *(B.A. Cognitive Science, 2015)*

---

## 🚧 Current focus

- Shipping Inbox0 v1.0: evaluation harness, tiered retrieval, and a triage classifier, each measured against a documented baseline
- Exploring lightweight models to cut cost in agent pipelines
- Sharpening evaluation frameworks for agent behavior

---

## 🛠 Tech

`Python` `LangGraph` `Pydantic` `PyTorch` `OpenAI APIs` `RAG` `RLHF` `Flask` `AWS` `GCP` `SQL` `Redis` `SQLite-vec` `Linux`

---

## 🤝 Open to opportunities

ML / AI engineering roles focused on agent systems, LLM applications, and evaluation.

📫 [ksharma06@pm.me](mailto:ksharma06@pm.me) · [LinkedIn](https://linkedin.com/in/kishen-sharma/)
