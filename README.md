<div align="center">

# 👾 Marian Glen Louis
### AI Engineer · Agentic Systems · MLOps · Multi-Agent Workflows

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Building+Autonomous+AI+Agents+%F0%9F%A4%96;LangGraph+%7C+MCP+%7C+Agentic+RAG;Self-Correcting+Multi-Agent+Systems;Bridging+Legacy+Infra+%E2%86%92+Production+AI)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Marian_Glen_Louis-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marian-glen-louis)
[![Portfolio](https://img.shields.io/badge/Portfolio-glen--louis.vercel.app-black?style=for-the-badge&logo=vercel&logoColor=white)](https://glen-louis.vercel.app)
[![Email](https://img.shields.io/badge/Email-rockyglen86@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rockyglen86@gmail.com)

</div>

---

## 🧠 About Me

> *"I don't just build models — I build systems that think, correct themselves, and act."*

I'm an **AI Engineer** specialized in architecting **autonomous, self-correcting agentic systems** and **multi-agent workflows** using **LangGraph** and **MCP**. My work sits at the intersection of AI research and production engineering — taking cutting-edge agentic patterns and making them reliable, observable, and deployable.

With a background in **Data Reliability Engineering** at Wipro Technologies, I bring a unique lens to AI: I've seen what happens when data pipelines fail at scale, and I build AI systems designed not to. I'm currently completing my **M.S. in Data Science at the University at Buffalo** (Dec 2025), where I've taken that foundation and gone deep on the full MLOps lifecycle — from feature stores and drift detection to LLM-powered compliance engines.

**What drives me:** I believe the next frontier isn't just smarter models — it's smarter *systems*. Agents that can plan, audit, self-correct, and collaborate. That's what I build.

---

## 🛠️ Tech Stack

<div align="center">

### 🤖 Agentic AI
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=for-the-badge&logo=python&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-6C3483?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F54033?style=for-the-badge&logoColor=white)
![Ragas](https://img.shields.io/badge/Ragas_Evaluation-4B8BBE?style=for-the-badge&logo=python&logoColor=white)

### ☁️ MLOps & Cloud
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Prefect](https://img.shields.io/badge/Prefect-024DFD?style=for-the-badge&logo=prefect&logoColor=white)

### 🗄️ Data Architecture
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant_VectorDB-DC244C?style=for-the-badge&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 🧪 Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=python&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

</div>

---

## 🚀 Featured Projects

---

### 🔐 [Aegis-Flow — Multi-Agent Cloud Security Orchestrator](https://github.com/rockyglen/ageis-flow)

> *Autonomous AI agent that audits, remediates, and verifies AWS infrastructure security — with a human-in-the-loop safety gate.*

**The Problem:** Manual AWS security audits are slow, inconsistent, and don't scale. A misconfigured IAM policy or open S3 bucket can go undetected for weeks.

**The Solution:** A fully autonomous multi-agent system that continuously monitors your AWS environment, identifies security violations, proposes remediations, gets human approval, and then executes — all within a stateful, observable graph.

| Component | Technology | Purpose |
|-----------|------------|---------|
| Agentic Workflow | LangGraph | State machine with conditional routing |
| Tool Layer | Model Context Protocol (MCP) | Exposes AWS APIs to the LLM |
| Infrastructure | AWS IAM · S3 · EC2 | Real-time environment interaction |
| Safety Gate | Human-in-the-loop node | Approval before any remediation runs |
| Persistence | LangGraph MemorySaver | Multi-turn context across investigations |

**Key Highlights:**
- 🧩 **Specialized agents:** Auditor detects risks; Remediator executes fixes — separated by a mandatory human approval gate
- 🔧 **MCP server** exposes live AWS tools to the LLM for precise, tool-augmented generation (TAG)
- 🔁 **State persistence** allows the agent to maintain context across multi-turn security investigations and handle async approvals
- ✅ **Post-fix verification** loop confirms remediation success before closing an investigation cycle

---

### 📋 [AuditAI — Agentic RAG Compliance Engine](https://github.com/rockyglen/audit-ai-backend)

> *A self-correcting RAG system that autonomously audits internal policies against the NIST Cybersecurity Framework (CSF 2.0).*

**The Problem:** Standard "one-shot" RAG pipelines fail in high-stakes compliance environments — a single bad retrieval leads to hallucinated audit findings, which can have serious legal consequences.

**The Solution:** A self-correcting agentic graph that detects when retrieval is poor, rewrites the query, and re-executes — all autonomously — until it finds grounded evidence or escalates.

| Component | Technology | Purpose |
|-----------|------------|---------|
| Graph Architecture | LangGraph + CRAG | Self-correcting retrieval loop |
| Vector Store | Qdrant | Semantic search over NIST CSF 2.0 |
| Semantic Router | Fast-path LLM classifier | Bypass graph for non-compliance queries |
| Evaluation | Ragas | Faithfulness & context recall scoring |
| Backend | FastAPI | Production API layer |

**Key Highlights:**
- 🎯 **1.00 Faithfulness score** — every audit finding is strictly derived from the verified compliance database
- 📈 **0.90 Context Recall score** — validated via RAGAS evaluation framework
- ⚡ **Semantic Router** reduces latency by classifying compliance vs. general chat and bypassing the heavy agentic graph for non-technical queries
- 🔄 **CRAG pattern** with document grader + query transformer enables autonomous search refinement when initial retrieval fails

---

### 🏎️ [F1 Apex Guardian — MLOps & AI Engineering](https://github.com/rockyglen/f1_apex_guardian)

> *End-to-end MLOps pipeline for real-time F1 telemetry anomaly detection with automated weekly retraining and live dashboarding.*

**The Problem:** F1 telemetry data is high-velocity and constantly drifting — a model trained on last season's data is stale by race day. Manual retraining is too slow and error-prone.

**The Solution:** A fully automated MLOps pipeline that ingests weekly telemetry, detects feature drift, triggers retraining when needed, and serves predictions through a live containerized dashboard.

| Component | Technology | Purpose |
|-----------|------------|---------|
| CI/CD Pipeline | GitHub Actions + uv | Zero-touch weekly retraining |
| Feature Store | AWS S3 + joblib | Multi-layer caching |
| Drift Detection | Kolmogorov-Smirnov tests | Statistical drift monitoring |
| Anomaly Detection | Isolation Forest | Race incident prediction |
| Experiment Tracking | MLflow + DagsHub | Lineage & versioning |
| Dashboard | Streamlit + Docker | Deployed on Hugging Face |

**Key Highlights:**
- 📉 **85% reduction** in dashboard latency via AWS S3 feature store + multi-layer caching
- 🔬 **KS statistical tests** detect feature drift in high-velocity telemetry and trigger automated Isolation Forest retraining
- 🐳 **Dockerized Streamlit dashboard** deployed on Hugging Face Spaces with full experiment lineage in DagsHub + MLflow
- ♻️ **Zero-touch pipeline** — data ingestion → feature engineering → model retraining → deployment, fully automated

---

### 🚲 [Citi-Bike Taxi — Automated MLOps Pipeline](https://github.com/rockyglen/bike_Taxi)

> *Production-grade demand forecasting system for NYC Citi Bike fleet management with real-time 24-hour predictions.*

**The Problem:** NYC Citi Bike data has a 20-day publishing lag — making real-time demand forecasting seemingly impossible with standard time-series approaches.

**The Solution:** A custom Recursive Bridge algorithm that generates real-time 24-hour demand forecasts despite the lag, backed by a fully automated monthly retraining pipeline and a live Next.js dashboard.

| Component | Technology | Purpose |
|-----------|------------|---------|
| Forecasting | Recursive Bridge (custom) | Overcomes 20-day data lag |
| ETL Pipeline | Pandas + PyArrow + Parquet | Streaming 12-month data ingestion |
| Feature Store | AWS S3 | Scalable Parquet feature storage |
| Experiment Tracking | MLflow | Model versioning & registry |
| CI/CD | GitHub Actions | Monthly retraining + hourly inference |
| Dashboard | Next.js 14 + Evidently AI | Live drift monitoring & fleet demand |

**Key Highlights:**
- 📊 **5.11 MAE / 8.04 RMSE** maintained via automated monthly retraining
- 🧠 **Custom Recursive Bridge algorithm** generates real-time forecasts by bridging the 20-day data publishing gap
- 🌊 **Streaming ETL** processes 12 months of raw ride data memory-efficiently into Parquet features on AWS S3
- 📡 **Next.js 14 dashboard** with Evidently AI integration for live drift monitoring, feature importances, and model health

---

## 💼 Work Experience

### 🔬 Data Scientist Intern — Nissha Medical Technologies *(Buffalo, NY | Aug–Dec 2025)*
- Built an end-to-end **computer vision system** using **YOLOv8 + OpenCV** to automate defect detection across **30M+ daily production tickets**
- Transitioned the facility from reactive to **predictive maintenance**, reducing material waste and machine downtime via real-time defect alerts

### ⚙️ Lead Data Reliability Engineer — Wipro Technologies *(Bengaluru, India | May 2022–Aug 2024)*
- Engineered **Python-based validation frameworks** to automate large-scale data migration verification from SQL Server → Snowflake
- Led **ETL transformation observability**, using SQL + Python to detect and resolve data drift during cloud-native transitions
- Directed a sub-team of 2, establishing peer-review standards and ensuring high-fidelity data deliverables for ML downstream systems
- Established **Ground Truth benchmarks** reconciling Power BI metrics with Snowflake backend records — critical for preventing hallucinations in automated decision layers

---

## 🎓 Education

🎓 **M.S. Data Science** — University at Buffalo, The State University of New York *(Dec 2025)*  
🎓 **B.Tech Electronics & Communication Engineering** — VTU, India *(Jun 2022)*

---

## 📜 Certifications

- 🏅 **AI Engineering Core Track** — Udemy
- 🏅 **AI Engineer Agentic Track: The Complete Agent & MCP Course** — Udemy

---

## 📊 GitHub Stats

<div align="center">

![Marian's GitHub Stats](https://github-readme-stats.vercel.app/api?username=rockyglen&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rockyglen&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=rockyglen&theme=tokyonight&hide_border=true)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=rockyglen&theme=tokyonight&no-frame=true&row=1&column=7)

</div>

---

<div align="center">

![Visitor Count](https://komarev.com/ghpvc/?username=rockyglen&color=00F7FF&style=for-the-badge&label=PROFILE+VIEWS)

*"The goal is not to automate tasks — it's to build systems that think."*

</div>
