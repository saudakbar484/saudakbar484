<div align="center">

# SAUD AKBAR

### AI Engineer · Agentic AI Engineer · RAG · Computer Vision · Full-Stack ML Systems

<p>
  <a href="https://saud-akbar.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-0A0A0A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://linkedin.com/in/saud-akbar">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:saudakbar65367@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/saudakar484">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&center=true&vCenter=true&width=760&lines=Building+Agentic+AI+Systems;RAG+%7C+LLM+Agents+%7C+Multi-Agent+Orchestration;Computer+Vision+%7C+Applied+Machine+Learning;Production-Grade+AI+APIs+%26+MLOps" alt="Typing SVG"/>

</div>

---

## 👋 About Me

I am an **AI Engineer / Agentic AI Engineer** focused on building practical AI systems that move beyond standalone models into **reasoning, retrieval, tool use, orchestration, evaluation, and production deployment**.

My work spans:

- 🤖 Agentic AI, LLM applications & multi-agent systems
- 🔎 RAG, semantic retrieval & grounded question answering
- 👁️ Computer vision & real-time biometric systems
- 🧠 Deep learning and applied machine learning
- 🛡️ AI-powered cybersecurity / SIEM systems
- ⚙️ FastAPI, microservices, Docker & MLOps
- 📊 AI evaluation, benchmarking & verification
- 💻 Full-stack AI applications

I enjoy taking an AI idea from **research → architecture → implementation → evaluation → deployment**.

---

## 🚀 Current Focus

| Area | What I'm Building |
|---|---|
| 🤖 Agentic AI | LLM agents, tool calling, multi-agent orchestration and autonomous workflows |
| 🔎 RAG | Enterprise document intelligence, grounded retrieval and reasoning |
| 🛡️ AI Security | Multi-agent AI layer over Wazuh SIEM for security event analysis |
| 👁️ Computer Vision | Real-time palm-vein biometric identification and verification |
| 📊 AI Evaluation | Deterministic/dynamic verifiers, AST analysis and anti-reward-hacking evaluation |
| ⚙️ MLOps | Model registries, drift monitoring, retraining triggers and reproducible pipelines |
| 🧩 Enterprise AI | Production APIs, databases, vector search and full-stack AI platforms |

---

# ⭐ Featured Engineering Projects

## 🧑‍💼 PeopleAI — Enterprise Workforce Intelligence

An enterprise workforce intelligence and employee-experience platform combining predictive ML, explainability, anomaly detection and policy-grounded RAG.

**Highlights**
- 1,000+ seeded employees
- XGBoost employee-turnover model
- **ROC-AUC: 0.942**
- SHAP-based local explainability
- Isolation Forest anomaly detection
- Policy-grounded RAG assistant
- Champion/candidate model registry
- PSI-based model drift monitoring

**Stack:** `Vue 3` `TypeScript` `Laravel 11` `FastAPI` `XGBoost` `SHAP` `Isolation Forest` `ChromaDB` `Groq`

---

## 🛡️ AI-Powered Wazuh Security Layer

A multi-agent AI security architecture designed around a clustered Wazuh SIEM environment.

**Architecture**

```text
                    ┌──────────────────────┐
                    │    Wazuh Cluster     │
                    │   Logs + Security    │
                    │       Events         │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    Agent 1           │
                    │ Categorization       │
                    │ Normal / Problematic │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    Agent 2           │
                    │ Threat Classification│
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │    Agent 3           │
                    │ Reconciliation /     │
                    │ Decision Support     │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Human-in-the-Loop    │
                    │ Observe → Recommend  │
                    │ → Approval → Safe    │
                    └──────────────────────┘
```

**Technologies:** `Wazuh` `Python` `PyTorch` `FastAPI` `MCP` `Docker` `LLMs` `RAG` `MITRE ATT&CK`

---

## 🖐️ Palm Vein Recognition System

