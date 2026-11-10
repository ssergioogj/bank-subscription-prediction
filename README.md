# Bank Term Deposit Subscription Predictor

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/Library-scikit--learn-F7931E.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An end-to-end Machine Learning pipeline designed to predict whether a client will subscribe to a bank term deposit based on direct telemarketing campaign data.

---

## 📌 Overview

The objective of this project is to build and evaluate classification models on tabular marketing data, addressing severe class imbalance and optimizing decision thresholds to maximize campaign conversion efficiency.

### Pipeline Highlights
- **Exploratory Data Analysis (EDA):** Feature distributions, outlier detection, and correlation analysis.
- **Preprocessing:** Categorical encoding (One-Hot / Target), missing value handling, and robust feature scaling.
- **Imbalance Handling:** Evaluates techniques such as SMOTE and class-weight balancing.
- **Models Evaluated:** Logistic Regression, Random Forest, and Gradient Boosted Trees (XGBoost / LightGBM).
- **Evaluation Metrics:** PR-AUC, ROC-AUC, F1-Score, and precision-recall trade-off analys
