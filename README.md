# 📉 Telecom Customer Churn Prediction App

This project aims to predict customer churn in the telecom industry using a machine learning model and provide an interactive interface via a **Streamlit** web application. The tool enables business users to input customer information and instantly see the likelihood of churn, helping telecom companies take proactive retention actions.


## 🚀 Project Overview

Churn prediction is a critical aspect of customer retention strategies in the telecom industry. This project includes:

- 📊 Exploratory Data Analysis (EDA)
- ⚙️ Preprocessing and Feature Engineering
- 🧠 Model Training and Evaluation
- 🌐 Deployment of a Streamlit Web App for Real-Time Prediction


## 📂 Dataset Overview

This dataset provides a comprehensive view of customer behavior and churn in the telecom industry. It includes detailed information on customer demographics, service usage, and key indicators that are critical for analyzing customer retention and churn.

### 🔑 Key Features

| Column Name       | Description                                                       |
|-------------------|-------------------------------------------------------------------|
| `CustomerID`      | Unique identifier for each customer                               |
| `Age`             | Age of the customer                                               |
| `Gender`          | Gender of the customer (Male/Female)                              |
| `Tenure`          | Number of months the customer has stayed                          |
| `MonthlyCharges`  | Monthly service charges                                           |
| `ContractType`    | Type of contract (Month-to-Month, One-Year, Two-Year)             |
| `InternetService` | Internet service type (DSL, Fiber Optic, None)                    |
| `TechSupport`     | Availability of tech support (Yes/No)                             |
| `TotalCharges`    | Total amount billed to the customer                               |
| `Churn`           | Target variable (Yes/No) indicating whether the customer churned  |


## 🎯 Objective & Applications

### 🎯 Objective

This dataset is designed to explore the key factors influencing customer churn and retention in the telecom industry. It is ideal for developing predictive models to identify at-risk customers and understand the dynamics behind customer turnover.

Key analytical goals include:

- Identifying patterns in customer demographics, contract types, and service usage that contribute to churn.
- Understanding the drivers behind customer decisions to stay or leave.
- Enabling data-driven strategies to reduce churn and improve customer loyalty.

### 💡 Applications

- **🔮 Churn Prediction**: Train machine learning models to predict which customers are likely to churn based on service usage and demographic variables.
- **👥 Customer Segmentation**: Segment the customer base to identify behavioral patterns and target retention strategies more effectively.
- **📈 Trend Analysis**: Examine trends in tenure, monthly charges, and contract types to discover actionable insights.
- **🧰 Feature Engineering**: Use domain knowledge to create new features that improve model performance and interpretability.


## 🧠 Model

A classification model such as **Logistic Regression**, **Random Forest**, **SVM**, or **XGBoost** is trained on historical customer data to predict the likelihood of churn.


## 🌐 Web App Demo

The **Streamlit** app allows users to input customer attributes and get a real-time churn prediction.

➡️ Enter details such as age, tenure, monthly charges, contract type, and more — and instantly see whether the model predicts the customer is likely to churn.