A contactless biometric identification and authentication system using near-infrared palm-vein imagery.

**Highlights**
- Real-time NIR image acquisition
- 1:1 verification
- 1:N identification
- Benchmarking of multiple CNN architectures
- EfficientNet-B0 + CBAM
- **~98% validation accuracy**
- **EER: 0.204**
- **3,000+ images / 130+ subjects**
- Published custom dataset

**Stack:** `Python` `PyTorch` `EfficientNet` `CBAM` `OpenCV` `NIR Imaging`

### Dataset

**SASH-VPV — Subcutaneous Vascular Palm Vein Dataset**

<a href="https://www.kaggle.com/datasets/sashinoventures/sash-vpv-subcutaneous-vascular-palm-vein-data">
<img src="https://img.shields.io/badge/Kaggle-Dataset-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle Dataset"/>
</a>

---

## 🎙️ Kafeel — PSH Voice AI Assistant

A production-oriented voice AI assistant for NGO donation and child-sponsorship workflows.

**Highlights**
- Real-time voice interaction
- RAG-powered responses
- Session-state management
- Confirm-before-commit workflow
- No optimistic transaction success
- FastAPI backend

**Stack:** `Python` `LiveKit` `Deepgram` `RAG` `FastAPI`

---

## 🔎 Enterprise RAG + Text-to-SQL

A multi-agent enterprise knowledge system that routes natural-language questions between document retrieval, Text-to-SQL and hybrid reasoning workflows.

**Highlights**
- Document question answering
- Natural-language → SQL
- PostgreSQL integration
- Qdrant vector retrieval
- LangGraph routing
- Grounded answers with citations
- SQL + confidence output
- RAGAS / SQL evaluation gates
- Approx. **5–7s** response latency

**Stack:** `Python` `FastAPI` `LangGraph` `PostgreSQL` `Qdrant` `Groq` `Langfuse` `sqlglot`

---

## 🔥 Early Fire & Smoke Detection

Real-time fire and smoke detection using YOLOv8.

**Results**
- **mAP50: 85.7%**
- **Precision: 82.8%**
- **Recall: 87.8%**

**Stack:** `Python` `PyTorch` `YOLOv8` `Roboflow` `OpenCV` `Ultralytics`

---

## 🏠 Gesture-Controlled Home Automation

Computer-vision-based home automation system using real-time hand landmarks and gesture classification.

🏆 **2nd Prize — ICAT 2024**

**Stack:** `Python` `TensorFlow` `Keras` `MediaPipe` `CNN` `Arduino` `OpenCV`

---

# 🧪 Other AI / ML Projects

| Project | Technologies |
|---|---|
| 🩺 Diabetic Retinopathy Detection | PyTorch · EfficientNet-B0 · NSGA-II · Scikit-learn |
| 😊 Facial Emotion Detection | TensorFlow · Keras · OpenCV · CNN · TTS |
| 📚 Enterprise RAG API | FastAPI · LangChain · Pinecone · Chroma · OpenAI |
| 🧠 ML Fundamentals from Scratch | NumPy · Backpropagation · Gradient Descent · K-Means |
| 🖥️ Full-Stack AI Applications | React · Vue 3 · TypeScript · FastAPI · Node.js |

---

# 🧰 Technology Stack

### 🤖 AI / Agentic AI

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square"/>
<img src="https://img.shields.io/badge/RAG-6A1B9A?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square"/>
</p>

### 🧠 Machine Learning / Deep Learning

<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
</p>

### 👁️ Computer Vision

`OpenCV` · `MediaPipe` · `YOLOv8` · `EfficientNet` · `CBAM` · `CNNs` · `Transformers` · `Real-Time Inference` · `ROI Extraction` · `NIR Imaging`

### 🔎 Vector Databases / Retrieval

`Qdrant` · `Pinecone` · `ChromaDB` · `Embeddings` · `Semantic Search` · `Reranking`

