# 🧬 Disease Prediction Model - CodeAlpha Internship

This project predicts whether a patient is likely to have a disease (e.g., breast cancer) using structured medical data. Built as part of the **CodeAlpha Machine Learning Internship**.

---

## 🚀 Project Overview

- **Goal:** Classify disease presence based on patient attributes.
- **Dataset:** Breast Cancer Wisconsin Dataset (UCI ML Repository, via sklearn)
- **Models Used:** Logistic Regression, Random Forest, XGBoost
- **Evaluation:** Accuracy, Precision, Recall, F1-Score, ROC-AUC

---

## 🧪 Features Used

Examples of features:
- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- Worst smoothness
- ... and more (30 total features)

---

## ⚙️ ML Workflow

1. Load breast cancer dataset from `sklearn.datasets`
2. Scale data using StandardScaler
3. Train classification models
4. Evaluate using classification report and ROC-AUC
5. Plot ROC Curve for visual comparison

---

## 📉 ROC Curve

*(Optional - Insert your ROC Curve image)*

---

## ✅ Results

All models performed well, especially **XGBoost** with a high ROC-AUC score and accuracy.

---
