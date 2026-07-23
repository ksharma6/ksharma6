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

- Built and operate an open-source LangGraph agent that grounds replies in a user's email history while gating every send through human review
- Architecting an evaluation harness with outcome-based metrics, LLM-as-judge comparison, and regression gating
- Diagnosed prompt growth from 739 to 56K tokens as thread depth increased from 5 to 40, overturning an initial linear-growth hypothesis
- Building a labeled benchmark and evaluating recall-first triage approaches across heuristic, zero-shot, and fine-tuned baselines

### Generative AI Evaluation Consultant
*February 2024 – November 2024*

- **OpenAI (ChatGPT):** Evaluated reasoning, tool usage, and prompt adherence across multi-turn conversations; wrote Python tests to verify generated code compiled and matched user intent
- **Google (Gemini):** Assessed tool-calling decisions and reasoning traces for Maps, Search, Calendar, and Purchasing; validated production schemas through code verification
- **Meta (Llama):** Produced RLHF preference data for machine-learning tasks by scoring output quality and regenerating responses at the point of failure

### Open-source Developer · [sktime](https://www.sktime.net)
*March 2024 – October 2024*

- Decoupled GridSearch from scikit-learn, reducing user-reported issues by 20% and improving reproducibility
- Shipped an AutoML `MultiplexerRegressor` that reduced model-selection time by 30%

### Data Scientist · Acorn Analytics
*August 2020 – March 2021*

- Developed lightweight Python and MySQL data pipelines on AWS for encryption and feature extraction
- Ran 10K Monte Carlo trials for headcount planning and delivered analysis that generated $140K in new business opportunities

### Staff Consultant · Celerity Consulting Group
*March 2016 – May 2018*

- Directed a team of five analysts, reduced burn rate by 18%, and built Tableau reporting on MySQL and SharePoint ETL pipelines
- Implemented a logistic-regression fraud-detection model that produced $250K in cost savings for a Fortune 500 client

---

## 🎓 Education

**Stanford University**  
*Graduate coursework, January 2022 – January 2024*

CS224N (Natural Language Processing) · CS336 (Language Modeling from Scratch) · CS236 (Deep Generative Models) · CS229 (Machine Learning) · CS231N (Computer Vision)

**University of California, San Diego**  
*B.A. Cognitive Science, 2015*

---

## 🚧 Current focus

- Shipping Inbox0 v1.0 with an evaluation harness, tiered retrieval, and a triage classifier—each measured against a documented baseline
- Exploring lightweight models that reduce cost and latency in agent pipelines
- Building practical evaluation frameworks for agent behavior and tool use

---

## 🛠 Technology

`Python` `LangGraph` `Pydantic` `PyTorch` `scikit-learn` `Hugging Face` `OpenAI APIs` `RAG` `RLHF` `Flask` `REST APIs` `Redis` `SQLite-vec` `AWS` `GCP` `SQL` `CI/CD` `Linux`

---

## 🤝 Open to opportunities

I'm interested in ML and AI engineering roles focused on agent systems, LLM applications, evaluation, and reliability.

📫 [ksharma06@pm.me](mailto:ksharma06@pm.me) · [LinkedIn](https://linkedin.com/in/kishen-sharma/) · [GitHub](https://github.com/ksharma6)
