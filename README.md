# Hi, I'm Muhammad Wyzer 👋

### Machine Learning & AI Systems Engineer • Python • PyTorch • Computer Vision • Numerical Computing • Full-Stack AI

I design and build reproducible machine-learning pipelines, computer-vision training and inference systems, numerical analysis workflows, and production-grade enterprise AI applications—combining rigorous engineering verification (`pytest`, synthetic datasets, deterministic pipelines) with modern AI-assisted workflows.

<p align="center">
  <a href="https://github.com/mwyzer">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=mwyzer&show_icons=true&theme=tokyonight&hide_border=true"/>
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mwyzer&layout=compact&theme=tokyonight&hide_border=true"/>
  </a>
</p>

---

## Focus Areas

- 🧠 **Model Training & Inference Systems:** Fine-tuning object detection models (**PyTorch**, **RF-DETR**), **ONNX Runtime** export, and serverless GPU orchestration on **Modal (NVIDIA L4)** with gradient accumulation and checkpoint validation.
- 📐 **Numerical Computing & Computer Vision:** Classical and deep-learning vision pipelines (**OpenCV**, **NumPy**, morphological filtering, PCA-based geometric heuristics, **3D Gaussian Splatting / `gsplat` & COLMAP**), spatial Gaussian kernel smoothing, and accelerometer RMS signal processing.
- ⚡ **Performance Optimization & Benchmarking:** Profiling inference throughput (FPS) and latency (p50/p95/p99), memory footprint optimization, and numerical parity verification ($\epsilon \le 10^{-4}$) between PyTorch and quantized/ONNX graph representations.
- 🤖 **Agentic & Multi-Agent Architectures:** Graph-based agent routing (**LangGraph**), human-in-the-loop review systems, RAG evaluation, and asynchronous workflow execution.
- 🏢 **Enterprise & Distributed Backend Systems:** Modular monolith and microservice architectures (**Spring Boot / Java 21**, FastAPI, Django), workforce risk intelligence pipelines, Kafka/Redis event streaming, and auditable domain workflows.

**Portfolio:** https://wyzer.my.id  
**Email:** muhammad.wyzer@gmail.com  
**LinkedIn:** https://linkedin.com/in/muhammad-wyzer

---

## 🛠️ How I Use Coding Agents in My Workflow

As an engineer working on complex machine learning and backend platforms, I treat **coding agents (Claude Code, Antigravity)** as high-velocity co-engineers embedded directly into terminal and CLI environments:

1. **Spec & Guardrails-First Engineering:** Before generating implementation code, I define strict schemas (Pydantic / Zod), architectural constraints, and safety guidelines (`PRD.md`, `GUARDRAILS.md`), keeping agent generations bounded and mathematically sound.
2. **Synthetic Data & Deterministic Verification:** I guide agents to construct procedural synthetic test datasets (e.g. `tests/dataset_sintetis.py` in `cek-kondisi-rumah`) to stress-test numerical boundaries, edge cases, and OpenCV morphological filters before touching live models.
3. **Automated Test Generation & Parity Checks:** I leverage coding agents to write rigorous `pytest` suites and verify numerical equivalence (e.g. cross-validating PyTorch vs ONNX tensors, or statistical distribution tests).
4. **Reproducible Tooling & Environment Isolation:** Every workflow is pinned with modern deterministic tools (`uv.lock`, `pyproject.toml`, Docker, and CI/CD actions) so all agent-crafted implementations can be reproduced reliably on any machine or remote GPU node.

---

## Core Tech Stack

### Machine Learning, Vision & Numerical Computing

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?logo=onnx&logoColor=white)

### Backend, Frameworks & Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java_21-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?logo=springboot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

---

## Featured High-Value Engineering Projects

### 1. [Home Condition Assessment & 3D Reconstruction (`cek-kondisi-rumah`)](https://github.com/mwyzer/cek-kondisi-rumah)
End-to-end computer vision and multimodal assessment platform for structural damage analysis:
- **Model Training & Inference:** COCO dataset validation and **RF-DETR (PyTorch)** training pipeline on **Modal L4 GPUs** (`detector/latih.py`, `modal_app.py`) with gradient accumulation, early stopping, and thread-safe inference (`analyzer/deteksi.py`).
- **3D Gaussian Splatting Pipeline:** Serverless GPU worker converting room videos into 3D splats via `ffmpeg` blur filtering → `COLMAP` → `gsplat` (MCMC up to 400k Gaussians).
- **Numerical & Morphological CV:** OpenCV + NumPy analyzer implementing gradient-ratio sharpness scoring, black-hat morphological crack detection with PCA elongation/axis-alignment filtering, and synthetic dataset unit tests (`pytest` + `uv`).

