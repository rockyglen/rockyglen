<div align="center">

# Marian Glen Louis
### AI Engineer · MLOps · Agentic Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marian-glen-louis)
[![Portfolio](https://img.shields.io/badge/Portfolio-View_My_Work-black?style=for-the-badge&logo=vercel&logoColor=white)](https://glen-louis.vercel.app)
[![Email](https://img.shields.io/badge/Email-Hire_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:glen.louis08@gmail.com)


### 🟢 Open to Work — AI Engineer · MLOps Engineer · Data Scientist

</div>

---

## Who I Am

I'm an **AI Engineer** who builds things that work in production — not just demos.

I specialize in **autonomous agentic AI systems**: multi-agent workflows, self-correcting RAG pipelines, and LLM-powered automation using **LangGraph** and **Model Context Protocol (MCP)**. This is a rare and fast-growing specialization — most engineers know how to call an LLM API; I know how to architect systems where multiple AI agents plan, collaborate, self-correct, and recover from failure.

My background in **Data Reliability Engineering at Wipro** (2 years, Bengaluru) means I think about AI differently than most: I've seen data pipelines fail at scale, and I build AI systems that don't. I recently completed my **M.S. in Data Science at the University at Buffalo** (Dec 2025) and I'm ready to bring this combination of production discipline and cutting-edge AI engineering to a team.

---

## What I Bring to a Team

| Capability | Evidence |
|---|---|
| 🤖 Agentic AI Systems | Built multi-agent orchestrators with LangGraph + MCP deployed against live AWS infra |
| 📊 Production MLOps | End-to-end automated pipelines: ingestion → training → deployment → monitoring |
| 🔍 RAG & LLM Engineering | 1.00 Faithfulness score on compliance RAG system evaluated with RAGAS |
| ☁️ Cloud & Infrastructure | AWS (IAM, S3, EC2, VPC), Docker, Terraform, GitHub Actions CI/CD |
| 📉 Measurable Impact | 85% dashboard latency reduction; 5.1 MAE maintained across automated retraining cycles |
| 🧠 Rare Skill Set | LangGraph · MCP · CRAG · Agentic RAG — expertise most teams are still building toward |

---

## 🔑 Core Skills

**Agentic AI:** LangGraph · LangChain · Model Context Protocol (MCP) · Agentic RAG · CRAG · Ragas · Groq · Anthropic API · OpenAI API  
**MLOps & Cloud:** AWS (S3, EC2, IAM, VPC) · Docker · GitHub Actions · MLflow · Terraform · Prefect · Hopsworks · Evidently AI  
**Data & Backend:** Snowflake · Qdrant Cloud · Supabase · FastAPI · Streamlit · SQL · Python · PyArrow · Pandera  
**ML & Vision:** PyTorch · LightGBM · YOLOv8 · OpenCV · Scikit-learn · Hugging Face · QLoRA  
**Frontend:** Next.js · TailwindCSS  

---

## 🚀 Projects — What I've Actually Built

> Each project below is production-grade, end-to-end, and on GitHub.

---

### 🔐 [Aegis-Flow — Multi-Agent Cloud Security Orchestrator](https://github.com/glenlouis8/ageis-flow)
**LangGraph · MCP · AWS IAM/S3/EC2/VPC · Google Gemini · Human-in-the-Loop**

An autonomous AI system that audits AWS infrastructure for security risks, proposes remediations, requests human approval, executes fixes, and verifies success — all without manual intervention.

- Engineered a multi-agent LLM pipeline (LangGraph + Claude Sonnet) that autonomously detects and remediates AWS security misconfigurations with a **100% remediation success rate** and post-fix verification pass rate across all completed scans
- Reduced Mean Time to Detect to **34s** and Mean Time to Remediate to **83s** by designing a stateful agent graph with parallel audit nodes, structured tool dispatch, and a recursion limit guard to prevent runaway inference loops
- Optimized LLM inference cost to **~$0.04 per full security scan** (27K tokens) by engineering targeted system prompts, filtering tool arguments against live MCP schema to eliminate hallucinated parameters, and adding explicit tool-to-action mappings
- Implemented a **human-in-the-loop safety gate** within the agent loop that intercepts the model's remediation plan pre-execution, surfaces structured approval context to operators, and resumes the agent via stdin signal — achieving 100% operator-reviewed fix rate with zero unauthorized automated changes

> *Why it matters to a hiring team: This isn't a chatbot. It's a working autonomous agent operating on real infrastructure with safety controls. This is the kind of system that replaces expensive manual security audits.*

---

### 📋 [AuditAI — Agentic RAG Compliance Engine](https://github.com/glenlouis8/audit-ai)
**LangGraph · CRAG · Qdrant · Llama-3.3 70B · FastAPI · Ragas**

A self-correcting AI system that audits company policies against the NIST Cybersecurity Framework — autonomously, with verified accuracy.

- Built a **Corrective RAG (CRAG)** agent using LangGraph with a self-healing 4-node pipeline that automatically rewrites failed queries up to 3x, achieving **100% Faithfulness** and **90% Context Recall** across 10 RAGAS-evaluated NIST compliance Q&A pairs
- Engineered a real-time token-streaming API with **FastAPI** (NDJSON/SSE) over a stateful LangGraph graph, filtering intermediate LLM grader tokens and implementing smart citation suppression — all metrics passing **≥0.7 threshold**
- Designed a **semantic query router** with conversation-history context (last 3 turns) that classifies intent before graph invocation, reducing unnecessary agentic calls for non-compliance queries while maintaining **76.4% Answer Relevancy**
- Delivered a full RAG evaluation pipeline across **50 ground-truth NIST Q&A pairs**, scoring **78.4% Context Precision**, **76.4% Answer Relevancy**, **90% Context Recall**, and **100% Faithfulness** using Gemini 2.5 Flash as judge LLM

> *Why it matters to a hiring team: Compliance is a billion-dollar problem. This system automates what typically requires expensive consultants and manual review, with measurable, auditable accuracy.*

---

### 💰 [FinBuddy — AI-Powered Personal Finance Tracker](https://github.com/glenlouis8/finbuddy)
**Next.js · Supabase · OpenAI GPT-4o · OCR · pgvector**

A full-stack AI platform that turns physical receipts into semantically searchable financial records using GPT-4o Vision, vector embeddings, and natural language retrieval.

- Developed a multi-stage OCR pipeline using **GPT-4o Vision** to extract structured financial data (amount, category, line items) from receipts, then generated **1536-dimensional embeddings** via `text-embedding-3-small` to transform receipts into semantically searchable records
- Engineered semantic search by integrating **pgvector** within **Supabase PostgreSQL**, implementing a custom `match_expenses` PL/pgSQL function with cosine similarity, adjustable precision thresholds, and **ivfflat** indexing for fast natural language retrieval
- Built an asynchronous insights engine using **GPT-4** to analyze raw OCR text, autonomously identifying unusual spending patterns and generating category-level summaries delivered as structured JSON for immediate frontend consumption
- Implemented a **semantic cache layer** in PostgreSQL storing 1536-dimensional embeddings of LLM summaries, enabling cosine-similarity lookups to eliminate redundant API calls before triggering expensive re-generation

> *Why it matters to a hiring team: RAG applied to personal finance — embeddings, semantic search, and LLM reasoning over structured data, all in a production full-stack app.*

---

### 🏎️ [F1 Apex Guardian — Real-Time Telemetry Monitoring & Anomaly Detection](https://github.com/glenlouis8/f1_apex_guardian)
**GitHub Actions · AWS S3 · MLflow · DagsHub · Isolation Forest · Docker · Streamlit**

A cloud-native MLOps system that monitors live F1 telemetry across 22 concurrent streams, using automated drift detection and unsupervised anomaly detection to flag electrical and thermal failures in real time.

- Architected a cloud-native monitoring system for F1 telemetry, integrating **GitHub Actions** for CI/CD automation and **AWS S3** as a centralized Feature Store and Model Registry
- Engineered a weekly Challenger pipeline that automates data ingestion via **FastF1** API, executes **Kolmogorov-Smirnov** statistical drift detection, and promotes high-performing models to production using DagsHub/MLflow for full lineage tracking
- Developed and deployed an unsupervised **Isolation Forest** model to identify high-speed electrical derating and thermal anomalies, achieving real-time diagnostic classification across **22+** concurrent telemetry streams
- Launched a high-concurrency **Streamlit** dashboard on Hugging Face Spaces, optimized with custom Docker containers and multi-layer resource caching (`@st.cache_resource`) to reduce dashboard latency and S3 data-pull times by **85%**

> *Why it matters to a hiring team: This demonstrates the full MLOps loop — not just model training, but automated retraining, drift monitoring, and production deployment. This is what senior ML engineers are hired to build.*

---

### 🚲 [Citi Bike Demand Forecaster — Live 24-Hour Prediction & Automated MLOps Pipeline](https://github.com/glenlouis8/bike_Taxi)
**LightGBM · GitHub Actions · Evidently AI · MLflow · AWS S3 · Next.js 14**

A production-grade MLOps pipeline for live 24-hour Citi Bike demand forecasting using a recursive LightGBM engine, automated Champion/Challenger model promotion, and a full-stack Next.js visualization dashboard.

- Built a production MLOps system on **GitHub Actions** that automatically ingests NYC Citi Bike trip data, engineers **32 lag and temporal features**, trains a **LightGBM** forecasting model, and deploys hourly predictions — achieving **MAE of 5.1 rides/hour** and **24% WMAPE** across 1,051 held-out test samples with zero manual intervention
- Designed a champion/challenger promotion loop using **Hopsworks Model Registry** and **MLflow** on DagsHub, where a new challenger model is automatically promoted only if it strictly improves MAE over the incumbent — eliminating manual model approval
- Engineered a **Recursive Bridge algorithm** that walks hour-by-hour from the last known data point to present using 28 lag features (top feature: lag_1 at **25% importance**), bridging a ~20-day Citi Bike data publication lag to generate live 24-hour forecasts
- Deployed a **Next.js 14** dashboard on Vercel that reads live Parquet predictions directly from S3 using **hyparquet** — eliminating a dedicated API server entirely — displaying hourly demand forecasts across NYC stations with an interactive heatmap

> *Why it matters to a hiring team: Custom algorithm design + automated MLOps + live dashboard = a full product, not a notebook.*

---

### 🦙 [Llama-3.2-3B Alpaca QLoRA — Instruction Fine-Tuning Pipeline](https://github.com/glenlouis8/llama-3.2-3b-alpaca-qlora)
**QLoRA · LoRA (PEFT) · Llama-3.2 · BitsAndBytes · SFTTrainer · Hugging Face**

An end-to-end fine-tuning, evaluation, and deployment pipeline for Llama-3.2-3B-Instruct on 52K instruction examples — with rigorous before/after benchmarking.

- Fine-tuned Llama-3.2-3B-Instruct on 52K Alpaca instruction examples via **QLoRA** (4-bit NF4 + double quantization, LoRA r=16 α=32 across all 7 attention/MLP projections), reducing perplexity **81.3%** (25.84 → 4.82) and improving ROUGE-L **+36.3%** (0.259 → 0.353)
- Reduced GPU memory **~40%** by combining 4-bit NF4 double quantization, gradient checkpointing, and paged **AdamW-8bit** — fine-tuning only **20M of 3B parameters (0.67%)** on a single 24GB RTX 4090 in ~2.5 hours
- Implemented correct SFT loss masking by applying the model's native chat template via **apply_chat_template** and routing through SFTTrainer's `formatting_func`, ensuring causal LM loss is computed only over assistant tokens — a common pitfall in instruction tuning pipelines
- Built a deterministic evaluation pipeline (shared seed=42 split, perplexity via teacher-forcing + ROUGE-L via greedy decoding) with versioned JSON result artifacts and automated **HuggingFace Hub** deployment with real eval numbers injected into the model card

> *Why it matters to a hiring team: Most engineers fine-tune models without rigorous evaluation. This pipeline treats it like a production ML system — reproducible, measured, and deployed with honest benchmarks.*

---

## 💼 Experience

**Volunteer Research Assistant** · University at Buffalo — Visual Computing Lab · Buffalo, NY *(Mar 2026 – Present)*
- Conducting applied research on time series trend prediction and root-cause analysis for power industry datasets under **Dr. Junsong Yuan** (IEEE Fellow, Director — Visual Computing Lab, UB CSE), targeting submission to a reputable conference or journal
- Designing and benchmarking forecasting pipelines to model temporal patterns in power consumption data, evaluating statistical and ML baselines for predictive accuracy and interpretability
- Collaborating with PhD researcher Ziqing Zhang to structure the data analysis workflow, define evaluation criteria, and build reproducible experiment pipelines for academic publication

**Data Scientist Intern (Capstone)** · Nissha Medical Technologies · Buffalo, NY *(Aug–Dec 2025)*
- Engineered a real-time Computer Vision quality control system using **YOLOv8 Nano** and **OpenCV** to inspect **30M+ daily tickets**, achieving **88.1% mAP** and **sub-100ms inference** to eliminate high-speed production bottlenecks
- Developed a defect analysis pipeline evaluating pixel color intensity and bounding box dimensions, capturing **86.67%** of critical micro-defects while maintaining **88.45% precision** to ensure no good material was wasted
- Built a predictive maintenance module tracking dimensional drift and color deviation over time, establishing warning thresholds (**Delta E > 15**) to proactively alert operators before production failures occurred

**Lead Data Reliability Engineer** · Wipro Technologies · Bengaluru, India *(May 2022–Aug 2024)*
- Engineered **Python automation frameworks** to replace manual data validation with programmatic verification across large-scale SQL Server → Snowflake migrations, enforcing data integrity for datasets feeding downstream ML and analytics pipelines
- Audited complex business transformation logic in SQL and Python, identifying discrepancies in data models before production deployment and ensuring clean, schema-consistent datasets for downstream ML feature engineering
- Directed a sub-team of 2 QA engineers, providing technical guidance on SQL optimization and requirement analysis while establishing peer-review processes that improved data deliverable quality across the team
- Established **Ground Truth benchmarks** by reconciling Power BI KPIs against Snowflake source tables, ensuring 100% consistency between visualization layers and raw data — a critical prerequisite for reliable ML model evaluation and automated decision-making

---

## 🎓 Education & Certifications

🎓 **M.S. Data Science** — University at Buffalo, SUNY *(Dec 2025)*  
🎓 **B.Tech Electronics & Communication** — VTU, India *(Jun 2022)*  
🏅 **AI Engineering Core Track** — Udemy  
🏅 **AI Engineer Agentic Track: The Complete Agent & MCP Course** — Udemy

---

## 📊 GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=glenlouis8&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=glenlouis8&layout=compact&theme=default&hide_border=true)

</div>

---

<div align="center">

### 🟢 Available for full-time roles — AI Engineer · MLOps Engineer · Data Scientist

📧 glen.louis08@gmail.com &nbsp;|&nbsp; 🌐 [glen-louis.vercel.app](https://glen-louis.vercel.app)

</div>
