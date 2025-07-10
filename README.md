# 💼 Capstone Project: AI-Driven Anti-Money Laundering (AML) & Fraud Detection

**Candidate**: Visvanath Balakrishnan  
**Program**: SCTP Associate AI Developer  
**Notebook**: `capstone_eda_aml.ipynb`  
**Submission Date**: July 2025  

---

## 🔍 Problem Statement
This project addresses the detection of **fraudulent financial transactions** using a machine learning approach. It is framed as a **binary classification task**, where each transaction is labeled as either:
- **Fraudulent (1)** or  
- **Legitimate (0)**

---

## 📊 Dataset Overview
- **Source**: Synthetic financial transaction data (PaySim-inspired), modeled on real African mobile money infrastructure.
- **Structure**: ~6 million transactions in raw dataset.
- **Features**: Transaction type, transaction amount, origin/destination account balances, fraud indicators, and AML flags.

---

## 🎯 Project Objectives
- Build a supervised ML model using Logistic Regression to classify transactions.
- Handle **imbalanced data** thoughtfully.
- Implement **explainable AI** (LIME) for interpretability.
- Embed ethical risk and bias awareness in model validation.

---

## 🧠 Techniques Used
- Logistic Regression
- Confusion Matrix, Precision/Recall/F1, ROC-AUC
- Class imbalance handling
- LIME (Local Interpretable Model-agnostic Explanations)
- Data preprocessing, feature engineering

---

## 🔧 Technical Stack
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, scikit-learn, matplotlib, seaborn, joblib, lime

---

## 📁 File Structure

| File | Description |
|------|-------------|
| `capstone_eda_aml.ipynb` | Final Jupyter notebook with full pipeline |
| `fraud_model_logreg.pkl` | Trained Logistic Regression model |
| `lime_explanation_transaction_1.png` | LIME output: Legitimate transaction |
| `lime_explanation_transaction_2.png` | LIME output: Fraudulent transaction |
| `lime_explanation_transaction_3.png` | LIME output: Borderline case |
| `README.md` | This documentation file |
| `requirements.txt` | Dependency list for reproducibility |

---

## ✅ Capstone Phases Completion

| Phase | Description | Status |
|-------|-------------|--------|
| Phase 1 | Problem framing, dataset selection | ✅ |
| Phase 2 | Data cleaning, encoding, EDA | ✅ |
| Phase 3 | Model training, tuning | ✅ |
| Phase 4 | Evaluation & metrics | ✅ |
| Phase 5 | Explainability with LIME | ✅ |
| Phase 6 | Final deliverables | ✅ |

---

## 📌 Notes
- All visuals are exported and embedded.
- Notebook runs cleanly from top to bottom.
- Ethical comments and class imbalance logic are included.
- Modular structure for easy GitHub viewing.

---

## 🔚 End of README