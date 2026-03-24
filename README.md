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
| ☁️ Cloud & Infrastructure | AWS (IAM, S3, EC2), Docker, Terraform, GitHub Actions CI/CD |
| 📉 Measurable Impact | 85% dashboard latency reduction; 5.11 MAE maintained across automated retraining cycles |
| 🧠 Rare Skill Set | LangGraph · MCP · CRAG · Agentic RAG — expertise most teams are still building toward |

---

## 🔑 Core Skills

**Agentic AI:** LangGraph · Model Context Protocol (MCP) · Agentic RAG · CRAG · Ragas · Groq  
**MLOps & Cloud:** AWS · Docker · GitHub Actions · MLflow · DVC · Terraform · Prefect  
**Data:** Snowflake · Qdrant (Vector DB) · Supabase · FastAPI · SQL · Python · PyArrow  
**ML:** PyTorch · LightGBM · YOLOv8 · OpenCV · Pandera · Isolation Forest  

---

## 🚀 Projects — What I've Actually Built

> Each project below is production-grade, end-to-end, and on GitHub.

---

### 🔐 [Aegis-Flow — Multi-Agent Cloud Security Orchestrator](https://github.com/rockyglen/ageis-flow)
**LangGraph · MCP · AWS IAM/S3/EC2 · Human-in-the-Loop**

An autonomous AI system that audits AWS infrastructure for security risks, proposes remediations, requests human approval, executes fixes, and verifies success — all without manual intervention.

- Architected a **multi-agent graph** (Auditor → Safety Gate → Remediator → Verifier) using LangGraph with full conditional routing and state persistence
- Built a **Model Context Protocol (MCP) server** that exposes live AWS tools directly to an LLM — enabling real-time cloud interaction through natural language
- Designed a **human-in-the-loop approval gate** so no remediation runs without explicit sign-off, ensuring operational safety
- Implemented **MemorySaver checkpointing** for multi-turn context across long-running security investigations

> *Why it matters to a hiring team: This isn't a chatbot. It's a working autonomous agent operating on real infrastructure with safety controls. This is the kind of system that replaces expensive manual security audits.*

---

### 📋 [AuditAI — Agentic RAG Compliance Engine](https://github.com/rockyglen/audit-ai-backend)
**LangGraph · CRAG · Qdrant · FastAPI · Ragas**

A self-correcting AI system that audits company policies against the NIST Cybersecurity Framework — autonomously, with verified accuracy.

- Built a **Corrective RAG (CRAG)** pipeline that detects poor retrievals, rewrites queries, and re-searches — no hallucinated findings
- Achieved **1.00 Faithfulness** and **0.90 Context Recall** in RAGAS evaluation — every finding is traceable to source documents
- Designed a **Semantic Router** that classifies queries and bypasses the heavy agentic graph for general questions, cutting unnecessary latency
- Deployed with a **FastAPI backend** ready for enterprise integration

> *Why it matters to a hiring team: Compliance is a billion-dollar problem. This system automates what typically requires expensive consultants and manual review, with measurable, auditable accuracy.*

---

### 🏎️ [F1 Apex Guardian — MLOps Pipeline](https://github.com/rockyglen/f1_apex_guardian)
**GitHub Actions · AWS S3 · MLflow · Docker · Streamlit · DagsHub**

A fully automated MLOps system for F1 telemetry anomaly detection — zero human intervention from data ingestion to live dashboard.

- Reduced dashboard latency by **85%** via a multi-layer caching strategy on an AWS S3 feature store
- Automated weekly model retraining with **GitHub Actions CI/CD** — data in, new model out, no manual steps
- Integrated **Kolmogorov-Smirnov drift detection** to trigger retraining only when needed, keeping the Isolation Forest model accurate
- Containerized and deployed a **Streamlit dashboard** on Hugging Face via Docker, with full lineage tracking in MLflow + DagsHub

> *Why it matters to a hiring team: This demonstrates the full MLOps loop — not just model training, but automated retraining, drift monitoring, and production deployment. This is what senior ML engineers are hired to build.*

---

### 🚲 [Citi-Bike Taxi — Demand Forecasting Pipeline](https://github.com/rockyglen/bike_Taxi)
**Python · AWS S3 · MLflow · GitHub Actions · Next.js 14 · Evidently AI**

A production-grade demand forecasting system for NYC's Citi Bike fleet — solving a 20-day data lag problem with a custom algorithm.

- Invented a **Recursive Bridge algorithm** to generate real-time 24-hour demand forecasts despite a 20-day raw data publishing delay
- Maintained **5.11 MAE / 8.04 RMSE** across automated monthly retraining cycles with zero manual intervention
- Built a **streaming ETL pipeline** (Pandas + PyArrow → Parquet → S3) processing 12 months of ride data efficiently
- Shipped a **Next.js 14 dashboard** with Evidently AI for live drift monitoring and fleet demand visualization

> *Why it matters to a hiring team: Custom algorithm design + automated MLOps + live dashboard = a full product, not a notebook.*

---

## 💼 Experience

**Data Scientist Intern** · Nissha Medical Technologies · Buffalo, NY *(Aug–Dec 2025)*
- Built a **YOLOv8 + OpenCV** vision system processing **30M+ daily production tickets** for automated defect detection
- Shifted facility operations to predictive maintenance, cutting material waste and unplanned machine downtime

**Lead Data Reliability Engineer** · Wipro Technologies · Bengaluru, India *(May 2022–Aug 2024)*
- Engineered **Python validation frameworks** automating SQL Server → Snowflake migration verification for ML-downstream datasets
- Led a sub-team of 2 engineers; established code review standards and ensured data fidelity across cloud-native transitions
- Built **Ground Truth benchmarks** reconciling Power BI dashboards with Snowflake backend — preventing hallucinations in automated decision layers

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

📧 glen.louis08@gmail.com &nbsp;|&nbsp;  &nbsp;|&nbsp; 🌐 [glen-louis.vercel.app](https://glen-louis.vercel.app)

</div>
