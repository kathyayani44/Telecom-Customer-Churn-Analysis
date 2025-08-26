# Telecom-Customer-Churn-Analysis
Telecom Customer Churn Analysis 

## Project Overview
This project aims to analyze a telecom customer dataset to understand the factors influencing customer churn and to build a predictive model that can identify customers at risk of leaving the service. The analysis includes data preprocessing, exploratory data visualization, and the evaluation of multiple machine learning models to find the best-performing one.

--- 

## 🧰 Tech Stack Used
- **Python 3**
- **NumPy** – for numerical operations
- **Pandas** – for data manipulation and analysis
- **Matplotlib** – for data visualization
- **Seaborn** – for advanced plotting and aesthetics
- **Scikit-learn** – For various machine learning tasks like model selection and evaluation
- **XGBoost** – For building the final predictive model
- **Jupyter Notebook** – for interactive coding

---

- ## 📁 Dataset
The analysis is based on the `telecom_customer_churn.csv` dataset, which contains detailed information about a telecom company's customers. The dataset includes:
- **Demographic Information**: Gender, age, marital status, number of dependents, etc.
- **Service Details**: Phone service, internet service type, streaming add-ons, contract type, etc.
- **Billing Information**: Monthly charges, total charges, total revenue, refunds, etc.
- **Churn Status**: A key column indicating if a customer has churned, stayed, or joined.

---

## 🔍 Key Analysis Performed
* **Project Goal:** The project aimed to analyze customer data to identify factors causing churn and build a model to predict which customers are at risk.
* **Data Preparation:** The data was preprocessed by removing irrelevant columns, handling missing values, and converting all features into a numerical format through encoding and scaling.
* **Key Findings from Analysis:** Visualizations revealed that customer churn rates were similar for different genders but significantly higher for single customers compared to married ones.
* **Modeling Approach:** Several machine learning models were tested, and `GridSearchCV` was used to find the best model and optimal parameters.
* **Final Outcome:** The `XGBClassifier` was selected as the best model, achieving an accuracy of `80.64%` in predicting customer churn.

---

## ✅ Results & Insights
- Model Performance: The project successfully built a predictive model for customer churn. The XGBClassifier was identified as the best-performing model, achieving an accuracy of 80.64% on the test dataset.
-Churn by Demographics: Analysis of customer data revealed that churn rates were similar between male and female customers. However, single customers were found to be more likely to churn than married customers.
-Contract Type and Churn: A significant insight was that customers with month-to-month contracts had a much higher churn rate compared to those with one-year or two-year contracts.
