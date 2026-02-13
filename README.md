# 🧠 AI Engineering Portfolio

> **Senior Software Engineer → AI Engineer** | 17 years of production software experience, now building intelligent systems.

I'm pivoting from software engineering to AI engineering, combining deep production expertise with modern AI/ML skills. This portfolio showcases real-world AI projects built with production-grade engineering practices.

---

## 🚀 Projects

### 1. 📄 Intelligent Document Q&A — RAG System
**Status:** 🔲 Not Started &nbsp;|&nbsp; **Timeline:** Week 5–7

Build a production-ready Retrieval-Augmented Generation pipeline over custom documents.

**What it does:**
- Ingests PDFs/documents and chunks them using multiple strategies (recursive, semantic)
- Generates embeddings and stores them in a vector database
- Retrieves relevant context and generates accurate answers via LLM
- Exposes a clean REST API + simple chat UI

**Tech Stack:**
`Python` · `FastAPI` · `LangChain` · `OpenAI API` · `pgvector` · `Docker` · `Streamlit`

**Key Engineering Decisions:**
- *Why pgvector over Pinecone?* → (will document after building)
- *Chunking strategy tradeoffs* → (will document after building)
- *Evaluation approach* → (will document after building)

**Links:** [Code]() · [Blog Post]() · [Live Demo]()

---

### 2. 🤖 Autonomous AI Agent with Tool Use
**Status:** 🔲 Not Started &nbsp;|&nbsp; **Timeline:** Week 7–9

Build an AI agent that reasons, uses tools, maintains memory, and handles multi-step tasks.

**What it does:**
- Receives a user goal and breaks it into sub-tasks autonomously
- Calls external tools (web search, APIs, calculator, code execution)
- Maintains conversation memory across sessions
- Includes guardrails, error recovery, and fallback strategies

**Tech Stack:**
`Python` · `LangGraph / CrewAI` · `OpenAI / Anthropic API` · `Redis` · `FastAPI` · `Docker`

**Key Engineering Decisions:**
- *Agent framework choice and why* → (will document after building)
- *Memory architecture* → (will document after building)
- *Guardrail implementation* → (will document after building)

**Links:** [Code]() · [Blog Post]() · [Live Demo]()

---

### 3. 🔧 Fine-Tuned LLM with Production Deployment
**Status:** 🔲 Not Started &nbsp;|&nbsp; **Timeline:** Week 9–11

Fine-tune an open-source LLM on domain-specific data and deploy it with full production infrastructure.

**What it does:**
- Fine-tunes Llama/Mistral on a curated domain-specific dataset
- Deploys the model with proper serving infrastructure
- Includes monitoring dashboard (latency, cost, quality metrics)
- Full CI/CD pipeline for model updates

**Tech Stack:**
`Python` · `Hugging Face Transformers` · `LoRA / QLoRA` · `vLLM` · `Docker` · `GitHub Actions` · `Weights & Biases`

**Key Engineering Decisions:**
- *Why LoRA over full fine-tuning?* → (will document after building)
- *Dataset curation process* → (will document after building)
- *Monitoring and observability approach* → (will document after building)

**Links:** [Code]() · [Blog Post]()

---

### 4. 📊 LLM Evaluation Framework
**Status:** 🔲 Not Started &nbsp;|&nbsp; **Timeline:** Week 8–10

Build a systematic evaluation pipeline for comparing models, prompts, and configurations.

**What it does:**
- Automated evaluation using multiple metrics (LLM-as-judge, BLEU, ROUGE, custom)
- Human evaluation workflows with annotation interface
- Regression testing for prompt changes
- A/B comparison dashboards for models and prompts

**Tech Stack:**
`Python` · `Ragas` · `DeepEval` · `Streamlit` · `SQLite` · `Pandas`

**Links:** [Code]() · [Blog Post]()

---

