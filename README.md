# Hi, I'm Kishen — Applied AI Engineer <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px" alt="wave">

**Agent Systems · LLM Evaluation · Reliable AI**

I build production-ready AI systems that combine LLM reasoning, structured tool-calling, and human-in-the-loop workflows—with evaluation built in from the start. Based in Daly City, California.

---

## 🔥 Featured project

### [Inbox0](https://github.com/ksharma6/Inbox0)

An open-source AI email agent that triages inbound threads, drafts replies in the user's voice, and routes every send through human review. Each change must beat a measured baseline before it ships.

- Built and operate a LangGraph agent with schema-validated tool-calling, state checkpointing, retry logic, and deterministic replay
- Architecting an evaluation harness around three implementation-independent metrics: send rate, latency, and cost per draft
- Using LLM-as-judge pairwise comparisons and regression gates to prevent changes that fail to beat baseline
- Building a labeled benchmark from sanitized inbox data, synthetic edge cases, Enron examples, and production failures
- Designing tiered semantic retrieval with a Redis working-set cache and SQLite-vec persistent store after diagnosing exponential prompt-token growth on deep email threads
- Evaluating heuristic, zero-shot, and fine-tuned DistilBERT baselines for a recall-first triage classifier
- Integrating Gmail and Slack Bolt with human-in-the-loop approval on every send

---

## 🧩 How I build AI systems

- Treat LLMs as **unreliable components** and enforce structure, validation, and fallback paths
- Prefer **schema-constrained tools and deterministic execution** over prompt-only control
- Design for **observability** through logging, replayability, tracing, and failure inspection
- Fold production failures back into labeled evaluation cases
- Measure before building: a feature ships when it **beats a baseline**, not when it merely feels complete

---

## 💼 Experience

### Applied AI Engineer · [Inbox0](https://github.com/ksharma6/Inbox0)
*May 2025 – Present*

- Built and operate an open-source LangGraph agent that triages Gmail and drafts replies using schema-validated tool calls, checkpointed state, and retriable execution; every outbound message requires human approval.
- Architected a pipeline evaluation harness: defined three model-agnostic metrics tied to user outcomes, implementing LLM-as-judge pairwise model comparisons, and automated regression gates that block releases performing below baseline.
- Built and maintain a versioned benchmark from sanitized inbox data, synthetic edge cases, the Enron email corpus, and production failures; used it to compare heuristic, zero-shot, and fine-tuned triage models and deploy recall-first routing that avoids unnecessary LLM inference.
- Designing an adaptive hybrid retrieval system to ground generated drafts in relevant context from a user’s email history; a schema-validated planner routes queries across lexical, vector, and metadata search, with rank fusion, reranking, evidence-coverage checks, and bounded query expansion

### Generative AI Evaluation Consultant
*February 2024 – November 2024*

Evaluated frontier generative AI models from OpenAI, Google, and Meta, focusing on reasoning, tool use, code generation, and instruction following. Diagnosed failure modes and produced correction and preference signals to improve model behavior.

- OpenAI (ChatGPT): designed evaluation criteria for multi-turn reasoning, tool usage, and prompt adherence; wrote Python unit tests to verify generated code compiled and matched intent; diagnosed and corrected failure modes where responses diverged from prior context.
- Google (Gemini): authored chain-of-thought rewrites to compress agentic turn counts, evaluated tool-calling decisions against production schemas (Maps, Search, Calendar, Purchasing), and produced trace-level correction signal feeding preference data.
- Meta (Llama): scored output quality on computer-science tasks, penalizing hallucinations and factual errors; generated preference data at the point of failure, modeling the annotator judgment that downstream reward models learn from.

### Open-source Developer · [sktime](https://www.sktime.net)
*March 2024 – October 2024*

- Contributed to a 1M+ user/month open-source ML framework: decoupled GridSearch from scikit-learn, reducing user-reported issues by 20% and improving reproducibility across regression and classification workflows.
- Shipped an AutoML MultiplexerRegressor that auto-selects among state-of-the-art time-series regressors with GridSearch hyperparameter tuning, cutting model-selection time by 30% and simplifying downstream integration.

### Data Scientist · Acorn Analytics
*August 2020 – March 2021*

- Built lightweight data pipelines on AWS (Python, MySQL) for data encryption and feature extraction; delivered analysis to C-suite that generated $140K in new business opportunities.
- Ran 10K Monte Carlo trials in a Markov chain framework to generate hiring ranges and risk bands, briefed B2B SaaS executives and standardized a repeatable template later reused for Q1 and Q2 headcount planning.

### Staff Consultant · Celerity Consulting Group
*March 2016 – May 2018*

- Directed a team of five analysts, reducing burn rate 18%; built weekly Tableau reporting via MySQL queries on SharePoint-hosted data (ETL, data modeling, scheduled refresh).
- Implemented a logistic regression fraud-detection model resulting in $250K cost savings for Fortune 500 client; engineered domain-informed features that increased model lift and recall.

---

## 🎓 Education

**Stanford University**  
*Non-Degree | Audited Graduate Coursework - January 2022 – January 2024*

- CS229 – Machine Learning
- CS224N – NLP with Deep Learning
- CS231N – Computer Vision
- CS336 – Language Modeling from Scratch
- CS236 – Deep Generative Models

**University of California, San Diego**  
*B.A. Cognitive Science, 2015*

---

## 🛠 Technology & Focus

- **LLM Evaluation (Evals):** LLM-as-judge, pairwise comparisons, evaluation datasets, failure analysis, regression testing
- **Agentic Workflows & Agent Orchestration:** LangGraph, structured tool calling, Pydantic, human-in-the-loop approval, state management, retries
- **Retrieval-Augmented Generation (RAG):** hybrid search, semantic retrieval, metadata filtering, rank fusion, reranking, Redis, sqlite-vec

**Languages & ML:** Python · SQL · PyTorch · scikit-learn · Hugging Face  
**APIs & Infrastructure:** OpenAI API · REST APIs · Flask · AWS · GCP · CI/CD · Linux
---

## 🤝 Open to opportunities

I'm interested in ML and AI engineering roles focused on agent systems, LLM applications, evaluation, and reliability.

📫 [ksharma06@pm.me](mailto:ksharma06@pm.me) · [LinkedIn](https://linkedin.com/in/kishen-sharma/) · [GitHub](https://github.com/ksharma6)
