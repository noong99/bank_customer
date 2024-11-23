# **Project** <br/>
## 1. Overview
- Project Goal
  - Goal: Develop data-driven promotional strategies to attract bank deposits
  - Notebook: bank_customer.ipynb
  
## 2. Data
  - data_test.csv : test dataset
  - data_train.csv : training dataset

## 3. Project Description
- Explanatory Variables
  - Customer-related information: Age, Job, Marital, Education, Default, Housing, Loan
  - Current telemarketing campaign details: Contact, Month, Day_of_week
  - Additional information: Campaign, Pdays, Previous, Poutcome
  - Socio-economic variables: emp.var.rate, cons.price.idx, cons.conf.idx
- Response Variable
  - Whether a customer deposits money in the bank after seeing advertisements (yes/no)

- Modeling
  - Logistic Regression
  - Random Forest
  - XGBoost
  
 - A custom scoring function was created and used as an evaluation metric

## 4. Conclusion
- The tuned Random Forest model, which achieved the highest performance, was selected

## 5. Development Environment
- Python
