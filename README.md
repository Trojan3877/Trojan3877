Hi, I’m Corey Leath (Trojan3877)

🎓 AS in Engineering Technology (Machine Learning) @ DeVry University (Sep 2025)  
🎓 Dual BS in Artificial Intelligence & Advancing Computer Science @ UAT (Sept 2027)  
🎓 Starting MSSE in Molecular Science & Software Engineering @ UC Berkeley (Online, July 2028)  
🎓 PhD candidate in Artificial Intelligence (’28+)

🔧 Tech stack  
• Languages: Python · Go · C++ · Java · JavaScript · HTML · CSS  
• ML & Data: TensorFlow · PyTorch · scikit-learn · Snowflake · Databricks · AWS SageMaker  
• Infra & DevOps: Docker · Kubernetes · Helm · CI/CD (GitHub Actions) · Terraform  
• Front-end & UX: React · Tailwind CSS · Figma  

📌 Pinned projects  
• **Diabetes Prediction ML Pipeline** – End-to-end workflow for predicting diabetes onset using EHR data (Logistic Regression, XGBoost, DVC, Airflow, FastAPI)  
• **LLM Quant Assistant** – AI-driven quant research tool (Python/Go, real-time financial modeling, DVC, Ansible)  
• **Facial Emotion Recognition System** – CV capstone with ≥ 92% accuracy (PyTorch, FastAPI, Docker)  
• **AI Vehicle Safety Classifier** – C++ safety classifier with Python mirror & full test suite (Docker, CI)  
• **NYC Finance Data Engineering** – End-to-end ETL & analytics on public NYC finance data (Spark, Snowflake)  
• **AWS-SageMaker-Snowflake ML Pipeline** – Helm-orchestrated ML workflow (Terraform, Ansible, GitOps)  

🎯 Career goal: L6 + ML/AI Engineer at OpenAI ∣ Anthropic ∣ DeepMind ∣ Netflix ∣ Meta ∣ Google | Microsoft | XAI | WAYMO | FinTech | Stripe |  

📬 Connect or collaborate:  
• corey22blue@hotmail.com  
• coreyleath10@gmail.com  
• [LinkedIn](https://linkedin.com/in/corey-leath)  
# Facial Emotion Recognition System (FER)

> Real-time classification of facial expressions with a simple API, reproducible metrics, and deployment-ready scaffolding.

## Results (at a glance)
| Metric       | Value | Notes                              |
|-------------:|------:|------------------------------------|
| Accuracy     | 0.00  | FER2013 test split (7 classes)     |
| F1 (macro)   | 0.00  | class-balanced report              |
| Latency (p50)| 0 ms  | CPU, 224×224 RGB, batch=1          |

> Replace with your actual numbers after running `python scripts/eval.py`.

---

## Quickstart

```bash
# 1) Setup (recommended: Python 3.11)
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
pip install -r requirements-dev.txt

# 2) Run unit tests
pytest -q

# 3) Evaluate (prints Accuracy/F1 and saves confusion matrix)
python scripts/eval.py --data data/fer2013 --weights models/fer_model.pt --img-size 224

# 4) (Optional) Start API
uvicorn src.app.main:app --host 0.0.0.0 --port 8080
# Health:   http://localhost:8080/health
# Metrics:  http://localhost:8080/metrics   (Prometheus format)
# Predict:  POST http://localhost:8080/predict (multipart/form-data: file=@image.jpg)

# 🔬 Corey Leath’s Top 6 Machine Learning Repositories

Welcome to my core portfolio of Machine Learning and AI Engineering projects. These repositories showcase my growing expertise in supervised learning, unsupervised learning, deep learning, cloud pipelines, and quantitative analysis.

Each project below includes the core ML algorithms implemented or suitable for the task, with badges denoting the model type.

---

## 📊 1. LLM Quant Assistant
[![Python](https://img.shields.io/badge/Language-Python-blue)]() [![ML Algorithm](https://img.shields.io/badge/Model-Regression%2C%20KNN%2C%20Boosting-green)]()

**Core ML Algorithms:**
- ✅ Linear Regression (price prediction)
- ✅ K-Nearest Neighbors (pattern similarity)
- ✅ Gradient Boosting (portfolio forecasting)

---

## 😀 2. Facial Emotion Recognition System
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red)]() [![ML Algorithm](https://img.shields.io/badge/Model-CNN%2C%20KMeans%2C%20Boosting-orange)]()

**Core ML Algorithms:**
- ✅ Convolutional Neural Networks (deep learning backbone)
- ✅ K-Means Clustering (unsupervised feature grouping)
- ✅ Gradient Boosting (tabular benchmark)

---

## 🚗 3. AI Vehicle Safety Classifier
[![C++](https://img.shields.io/badge/Language-C++-lightgrey)]() [![ML Algorithm](https://img.shields.io/badge/Model-RandomForest%2C%20KNN%2C%20Boosting-brightgreen)]()

**Core ML Algorithms:**
- ✅ Random Forest (tabular safety classification)
- ✅ K-Nearest Neighbors (incident similarity)
- ✅ Gradient Boosting (boosted safety predictions)

---

## ⚡ 4. Energy-Demand-Forecasting-DevMLOps
[![CI/CD](https://img.shields.io/badge/Workflow-CI%2FCD-blueviolet)]() [![ML Algorithm](https://img.shields.io/badge/Model-Regression%2C%20RandomForest%2C%20Boosting-yellow)]()

**Core ML Algorithms:**
- ✅ Linear Regression (time-based forecasting)
- ✅ Random Forest (multi-variable regression)
- ✅ Gradient Boosting (advanced time-aware modeling)

---

## ☁️ 5. AWS-SageMaker-Snowflake ML Pipeline
[![Cloud](https://img.shields.io/badge/Cloud-AWS%20SageMaker-informational)]() [![ML Algorithm](https://img.shields.io/badge/Model-RandomForest%2C%20Boosting%2C%20KMeans-blue)]()

**Core ML Algorithms:**
- ✅ Random Forest (cloud-optimized classifier)
- ✅ Gradient Boosting (via SageMaker XGBoost)
- ✅ K-Means Clustering (energy user grouping)

---

## 📈 6. Algo-Quant-Backtester
[![Quant](https://img.shields.io/badge/Domain-Quantitative%20Finance-purple)]() [![ML Algorithm](https://img.shields.io/badge/Model-Regression%2C%20KMeans%2C%20KNN%2C%20RandomForest-lightblue)]()

**Core ML Algorithms:**
- ✅ Linear Regression (strategy return prediction)
- ✅ K-Means (cluster strategies)
- ✅ Random Forest (ensemble modeling)
- ✅ K-Nearest Neighbors (market behavior similarity)

---

🔗 Visit my GitHub: [Trojan3877](https://github.com/Trojan3877)


