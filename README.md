# 📊 E-Commerce Client Income Prediction

This project focuses on predicting the **Annual Income** of E-Commerce clients using supervised machine learning techniques, primarily **Linear Regression**. The dataset consists of various user attributes, such as session length, time on app, time on website, and membership length, used to model and forecast annual income patterns.

---

## 📌 Objective

To build a regression model that accurately predicts a client's annual income using behavioral and demographic data available in the E-Commerce dataset.

---

## 📂 Dataset

The dataset used is `Ecommerce Customers.csv`, which contains the following key features:

- **Avg. Session Length**
- **Time on App**
- **Time on Website**
- **Length of Membership**
- **Yearly Amount Spent** *(target variable)*

---

## 🛠 Technologies & Libraries

- `Python 3.x`
- `pandas`, `numpy` – data handling
- `matplotlib`, `seaborn` – data visualization
- `scikit-learn` – model training & evaluation
- `scipy` – probability plots & normality checks

---

## 🔍 Workflow Overview

1. **Exploratory Data Analysis**
   - Pair plots, heatmaps, and distribution checks  
2. **Data Preprocessing**
   - Feature selection, train-test splitting  
3. **Model Training**
   - Using `LinearRegression` from `scikit-learn`  
4. **Model Evaluation**
   - R² Score, RMSE, residual analysis, and probability plot  
5. **Assumption Check**
   - Residuals are assessed for normality using QQ-plot  

---

## 📈 Final Output – Residuals Probability Plot

This probability plot checks the normality of the residuals, which is crucial for validating the assumptions of a linear regression model.

![Final Result](HASIL%20AKHIR.png)

---

