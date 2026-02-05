# Bank Customer Churn Analysis 📉

## Overview
This project focuses on analyzing bank customer data to understand the factors that contribute to customer churn. The goal is to identify patterns and behaviors that indicate why customers leave the bank and to provide actionable insights for improving customer retention.

This analysis simulates a real-world business scenario where data is used to support strategic decision-making.

---

## Business Problem
Customer churn is a major challenge for banks, as acquiring new customers is more expensive than retaining existing ones.

The bank wants to:
- Identify which customers are more likely to churn.
- Understand the main drivers behind customer churn.
- Use data insights to improve retention strategies.

---

## Dataset
Source: Bank Customer Churn Dataset (Kaggle)  
Records: 10,000 customer records  

The dataset includes:
- Customer demographics (Age, Gender, Geography)
- Financial information (Credit Score, Balance, Salary)
- Banking behavior (Tenure, Products, Activity status)
- Target variable: `Exited` (1 = churned, 0 = retained)

---

## Objectives
The main objectives of this analysis are:
- To measure the overall churn rate.
- To identify key factors influencing churn.
- To compare churned vs retained customers.
- To build insights that support customer retention strategies.

---

## Tools & Technologies
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook
- scikit-learn (for modeling)

---

## Project Workflow
The project follows these steps:

1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering  
5. Data visualization  
6. (Optional) Predictive modeling  
7. Insight generation  
8. Business recommendations  

---

## Key Analysis Performed
- Churn rate calculation
- Churn analysis by:
  - Geography
  - Gender
  - Age groups
  - Activity status
- Correlation analysis between features
- Visualization of churn patterns
- Logistic Regression model for churn prediction

---

## Key Insights
- Inactivity is the biggest driver: inactive members churn much more than active ones.
- Geography matters: Spain has low churn; France and Germany have higher churn and larger volume.
- Demographics & products matter: females show higher churn; credit-card ownership signals engagement but also risk.

---

## Business Recommendations
- Re‑engage inactive members with a focused pilot (emails + incentives).
- Run targeted retention tests in high‑churn regions (France/Germany).
- Create female‑focused messaging and product incentives tied to activity (e.g., rewards).


