# 🧠 Insurance Price Prediction Model  
### MSc Big Data & Business Intelligence (Distinction, 2020)  
#### by John Uzoukwu | JNUS Associates Ltd  

---

## 💡 Overview

This project demonstrates a supervised machine learning model developed to **predict insurance product prices** using key customer and policy features.  
The model was created as part of my MSc research in *Big Data & Business Intelligence (2020)*, where it achieved a **Distinction**.

The study explored how data-driven models can enhance pricing precision and underwriting efficiency in the insurance sector, integrating analytical rigor with business intelligence principles.

---

## 🧩 Project Objectives

- Build a predictive model for estimating insurance product prices  
- Compare the performance of multiple algorithms (e.g. Linear Regression, Random Forest, XGBoost)  
- Evaluate accuracy, error margins, and business interpretability  
- Recommend data-driven insights for improved risk-based pricing  

---

## ⚙️ Tech Stack

| Category | Tools / Libraries |
|-----------|-------------------|
| Language  | **Python 3.8+** |
| Data      | **Pandas**, **NumPy**, **CSV datasets** |
| Modeling  | **Scikit-Learn**, **XGBoost**, **Statsmodels** |
| Visualization | **Matplotlib**, **Seaborn** |
| Environment | **Jupyter Notebook (.ipynb)** |

---

## 📊 Dataset & Features

- **Customer attributes:** Age, gender, occupation, risk category  
- **Policy variables:** Coverage type, term length, premium range  
- **External factors:** Market rate index, claim frequency, macro indicators  

The dataset was preprocessed, normalized, and encoded for model training and testing.

---

## 🧠 Model Performance Summary

| Metric | Result |
|--------|--------|
| R² Score | **0.93** |
| Mean Absolute Error | **↓ 12% improvement** |
| Cross-Validation | 10-fold |
| Model Used | Random Forest Regressor (final) |

> The model achieved a strong predictive performance, demonstrating the feasibility of using machine learning to support actuarial decision-making and dynamic premium optimization.

---

## 🔍 Key Insights

- Machine learning significantly improves consistency in premium pricing  
- Feature importance identified **risk category**, **claim history**, and **age group** as top predictors  
- The approach provides transparency and scalability across insurance product lines  

---

## 🚀 How to Run the Notebook

```bash
# Clone this repository
git clone https://github.com/<yourusername>/insurance-pricing-ml-model.git
cd insurance-pricing-ml-model

# Open the notebook
jupyter notebook insurance_price_prediction_model.ipynb