### 🛡️ Cybersecurity / SIEM

`Wazuh` · `MCP` · `MITRE ATT&CK` · `MISP` · `VirusTotal` · `AbuseIPDB` · `MITRE Caldera` · `Atomic Red Team`

### ⚙️ Backend / APIs

`FastAPI` · `Node.js` · `Express.js` · `Laravel 11` · `REST APIs` · `Celery` · `Redis` · `Microservices`

### 🚀 MLOps / DevOps

`Docker` · `GitHub Actions` · `CI/CD` · `Model Registry` · `PSI Drift Monitoring` · `Retraining Pipelines` · `Ubuntu`

### 💻 Frontend

`React` · `Vue 3` · `Tailwind CSS` · `TypeScript` · `JavaScript` · `Flutter`

### 🗄️ Databases

`PostgreSQL` · `MySQL` · `Firebase` · `SQLite`

---

# 🧠 Engineering Philosophy

```text
Research
   ↓
Problem Definition
   ↓
Data / Knowledge Layer
   ↓
Model / Agent Architecture
   ↓
Evaluation
   ↓
API / System Integration
   ↓
Deployment
   ↓
Monitoring & Continuous Improvement
```

I focus on building systems that are:

- **Grounded** — responses should be connected to reliable data or evidence
- **Evaluated** — models and agents should be measured, not assumed to work
- **Observable** — production systems need logs, traces and monitoring
- **Composable** — complex workflows should be built from clear components
- **Deployable** — research should translate into usable systems

---

# 🔬 Research

### Ethics of Generative AI in Marketing: A Multi-Stakeholder Approach to Implementation

**Namal Business Conference (NBC 2026)**  
Technology & Innovation

Research coverage included:
- **47 case studies**
- **23 ethical models**
- Reported **89% coverage** compared with **43%** for existing frameworks

---

# 🏆 Achievements

- 🥈 **2nd Prize — ICAT 2024**
- 🖐️ Developed and published a **3,000+ image / 130+ subject** palm-vein dataset
- 📈 Achieved **0.942 ROC-AUC** in PeopleAI turnover prediction
- 🔥 Achieved **85.7% mAP50** in fire/smoke detection
- 👁️ Achieved approximately **98% validation accuracy** in palm-vein recognition
- 🧪 Worked on AI evaluation and verification systems across multiple domains

---

# 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=saudakar484&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="Saud Akbar GitHub Stats"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saudakar484&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=html,css" alt="Top Languages"/>

</div>

<br/>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=saudakar484&theme=tokyo-night&hide_border=true&area=true&custom_title=Saud%20Akbar%20-%20Contribution%20Activity" alt="Contribution Activity"/>

</div>

---

# 🏅 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=saudakar484&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&margin-h=8&row=1&column=7" alt="GitHub Trophies"/>

</div>

---

# 🎓 Education

**BS Artificial Intelligence — National University of Technology (NUTECH)**  
`Sep 2022 – Jul 2026`

Relevant areas:
`Data Structures` · `Machine Learning` · `Deep Learning` · `Computer Vision` · `NLP` · `Artificial Neural Networks` · `Software Engineering`

---

# 📜 Certifications

- Deep Learning Specialization — DeepLearning.AI / Coursera
- Computer Vision with TensorFlow
- Python for Data Science & AI — IBM / Coursera
- AI / ML Internship Certifications
- Web Development Internship Certifications

---

# 🤝 Let's Connect

<div align="center">

<a href="https://saud-akbar.vercel.app">
<img src="https://img.shields.io/badge/🌐_Portfolio-Visit-0A0A0A?style=for-the-badge"/>
</a>

<a href="https://linkedin.com/in/saud-akbar">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/saudakar484">
<img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:saudakbar65367@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

<div align="center">

### Building intelligent systems from research to production.

**AI · Agentic Systems · RAG · Computer Vision · MLOps · Cybersecurity**

</div>
