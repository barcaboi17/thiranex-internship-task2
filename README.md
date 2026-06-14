# 🤖 Predictive Modeling Using Machine Learning
### Thiranex Internship | Task 2
**Intern:** Suraj &nbsp;|&nbsp; **ID:** THX-JUN0526-1465 &nbsp;|&nbsp; **Role:** Data Science Intern

---

## 📌 Project Overview

This project was completed as part of the **Thiranex Data Science Internship (June 2026)**. The goal was to build a machine learning model to predict outcomes based on given data by applying supervised learning algorithms, evaluating model performance, and visualizing results through confusion matrices and ROC curves.

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `predictive_model.ipynb` | Jupyter Notebook with step-by-step ML implementation |
| `1_confusion_matrices.png` | Confusion matrices for all 3 models |
| `2_roc_curves.png` | ROC curves comparison chart |
| `3_metrics_dashboard.png` | Model performance metrics dashboard |
| `4_feature_importance.png` | Top 15 feature importances (Random Forest) |
| `5_cv_scores.png` | 5-Fold Cross Validation scores |
| `README.md` | Project documentation (this file) |

---

## 🗂️ Dataset Description

Breast Cancer Wisconsin Dataset — built into `sklearn.datasets` (no download needed):

| Property | Details |
|----------|---------|
| Samples | 569 records |
| Features | 30 numeric columns |
| Target | 0 = Malignant / 1 = Benign |
| Missing Values | None |
| Source | UCI Machine Learning Repository |

| Column Group | Description |
|---|---|
| Mean Features | mean radius, mean texture, mean perimeter, etc. |
| Error Features | radius error, texture error, perimeter error, etc. |
| Worst Features | worst radius, worst texture, worst perimeter, etc. |
| Target | Tumor classification (Malignant or Benign) |

---

## 🤖 Models Applied

### Three Supervised Learning Algorithms Used:

| Model | Description |
|-------|-------------|
| **Logistic Regression** | Linear model for binary classification |
| **Decision Tree** | Tree-based model with max depth of 5 |
| **Random Forest** | Ensemble of 100 decision trees |

---

## 🧪 Model Training & Evaluation

### Training Setup:
| Step | Details |
|------|---------|
| Train / Test Split | 80% / 20% (455 / 114 samples) |
| Scaling | StandardScaler (mean=0, std=1) |
| Stratified Split | Yes (maintains class balance) |
| Cross Validation | 5-Fold Stratified KFold |

### Results:

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| **Logistic Regression** 🏆 | **98.25%** | 98.61% | 98.61% | 98.61%
