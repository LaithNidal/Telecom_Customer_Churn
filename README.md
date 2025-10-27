# Telecom_Customer_Churn
* The dataset contains information about:
  *  customer who left within past month - this column is denoted as "Churn".
  *  Demographic Information about customer, gender, age range, and if they have partners and dependents.
  *  Services each customer has signed up for :  phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
  *  Customer account information such as :  how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges.
  *  The dataset contains 21 columns and 7043 rows and obtained from the follwing Kaggle Link:[https://www.kaggle.com/datasets/blastchar/telco-customer-churn](url).
 
* The notebook goes over the Data Analysis framework of Exploratory Data Exploration where the data is visualizaed using matplotlib as well as pandas for Data Cleaning ensuring there are no discrpencies in the raw data, null values were also accounted for, proper column formatting was also applied as part of the data cleaning process so that the data would be usable in training and fitting of several bianry classification models such as :Random Forest Classifier (RFC), XGB Classifier, Support Vector Classifier (SVC), Adaboost to name a few.
*  The accuracy and precision score for the models were plotted across 50 random states and averaged for each of the models selected.
*  Optuna was then used for Hyperparameter optimization on the RFC model were the best accuracy score obtained was 0.85 or 85 % accuracy. 
