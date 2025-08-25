# FAIRAI – Fair and Transparent Churn Prediction using Mixture of Experts

![Python](https://img.shields.io/badge/Python-3.9-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

This repository contains the complete code, dataset and outputs for my capstone project titled the **FAIRAI** system – a modular and regulation-aware AI framework designed for **ethical, fair, and explainable churn prediction** in financial services. The goal of this project is to design a regulation-aware churn prediction system that balances accuracy, fairness, explainability, and ethical compliance, especially suited for the Irish financial sector.

The project uses a real-world government dataset enriched with engineered features, and implements a **Mixture of Experts (MoE)** architecture, integrating fairness optimization, explainable AI, and ethical governance checks. Future integration includes a Reinforcement Learning module to optimize decisions in real-time.

---

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Experiments & Results](#experiments--results)
- [Explainability and Fairness Insights](#explainability-and-fairness-insights)
- [Dashboard and Audit Logs](#dashboard-and-audit-logs)
- [Limitations and Future Work](#limitations-and-future-work)
- [Contributors](#contributors)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 📌 Project Overview

The **FAIRAI** project aims to bridge the gap between accurate churn prediction and responsible AI practices. The solution introduces a hybrid AI system based on a Mixture of Experts (MoE) which integrates traditional models (Logistic Regression, Random Forest, MLP, SVM) through a gating network, and enhances them with specialist modules:

- 🔄 Fairness Optimization using Disparate Impact
- 🔍 Explainability using ELI5 and local feature attribution
- 🛡️ Ethical Auditing using rule-based compliance checks
- 🎯 Future Integration of Reinforcement Learning for dynamic fairness-policy control

---

## 📂 Dataset

- **Source**: [data.gov.ie](https://data.gov.ie)
- **Records**: 615 original + synthetically extended rows
- **Attributes**: Income, Loan Amount, Credit History, Gender, Marital Status, etc.
- **Engineered Features**: EMI, Loan-Income Ratio, Total Income, Ethical Audit Flag
