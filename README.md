

<div align="center">

# 💳 Credit Card Fraud Detection

### An End-to-End Machine Learning Pipeline for Detecting Fraudulent Transactions

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Viz-11557C?style=flat-square)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Viz-4C72B0?style=flat-square)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-Educational-lightgrey?style=flat-square)]()

</div>

---

## 📖 Overview

The growth of e-commerce and digital payments has driven a corresponding rise in online purchases — and, alongside it, payment fraud. This costs the global economy **tens of billions of dollars annually**, driven largely by online transactions and remote (card-not-present) payments.

> This project builds a full end-to-end machine learning pipeline to detect fraudulent credit card transactions, using a well-known benchmark dataset.

---

## 📊 Key Fraud Trends

| Trend | Description |
|---|---|
| 🖥️ **CNP Dominance** | Online shopping and digital channels remain the primary vector for unauthorized charges |
| 🌍 **Geographic Impact** | The US accounts for over **38%** of global card fraud losses, followed by Western Europe and Asia |
| 🎭 **Evolving Tactics** | Criminals are shifting toward automated, industrial-scale attacks, proxy wallets, and social engineering |

---

## 🗂️ Dataset

**Source:** [Credit Card Fraud Detection (ULB)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) — Kaggle

> ⚠️ **Disclaimer:** This project uses a public dataset sourced from Kaggle (originally released by the Machine Learning Group at ULB). All rights to the raw data belong to its original creators. This project is for educational and portfolio purposes only and is **not intended for production fraud detection use** without further validation, compliance review, and access to live transaction data.

---

## 🔁 Project Workflow

```
📦 Load Libraries  →  📥 Load Dataset  →  🔍 Initial Inspection
        ↓
🧹 Data Cleaning  →  📈 EDA  →  🤖 Model Training
        ↓
✅ Evaluation & Validation  →  🚀 Deployment
```

| Step | Description |
|---|---|
| 1️⃣ Load Libraries | Import all required packages |
| 2️⃣ Load Dataset | Read the raw data into memory |
| 3️⃣ Initial Inspection | Shape, dtypes, missing values, class balance |
| 4️⃣ Data Cleaning | Handle missing values, duplicates, inconsistencies |
| 5️⃣ EDA | Visualize distributions, correlations, and class imbalance |
| 6️⃣ Model Training | Fit candidate classification models |
| 7️⃣ Evaluation & Validation | Assess performance on imbalanced data |
| 8️⃣ Deployment | Package and serve the trained model |

---

## 🛠️ Tools & Tech Stack

<div align="center">

| Category | Tools |
|---|---|
| 🐍 **Language** | Python |
| 🧮 **Data Manipulation** | pandas, NumPy |
| 📊 **Visualization** | Matplotlib, Seaborn |
| 🤖 **Modeling** | scikit-learn |
| 🚀 **Deployment** | Flask / FastAPI, Docker, Render |

</div>

---

## 📁 Project Structure

```
credit-card-fraud-detection/
├── data/               # raw and processed data (not committed)
├── notebooks/          # EDA and experimentation notebooks
├── src/                # reusable pipeline code
├── models/             # saved/trained models
├── app/                # deployment app (API/service)
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup

```bash
git clone <your-repo-url>
cd credit-card-fraud-detection
pip install -r requirements.txt
```

---

## 📜 License

This project is released for educational purposes. The underlying dataset remains subject to its original Kaggle license terms.

<div align="center">

Made with ☕ and curiosity by **Jamin**

</div>
