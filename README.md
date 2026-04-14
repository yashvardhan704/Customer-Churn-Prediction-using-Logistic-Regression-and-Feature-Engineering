# 📊 Customer Churn Prediction using Logistic Regression

## 🧠 Project Overview

This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave a telecom service based on demographic, account, and service-related features.

We use **Logistic Regression** as the primary model along with feature engineering, preprocessing, and model evaluation techniques.

---

## 📁 Dataset

- Source: Kaggle – Telco Customer Churn Dataset  
- Records: ~7043 customers  
- Target variable: `Churn` (0 = No, 1 = Yes)

---

## 🎯 Objective

To build a binary classification model that predicts whether a customer will churn or not.

---

## ⚙️ Workflow

1. Data Cleaning  
2. Handling Missing Values  
3. Exploratory Data Analysis (EDA)  
4. Feature Encoding (One-Hot Encoding)  
5. Feature Scaling (Standardization)  
6. Train-Test Split  
7. Logistic Regression Model Training  
8. Feature Importance Analysis  
9. Model Evaluation  

---

## 🧪 Machine Learning Model

### Logistic Regression

Logistic Regression is used for binary classification problems. It estimates the probability of churn using a sigmoid function.

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Score
- Confusion Matrix

---

## 📈 Results

- Accuracy: ~0.79  
- ROC-AUC Score: ~0.75  
- Improved recall using class balancing techniques  

---

## 🔍 Key Insights

- Customers with **low tenure** are more likely to churn  
- **Month-to-month contracts** significantly increase churn probability  
- **Fiber optic users** show higher churn rates  
- **Electronic check payment method** is strongly associated with churn  
- Longer contracts reduce churn risk  

---


## 🧠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🚀 How to Run

```bash
git clone https://github.com/yashvardhan704/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