### 5. 🎙️ Multi-Modal AI Application *(Stretch Goal)*
**Status:** 🔲 Not Started &nbsp;|&nbsp; **Timeline:** Week 10–12

Combine text + audio/image processing into a single intelligent application.

**What it does:**
- Meeting summariser: ingests audio → transcribes → extracts action items via LLM
- OR: Document understanding pipeline that processes images + text together
- Clean API with proper error handling and monitoring

**Tech Stack:**
`Python` · `Whisper` · `GPT-4 Vision / Claude` · `FastAPI` · `Docker`

**Links:** [Code]() · [Blog Post]()

---

## 📚 Learning Journey

I'm documenting my transition from software engineering to AI engineering. Here's what I'm studying and building week by week.

| Week | Focus | Status |
|------|-------|--------|
| Week 1–2 | Foundations: Neural networks, transformers, attention (Karpathy, 3Blue1Brown) | 🟡 In Progress |
| Week 3–4 | LLM application basics: RAG, agents, prompt engineering (DeepLearning.AI, Hugging Face) | 🔲 Not Started |
| Week 5–6 | Building LLM apps: LangChain, vector DBs, Full Stack LLM Bootcamp | 🔲 Not Started |
| Week 7–8 | Production & MLOps: Made With ML, deployment patterns | 🔲 Not Started |
| Week 9–10 | Fine-tuning & evaluation: LoRA, RLHF, quantization | 🔲 Not Started |
| Week 11–12 | Portfolio polish & interview preparation | 🔲 Not Started |

### 📖 Books I'm Reading
- [ ] Build a Large Language Model from Scratch — Sebastian Raschka
- [ ] The Hundred-Page Machine Learning Book — Andriy Burkov
- [ ] AI Engineering — Chip Huyen
- [ ] Designing Machine Learning Systems — Chip Huyen
- [ ] LLM Engineer's Handbook — Paul Iusztin & Maxime Labonne
- [ ] Prompt Engineering for LLMs — Berryman & Ziegler

---

## 🛠️ Technical Skills

**AI/ML:** LLMs · RAG · AI Agents · Fine-Tuning (LoRA/QLoRA) · Prompt Engineering · Embeddings · Vector Databases · LLM Evaluation

**Frameworks & Tools:** LangChain · LlamaIndex · Hugging Face Transformers · OpenAI API · Anthropic API · vLLM · Weights & Biases

**Infrastructure:** Docker · Kubernetes · CI/CD · FastAPI · PostgreSQL · Redis · GitHub Actions

**Software Engineering (17 years):** System Design · Microservices · API Design · Testing · Monitoring · Observability · Agile/Scrum

---

## ✍️ Blog Posts & Writing

I write about what I learn as I build. Technical deep-dives, architecture decisions, and lessons from the pivot.

- [ ] *"What I Learned Building a GPT from Scratch"* — (Week 2)
- [ ] *"Designing a RAG System: Architecture Decisions & Tradeoffs"* — (Week 6)
- [ ] *"Building an AI Agent That Actually Works in Production"* — (Week 9)
- [ ] *"Fine-Tuning vs RAG vs Prompting: When to Use What"* — (Week 10)

---

## 🧭 About This Portfolio

This isn't a collection of tutorial follow-alongs. Every project here is designed to demonstrate production-grade AI engineering:

- **Clean, tested code** — not notebooks
- **Architecture decision records** — documenting the "why" behind every choice
- **Deployment-ready** — Docker, CI/CD, monitoring
- **Evaluated** — every system includes proper evaluation methodology
- **Written up** — blog posts explaining design tradeoffs

I believe the best AI engineers are great software engineers first. This portfolio reflects that philosophy.

---

## 📬 Connect

- **LinkedIn:** [Your LinkedIn URL]
- **Blog:** [Your Blog URL]
- **Email:** [your.email@example.com]

---

*This portfolio is actively being built as part of a 12-week AI engineering pivot. Last updated: February 2026*
