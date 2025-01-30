
# 📉 Customer Churn Prediction: Machine Learning for Retention Strategy

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2.2-green)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7.6-orange)
![LightGBM](https://img.shields.io/badge/LightGBM-3.3.5-yellow)

Predict customer churn using machine learning to identify at-risk clients and optimize retention strategies. Achieved **79.6% accuracy** with XGBoost and LightGBM.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🚀 Project Overview
**Goal**: Predict customer churn risk using demographic and transactional data to enable proactive retention efforts.  
**Dataset**: 10,000 records with 14 features (e.g., `CreditScore`, `Geography`, `Balance`).  
**Impact**: Demonstrates how ML can directly reduce attrition and stabilize revenue streams.

---

## 🔑 Key Features
### **Data Preprocessing**
- Handled categorical variables with `LabelEncoder` and `OneHotEncoder`.
- Engineered features like `Tenure` and `NumOfProducts` for model relevance.

### **Models & Evaluation**
- **Algorithms**: XGBoost (`n_estimators=200`, `max_depth=4`) and LightGBM.
- **Metrics**: 79.6% accuracy, confusion matrices, and 10-fold cross-validation.
- **Optimization**: Tuned hyperparameters to minimize overfitting (train/test score: ~79.6%).

### **Tools**
- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.

---

📊 Results
Model Performance
Metric	XGBoost	LightGBM
Accuracy	79.6%	79.6%
Precision	0.72	0.71
Recall	0.63	0.62
