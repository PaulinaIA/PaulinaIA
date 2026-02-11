<div align="center">

<!-- (Opcional) Banner: subí una imagen a assets/banner.png y descomentá la línea -->
<!-- ![banner](assets/banner.png) -->

# Paulina Peralta (@PaulinaIA)

AI & Data Science • Electronic Engineer • Barcelona  
Building **end-to-end ML systems** and exploring **Generative AI for scientific simulation** (Diffusion / DiT)

[LinkedIn](https://www.linkedin.com/in/paulina-peralta-916a46140/) ·
[Email](mailto:pauliperalta@gmail.com) ·
[GitHub](https://github.com/PaulinaIA)

![Python](https://img.shields.io/badge/Python-3.10%2B-2ea44f?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1f6feb?style=for-the-badge&logo=postgresql&logoColor=white)
![Spark](https://img.shields.io/badge/Apache%20Spark-e76f00?style=for-the-badge&logo=apachespark&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-111827?style=for-the-badge&logo=polars&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232f3e?style=for-the-badge&logo=amazonaws&logoColor=white)

</div>

---

## About
I’m an Electronic Engineer focused on **Applied ML + Data Engineering**, and I’m especially interested in **Generative AI for scientific simulation** (diffusion/transformer-based models).  
I care a lot about **clean repo structure**, **reproducibility**, and building projects that feel *real* (not just notebooks).

---

## What I’m focused on now
- **Generative models for simulation** (Diffusion / DiT) and high-dimensional generation  
- **ML systems**: scraping → storage → processing (Polars/Spark) → modeling → evaluation  
- **Production mindset**: modular codebases, documentation-first, scalable pipelines  

---

## My pipeline mindset

```mermaid
flowchart LR
  A[Data Sources] --> B[Ingestion / Scraping]
  B --> C[Normalize + Validate]
  C --> D[(Storage)]
  D --> E[Processing<br/>Polars / Spark]
  E --> F[Modeling<br/>sklearn / H2O / DL]
  F --> G[Evaluation + Reporting]
  G --> H[Delivery<br/>Dashboards / API / Notebooks]
```

## Featured projects (my current favorites)

### 🌸 Bloom — Adaptive fertility prediction (ML + personalization)
A cycle prediction system that combines ML + personalized signals to estimate cycle length and ovulation timing.
- Clean modular design (feature engineering + predictors + evaluation)
- Emphasis on interpretability and practical use
flowchart LR
  X[(User Logs)] --> FE[Feature Engineering]
  FE --> M1[Cycle Predictor]
  FE --> M2[Ovulation Classifier]
  M1 --> OUT[Predictions + Insights]
  M2 --> OUT
Repo: https://github.com/PaulinaIA/Bloom

### 🛡️ Dark Eye Core — Threat Intelligence ETL + dashboards
Pipeline that extracts and normalizes IoCs from multiple sources and visualizes them in Grafana.
- Multi-source ingestion (AbuseIPDB / URLhaus / OTX)
- Normalization + relational storage + observability-ready design
flowchart LR
  S1[AbuseIPDB] --> N[Normalizers]
  S2[URLhaus] --> N
  S3[AlienVault OTX] --> N
  N --> DB[(PostgreSQL)]
  DB --> G[Grafana Dashboards]
Repo: https://github.com/PaulinaIA/dark_eye_core

### 🤖 Moltbook Safety — Web scraping + behavioral signals → karma prediction
End-to-end data engineering + applied ML project.
- Web scraping → relational model → processing with Polars/Spark → modeling (H2O AutoML)
- Focus on content/behavior features and responsible analysis
flowchart LR
  W[Web Scraping] --> R[(Relational Tables)]
  R --> P[Processing<br/>Polars / Spark]
  P --> FS[Feature Set]
  FS --> ML[Modeling<br/>H2O AutoML]
  ML --> EV[Metrics + Insights]  
Repo: https://github.com/PaulinaIA/moltbook-safety

---

## Tech stack (curated)
**Python · SQL · Spark · Polars · Airflow · Docker · AWS · scikit-learn · PyTorch · TensorFlow**  
Also: R · MATLAB · C/C++ · Embedded/IoT background

---

## How I work
- I care about **clarity** (simple architecture, readable code)
- I prioritize **reproducibility** (structured repos, deterministic pipelines when possible)
- I like projects with **meaning + impact**, not only metrics

---

## Contact
📩 pauliperalta@gmail.com  
🔗 https://www.linkedin.com/in/paulina-peralta-916a46140/

