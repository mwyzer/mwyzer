# Hi, I'm Muhammad Wyzer 👋

### Machine Learning & AI Systems Engineer • Python • PyTorch • Computer Vision • Numerical Computing • TypeScript

I design and build reproducible machine-learning pipelines, computer-vision training and inference systems, numerical analysis workflows, and agentic AI applications—combining rigorous verification (`pytest`, synthetic datasets, deterministic pipelines) with modern AI-assisted engineering workflows.

<p align="center">
  <a href="https://github.com/mwyzer">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=mwyzer&show_icons=true&theme=tokyonight&hide_border=true"/>
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mwyzer&layout=compact&theme=tokyonight&hide_border=true"/>
  </a>
</p>

---

## Focus Areas

- 🧠 **Model Training & Inference Systems:** Fine-tuning object detection models (**PyTorch**, **RF-DETR**), **ONNX** export, and serverless GPU orchestration on **Modal (NVIDIA L4)** with gradient accumulation and checkpoint validation.
- 📐 **Numerical Computing & Computer Vision:** Classical and deep-learning vision pipelines (**OpenCV**, **NumPy**, morphological filtering, PCA-based geometric heuristics, **3D Gaussian Splatting / `gsplat` & COLMAP**), spatial Gaussian kernel smoothing, and accelerometer RMS signal processing.
- 🤖 **Agentic Workflows & Reproducible Python Engineering:** High-velocity development using **coding agents** (Claude Code, Antigravity) paired with modern Python tooling (`uv`, `pytest`, FastAPI, CLI automation, synthetic test suites, and CI/CD).

**Portfolio:** https://wyzer.my.id  
**Email:** muhammad.wyzer@gmail.com  
**LinkedIn:** https://linkedin.com/in/muhammad-wyzer

---

## Core Tech Stack

### Machine Learning, Vision & Numerical Computing

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?logo=onnx&logoColor=white)

### Backend, Infrastructure & Reproducible Tooling

![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

---

## Featured ML, Vision & AI Systems Projects

### 1. [Home Condition Assessment & 3D Reconstruction (`cek-kondisi-rumah`)](https://github.com/mwyzer/cek-kondisi-rumah)
End-to-end computer vision and multimodal assessment platform for structural damage analysis:
- **Model Training & Inference:** COCO dataset validation and **RF-DETR (PyTorch)** training pipeline on **Modal L4 GPUs** (`detector/latih.py`, `modal_app.py`) with gradient accumulation, early stopping, and thread-safe inference (`analyzer/deteksi.py`).
- **3D Gaussian Splatting Pipeline:** Serverless GPU worker converting room videos into 3D splats via `ffmpeg` blur filtering → `COLMAP` → `gsplat` (MCMC up to 400k Gaussians).
- **Numerical & Morphological CV:** OpenCV + NumPy analyzer implementing gradient-ratio sharpness scoring, black-hat morphological crack detection with PCA elongation/axis-alignment filtering, and synthetic dataset unit tests (`pytest` + `uv`).

### 2. [Road Surface Distress Index & Sensor Analytics (`penilai-kondisi-jalan`)](https://github.com/mwyzer/penilai-kondisi-jalan)
Automated road pavement evaluation system combining computer vision, numerical signal processing, and spatial statistics:
- **Offline Object Detection:** **RF-DETR Nano** training workflow on Road Damage Dataset (RDD) with **ONNX** export for low-latency deployment.
- **Numerical & Statistical Methods:** Spatial **Gaussian kernel smoothing** (`σ = 50 m`) along road stationing, 95% confidence interval estimation, and z-score outlier detection (`|z| > 2`).
- **Signal Processing:** Vertical acceleration **RMS roughness calculation** with gravity component removal and Haversine geodesic segmentation from raw smartphone accelerometer telemetry.

### 3. [Multi-Agent Shipping Operations System (`shipping-ops-agent`)](https://github.com/mwyzer/shipping-ops-agent)
Modular Python multi-agent system orchestrating pricing, schedule reconciliation, data entry, and reporting workflows via graph-based agent routing, CLI tooling, and automated CI validation.

### 4. [Django AI Employee (`django_ai_employee`)](https://github.com/mwyzer/django_ai_employee)
AI-assisted workflow automation platform with asynchronous task processing (Celery), load testing (Locust), containerized deployment, and automated test coverage.

---

## Engineering & Verification Practices

- **Reproducible ML Workflows:** Deterministic environment management with `uv` (`uv.lock`), Docker, and CLI-first training/evaluation scripts.
- **Objective Verification:** Automated unit and integration testing with `pytest`, synthetic image/dataset generators, and strict schema validation (Zod / Pydantic).
- **AI-Assisted Development:** Extensive daily workflow integrating coding agents (Claude Code, Antigravity) with Python for rapid prototyping, numerical debugging, and test generation.

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
