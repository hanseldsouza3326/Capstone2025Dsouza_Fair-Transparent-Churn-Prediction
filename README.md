# FAIRAI – Fair and Transparent Churn Prediction using Mixture of Experts

![Python](https://img.shields.io/badge/Python-3.9-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

This repository contains the complete codes, datasets and outputs for my capstone project titled the **FAIRAI** system  which is a modular and regulation-aware AI framework designed for **ethical, fair, and explainable churn prediction** in financial services. The goal of this project is to design a regulation-aware churn prediction system that balances accuracy, fairness, explainability, and ethical compliance, especially suited for the Irish financial sector.

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

The **FAIRAI** project aims to bridge the gap between accurate churn prediction, ethical and responsible practices. The solution introduces a hybrid AI system based on a Mixture of Experts (MoE) which integrates traditional models (Logistic Regression, Random Forest, MLP, SVM) through a gating network, and enhances them with specialist modules:

- 🔄 Fairness Optimization using Disparate Impact
- 🔍 Explainability using ELI5 and local feature attribution
- 🛡️ Ethical Auditing using rule-based compliance checks
- 🎯 Reinforcement Learning for dynamic fairness-policy control (With Proper Future Integration) 

---

## 📂 Dataset

- **Source**: [data.gov.ie](https://data.gov.ie)
- **Records**: 615 original + synthetically extended rows
- **Attributes**: Income, Loan Amount, Credit History, Gender, Marital Status, etc.
- **Engineered Features**: EMI, Loan-Income Ratio, Total Income, Ethical Audit Flag

---

## 🧠 Methodology

The end-to-end pipeline consists of:

1. Data Preprocessing & Imputation
2. Feature Engineering
3. Baseline Logistic Regression Model
4. Mixture of Experts (MoE) with 4 expert models
5. Fairness Evaluation & Mitigation Expert
6. Model Explainability Expert via ELI5
7. Rule-Based Ethical Auditing EExpert
8. Reinforcement Learning Expert
9.  Dashboard generation in Tableau

---

## 📊 Experiments & Results

| Model Version                    | Accuracy | F1 Score | ROC-AUC |
|----------------------------------|----------|----------|---------|
| Baseline Logistic Regression     | 86.18%   | 90.81%   | 80.43%  |
| Full MoE System (All Experts)    | 86.18%   | 90.71%   | 79.08%  |

### Fairness Outcomes (Gender Disparate Impact)
- **Baseline:** 0.92  
- **MoE Pre-Fairness:** 0.88  
- **MoE Post-Fairness:** 0.96  

### Governance Audit Outcome
- **Over-Rejections:** 3.2%  
- **Over-Approvals:** 2.5%  
- **Gender Bias Flags:** 1.8%  
- **Overall Compliance:** 94%

---

## 🔍 Explainability and Fairness Insights

- ELI5 explanations show high influence of:
  - Credit History
  - EMI
  - Total Income
- Fairness Expert computes **Disparate Impact**
- Ethical Expert flags non-compliant decisions with logic-based rules

---

## 📊 Dashboard and Audit Logs

[Visit Tableau dashboard] (https://public.tableau.com/app/profile/hansel.joaquim.d.souza/viz/FAIRAI-FairTransparentChurnPrediction/Dashboard1)

---

## 🔮 Limitations and Future Work

- Dataset is synthetically extended
- No access to real employment history
- Reinforcement Learning Expert is under development
- Causal bias detection is not yet implemented

---

## 👥 Contributors

- **Hansel Joaquim Stephen Dsouza** – [Author and Developer]

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.

---

## 🙏 Acknowledgments

- Irish Government Open Data Portal
- GDPR, Equal Status Act, Central Bank of Ireland, Lending & Secured Financial laws, Financial Consumer Protection codes
