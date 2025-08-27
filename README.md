# Credit Card Default Prediction

This project predicts the likelihood of credit card default using the **UCI Credit Card Dataset**.  
The main objective is to assist financial institutions in identifying potential defaulters early, reducing financial risk.

---

## Project Overview
- Performed **data cleaning, preprocessing, and feature engineering** on the dataset.  
- Conducted **exploratory data analysis (EDA)** to understand key drivers of default.  
- Built and compared **Logistic Regression, Random Forest, and XGBoost classifiers**.  
- Evaluated models primarily using **Recall**, since identifying defaulters is more critical than minimizing false positives.  
- Provided insights into **financial & demographic factors** that influence default behavior.  

---

##  Dataset
- Source: [UCI Machine Learning Repository – Default of Credit Card Clients Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)  
- **Size:** 30,000 records × 24 features  
- **Features include:**  
  - Demographics (age, sex, education, marital status)  
  - Credit details (credit limit, bill statement, repayment status)  
  - Payment history (past due payments, default history)  

---

##  Tools & Libraries
- **Languages/Tools:** Python, Jupyter Notebook   

---

## Models Implemented
1. **Logistic Regression**  
2. **Random Forest Classifier**  
3. **XGBoost Classifier**  

---

## Evaluation Metrics
Since predicting defaults is more important than predicting non-defaults, **Recall** was chosen as the primary evaluation metric.  
Other metrics like **Precision, F1-score, and ROC-AUC** were also compared for balanced evaluation.

---

##  Key Insights
- Payment history and past due amounts are strong indicators of default.  
- Higher credit limits generally reduce default probability.  
- Younger clients with inconsistent repayment history have higher default rates.  

---

## 📁 Repository Structure