### 2. [Road Surface Distress Index & Sensor Analytics (`penilai-kondisi-jalan`)](https://github.com/mwyzer/penilai-kondisi-jalan)
Automated road pavement evaluation system combining computer vision, numerical signal processing, and spatial statistics:
- **Offline Object Detection & Benchmarking:** **RF-DETR Nano** training workflow with **ONNX Runtime** export and inference benchmarking suite (`benchmark_inferensi.py`) measuring FPS, p50/p95 latency, and numerical parity.
- **Numerical & Statistical Methods:** Spatial **Gaussian kernel smoothing** (`σ = 50 m`) along road stationing, 95% confidence interval estimation, and z-score outlier detection (`|z| > 2`).
- **Signal Processing:** Vertical acceleration **RMS roughness calculation** with gravity component removal and Haversine geodesic segmentation from raw smartphone accelerometer telemetry.

### 3. [WorkforceOS — Enterprise Operations & Risk Intelligence (`WorkForceOS`)](https://github.com/mwyzer/WorkForceOS)
Enterprise REST API platform for shift-based workforce management with automated operational risk intelligence:
- **Risk Intelligence Pipeline:** Real-time risk detection engine combining heuristics and LLM-driven operational analysis to identify scheduling bottlenecks, fatigue risks, and attendance anomalies.
- **Enterprise Architecture:** Modular monolith built with **Spring Boot 3 / Java 21**, JWT security filters, PostgreSQL database migrations via Flyway, and audit-logged domain workflows.

### 4. [TalentMatch AI — Candidate Evaluation & Matching Platform (`TalentMatch-AI---Flask---ReactJS`)](https://github.com/mwyzer/TalentMatch-AI---Flask---ReactJS)
Explainable AI hiring intelligence platform that scores candidate fit with measurable evaluation metrics:
- **Explainable Scoring Engine:** Multi-stage resume-to-job matching pipeline incorporating structured extraction, semantic similarity, and deterministic qualification scoring.
- **Production Architecture:** Modular Flask REST API with clean layer boundaries, containerized multi-stage Docker builds, automated test pipelines, and GitHub Actions CI/CD.

### 5. [Shipping Operations Multi-Agent System (`shipping-ops-agent`)](https://github.com/mwyzer/shipping-ops-agent)
Domain-specific **LangGraph** multi-agent system addressing real-world logistics workflows:
- **Architecture:** One Coordinator and six specialized agents (Reconciliation, Data Entry, Reporting, Email, Pricing, Scheduling) with strict human-in-the-loop review guards.
- **Verification & Tooling:** Automated discrepancy audits (manifests vs container lists, ISO 6346 check digits), CLI utilities, and unified FastAPI backend paired with TypeScript/Next.js and zero-build HTML interfaces.

### 6. [AI Workplace Automation Platform (`django_ai_employee`)](https://github.com/mwyzer/django_ai_employee)
Enterprise AI assistant with asynchronous background execution and performance testing:
- **Async Execution & Scale:** Celery-driven task queues for asynchronous LLM/RAG workflows backed by Redis and PostgreSQL.
- **Performance & Load Testing:** Locust-based load testing suites (`locustfile.py`), comprehensive test coverage reporting, and Docker Compose orchestration.

### 7. [AI Interview & Assessment Platform (`ai-interview-platform-fs`)](https://github.com/mwyzer/ai-interview-platform-fs)
Full-stack candidate assessment and evaluation platform with strong quality engineering emphasis:
- **System Architecture:** Two-service architecture (API + Web) featuring automated candidate evaluation, scoring reproducibility, and end-to-end integration test suites.

---

## GitHub Streak

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mwyzer&theme=tokyonight&hide_border=true"/>
</p>

---

## Connect

<p align="left">
  <a href="https://github.com/mwyzer"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
  <a href="https://linkedin.com/in/muhammad-wyzer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:muhammad.wyzer@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

> *“First, solve the problem. Then, write the cleanest, most verifiable solution you can.”*

⭐ Thanks for visiting my profile!
