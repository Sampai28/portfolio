# Sameer Saxena

**Data Engineer | Building reliable data pipelines, cloud-native platforms, and production ML systems**

---

## About Me

I'm pursuing a Master of Science in Data Science at Northeastern University, building on a Computer Science degree (Big Data minor) from Manipal Institute of Technology. My experience spans engineering data pipelines and dashboards at BackPac Technologies, automating security data workflows on Shell's Cyber Defence team, and publishing peer-reviewed ML research. Most recently, my team's MLOps project **TicketForge** took **Third Place Overall at the MLOps Expo**, hosted by Northeastern University's College of Engineering and Google Cloud.

---

## Featured Projects

### TicketForge 🏆
**MLOps Expo (Northeastern University × Google Cloud) — Third Place Overall, June 2026**
AI-powered DevOps ticket assignment system that cuts 15–20 minutes of manual triage per ticket — Airflow-orchestrated ETL, DVC-versioned data, MLflow model registry, FastAPI inference, and Terraform-provisioned GCP deployment.
[View on GitHub](https://github.com/Sampai28/ticket-forge)

### Toolsmith
An MCP server over survey-analytics data, plus a two-factor ablation harness that measures how tool descriptions and system prompts change an LLM's tool selection — with guardrails that get attacked by an adversarial bypass suite rather than asserted. Runs entirely locally on containerised Ollama.
[View on GitHub](https://github.com/Sampai28/Toolsmith)

### Beacon
A horizontally-sharded real-time presence and session-join service in Go — three gateway replicas over Redis with a custom consistent hash ring that reassigns stale-session ownership when a node dies. Sustains 20,000 concurrent connections with every JOIN answered.
[View on GitHub](https://github.com/Sampai28/Beacon)

### Tapewatch
Market abuse surveillance — a C++20 streaming engine detecting spoofing, layering, wash trading and momentum ignition, scored against synthetic order flow with injected ground truth, plus a React triage console with order book replay. Built around the hard case: legitimate market makers who look guilty.
[View on GitHub](https://github.com/Sampai28/Tapewatch)

### Matchbook
A deterministic, single-threaded limit order book and matching engine in C++20 with price-time priority — implemented four times from a naive baseline to a cache-tuned version, all producing byte-identical event logs, plus a streaming market data gateway and a React terminal that renders the book live.
[View on GitHub](https://github.com/Sampai28/Matchbook)

### Skein
An asyncio runtime that executes agent workflows defined as directed acyclic graphs — maximal safe concurrency with bounded parallelism, real cancellation, timeouts that don't leak tasks, per-tool circuit breakers, and deterministic record and replay.
[View on GitHub](https://github.com/Sampai28/Skein)

### Strata
A local Hadoop, Hive and Spark stack used as a laboratory for measuring how physical data layout drives query performance — partition pruning, columnar formats and small-file effects, each experiment with a hypothesis, a controlled configuration and measured results.
[View on GitHub](https://github.com/Sampai28/Strata)

### Arbiter
A payment card chargeback dispute lifecycle service in Java 21 and Spring Boot 3 — explicit state machine, idempotency keys, optimistic locking and a transactional outbox over PostgreSQL and Redpanda, so a retried call never files twice and every transition actually reaches settlement.
[View on GitHub](https://github.com/Sampai28/Arbiter)

### Longlead
Probabilistic lead-time forecasting for long-lead nuclear procurement — quantile models with conformal prediction intervals, rolling-origin backtesting, and drift detection scored against injected ground truth rather than merely displayed.
[View on GitHub](https://github.com/Sampai28/Longlead)

### Dynamic Twitter Friend Grouping Using Clustering
**Published in IET Communications**
Research on social network analysis and user clustering algorithms — KMeans, BIRCH, DBSCAN, Spectral, Fuzzy C-Means, Rep-C, GMM — validated on real-world datasets (Ciao, FilmTrust).
[Read the paper](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/cmu2.12807)

### XCI-Sketch
**NeurIPS 2021 Workshops**
Converts photographs into colored sketches via K-Means color transfer and GAN-generated color-filled sketches — official implementation of an arXiv paper, with an interactive Streamlit demo.
[View on GitHub](https://github.com/Sampai28/XCI-Sketch)

### VulnLens
Serverless SAST platform on AWS that turns vulnerability scan findings into actionable insights — CWE enrichment, weighted risk scoring, DBSCAN clustering, and trend analysis, triggered from GitHub pull requests.
[View on GitHub](https://github.com/Sampai28/VulnLens)

### Kissan Mitra (Farmer's Friend)
Voice-enabled AI advisory system using multilingual NLP (5+ languages, ~86% of India's farming community), knowledge retrieval, and workflow orchestration for real-time weather, pricing, and crop advisory.
[View on GitHub](https://github.com/Kissan-Mitra/Kissan-Mitra)

### Agentic AV Scenario Generator
Multi-tool LangChain agent that converts natural-language driving descriptions into Pydantic-validated AV simulation configs across 64 environment combinations with CARLA export.
[View on GitHub](https://github.com/Sampai28/scenariogen)

### RePose — Real-Time Pose Estimation & Motion Analysis
Real-time motion analysis pipeline that tracks skeletal landmarks from video, computes joint angles, and evaluates movement symmetry for sports biomechanics.
[View on GitHub](https://github.com/Sampai28/RePose-Real-Time-Pose-Estimation-Motion-Analysis-System)

### Multimodal Infant Cry Detection System
Audio classification system combining spectral and temporal features (MFCCs, spectrograms) with deep learning to detect infant cries in noisy real-world environments.
[View on GitHub](https://github.com/Sampai28/Multimodal-Infant-Cry-Detection-System)

### Veritas — AI-Powered Documentation Verification
Embedding-based comparison and knowledge retrieval pipeline using transformer models for scalable code-document analysis, identifying semantic mismatches across 1000+ lines of code per run.
[View on GitHub](https://github.com/niloy-saha-123/veritas)

---

## Professional Experience

- **Systems Engineer** @ *Shell — Cyber Defence* (Aug 2023 – Aug 2025)
  Kept high-volume security log pipelines reliable (Azure AD and 5+ critical sources), built Splunk dashboards/alerts and a custom RBAC app, automated CrowdStrike reporting with Python + Azure DevOps, and redesigned ServiceNow workflows (30% backlog reduction).

- **Data Science Intern** @ *BackPac Technologies* (Jan 2023 – Jul 2023)
  Built Airflow data cleaning/preprocessing pipelines, shipped a Looker Studio dashboard for 1,000+ employees across 12+ departments, and ran statistical significance testing.

- **Undergraduate Research Assistant**, Manipal Institute of Technology (Aug 2021 – Dec 2022)
  Co-authored an IET Communications paper on dynamic friend grouping, validated with Silhouette, Davies-Bouldin, and Calinski-Harabasz on real-world datasets.

- **Core Team Member**, Cryptonite CTF Team (Jan 2020 – Jun 2022)
  Memory forensics specialist; contributed to NITE CTF 2021; team ranks top 100 globally on CTFtime.

---

## Technical Skills

| Data Engineering | Cloud & MLOps | Languages | Analytics & ML | Security & Observability |
|---|---|---|---|---|
| Apache Airflow, PySpark, ETL/ELT, SQL, Data Modeling | Google Cloud, AWS Lambda, Azure DevOps, CI/CD, MLOps | Python, SQL, Bash, C++, JavaScript, TypeScript | TensorFlow, PyTorch, Scikit-learn, Power BI, Looker Studio, Hypothesis Testing | Splunk Cloud, Splunk SOAR, ServiceNow SIR/VR |

---

## Achievements

- 🏆 **Third Place Overall** – MLOps Expo, Northeastern University × Google Cloud (TicketForge, June 2026)
- **2 Research Publications** – IET Communications & NeurIPS Workshops
- **2nd Place** – Code Innovation Series Hackathon (GitHub India & Department of ICT)
- **Top 3** – MakeHarvard 2021 Maker's Choice
- **7th Place** – Boss of the SOC (Shell's Splunk tournament, India–Netherlands teams)
- **Top 100 CTF Team** – Cryptonite on CTFtime
- **Academic Excellence** – 4.0/4.0 GPA at Northeastern; 3.8/4.0 with Big Data minor at MIT Manipal

---

## Education

- **Northeastern University** — MS in Data Science (Expected May 2027), Boston, MA — GPA 4.0/4.0
- **Manipal Institute of Technology** — B.Tech in Computer Science, Minor in Big Data (2019 – 2023) — GPA 3.8/4.0

---

## Let's Connect

Open to data engineering roles and collaborations in **data engineering**, **machine learning**, and **automation**:

- **Email**: [sameersaxena2810@gmail.com](mailto:sameersaxena2810@gmail.com)
- **LinkedIn**: [sameersaxena2810](https://www.linkedin.com/in/sameersaxena2810/)
- **GitHub**: [Sampai28](https://github.com/Sampai28)
