# Telecom_Customer_Churn : 

## 📊Project Overview
This project aims to utilize unsupervised Binary Classification Machine Learning models to predict customer churn behavior. The aim is to identify key factors contributing to customer attrition and build predictinve models accurately classifiy weather a customer is likely to churn. 

## 🧾Dataset Description
* The dataset contains information about:
  *  customers who left a ficiticious telecommunication compnay within past month - this column is denoted as "Churn".
  *  Demographic Information about customer, gender, age range, and if they have partners and dependents.
  *  Services each customer has signed up for :  phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
  *  Customer account information such as :  how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges.
  *  The dataset contains 21 columns and 7043 rows and obtained from the follwing Kaggle Link:[https://www.kaggle.com/datasets/blastchar/telco-customer-churn](url).

 ## 🧠 Methodology (Notebook Description)
 The note books follows a complete data analysis and modelling pipeline, including: 
 1. Exploratory Data Analysis (EDA) - Visualized key trends and relationships using **pandas and matplotlib **.
 2. Data Cleaning  - **ensuring data consistency, handling missing values and standerdizing column formatting** for training/ test split to be fitted by ML Models.
 3. Model Training – Built and compared multiple binary classification models:

      * XGBoost Classifier 
      * AdaBoost Classifier
      * Support Vector Classifier (SVC) 
      * Random Forest Classifier (RFC)

 4.  Model Evaluation – Evaluated models using accuracy and precision metrics averaged across 50 random states.
 5. Hyperparameter Optimization – Applied **Optuna** to fine-tune the Random Forest model, achieving a best accuracy of **85%**.


