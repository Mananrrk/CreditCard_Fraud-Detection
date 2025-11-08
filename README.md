# 💳 Credit Card Fraud Detection using Machine Learning

## 📘 Overview
This project detects fraudulent credit card transactions using **XGBoost**, a powerful gradient boosting algorithm. It addresses the challenge of **imbalanced datasets** — where only a small fraction of transactions are fraudulent — and aims to accurately identify fraudulent activities while minimizing false alarms.

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:**  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `imblearn`, `shap`

---

## 🚀 Project Workflow
1. **Data Preprocessing** – Cleaning, scaling, and preparing the dataset.  
2. **Imbalance Handling** – Oversampling or undersampling to balance classes.  
3. **Model Training** – Using XGBoost Classifier in a pipeline with StandardScaler.  
4. **Hyperparameter Tuning** – Optimized with GridSearchCV.  
5. **Evaluation** – Metrics: ROC-AUC, PR-AUC, Confusion Matrix, Classification Report.  
6. **Explainability** – SHAP used to interpret model predictions and feature importance.

---

## 📊 Results
- **Tuned Precision-Recall AUC:** 0.84  
- **Model:** XGBoost Classifier  
- Demonstrates strong fraud detection performance with minimal false positives.

---

## 🔍 Visualizations
- ROC Curve  
- Precision-Recall Curve  
- Confusion Matrix  
- SHAP Summary Plot  

---

## 🧠 Key Learnings
- Dealing with **imbalanced datasets**.  
- Building a **complete ML pipeline** from preprocessing to evaluation.  
- Applying **model interpretability** with SHAP.  
- Fine-tuning parameters to boost detection accuracy.

---

## 📂 Dataset
Dataset used: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

Contains anonymized European card transactions from September 2013.

---

## 👤 Author

**Manan Goyal**  
🔗 [GitHub](https://github.com/MananRRK)  
📧 mananmlzs@gmail.com  
📞 +91-7895296561

