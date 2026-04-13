# 📊 Bankruptcy Prevention

## 🚀 Project Overview

This project predicts whether a company is likely to go bankrupt based on financial and operational risk factors.

## 🎯 Business Objective

To build a classification model that estimates the probability of bankruptcy using structured risk indicators.

---

## 📁 Dataset

* 250 companies
* Features include:

  * Industrial Risk
  * Management Risk
  * Financial Flexibility
  * Credibility
  * Competitiveness
  * Operating Risk

---

## 🔍 Approach

### 1. Exploratory Data Analysis

* Distribution analysis
* Correlation analysis
* Feature relationships

### 2. Feature Engineering

* Created:

  * Total Risk Score
  * Stability Score
* Integrated into pipeline

### 3. Model Building

* Models used:

  * Logistic Regression
  * SVM
  * Random Forest
  * KKN
  * Boosting Models

### 4. Model Selection

* Based on:

  * ROC-AUC (primary metric)
  * Cross-validation
  * Overfitting check

---

## 🏆 Final Model

* Random Forest (Pipeline-based)
* Robust performance with strong generalization

---

## 📈 Evaluation Metrics

* ROC-AUC
* Accuracy
* Cross-validation score

---

## 🧠 Explainability

* SHAP used to interpret feature importance
* Key insights:

  * High competitiveness reduces bankruptcy risk
  * High operational risk increases bankruptcy probability

---

## 🌐 Deployment

* Streamlit web app
* Features:

  * Individual prediction
  * Bulk prediction
  * SQLite-based logging
  * Interactive visualizations

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
streamlit run app/BkPv_app.py
```

---

## 📌 Future Improvements

* Model deployment using FastAPI
* Cloud deployment (AWS Cloud)
* Real-time data integration

---

## 👨‍💻 Author

Sameer Jadhav
