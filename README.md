# 📊 Credit Card Default Prediction  

## 🔍 Overview  
Credit card default prediction is a critical problem in the field of **credit risk management**. Banks and financial institutions face significant losses when customers default on payments. Identifying risky customers in advance allows lenders to design better credit policies and reduce non-performing assets (NPAs).  

In this project, I use the **UCI Credit Card Dataset** to build machine learning models that can **predict the probability of default in the next month**. The dataset contains demographic, financial, and repayment history information for 30,000 clients.  

The workflow includes:  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Scaling  
- Model Training (Logistic Regression, XGBOOST , Random Forest, etc.)  
- Model Evaluation using Accuracy, Precision, Recall, F1-Score, and ROC-AUC    

---

## 📂 Dataset  

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)  
- **Size:** 30,000 rows × 25 columns  
- **Target Variable:**  
  - `default.payment.next.month` → 1 = Default, 0 = No Default  

### Features:  
- **Demographics:** `SEX`, `EDUCATION`, `MARRIAGE`, `AGE`  
- **Credit Limit:** `LIMIT_BAL`  
- **Repayment Status:** `PAY_0` → `PAY_6`  
- **Bill Statements:** `BILL_AMT1` → `BILL_AMT6`  
- **Payments Made:** `PAY_AMT1` → `PAY_AMT6`  
 

---

## ⚙️ Project Workflow  

### 1️⃣ Data Preprocessing  
- Handle categorical variables (SEX, EDUCATION, MARRIAGE)  
- Check for missing values & outliers  
- Standardize features using `StandardScaler`  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Distribution of demographic variables  
- Correlation between repayment history and defaults  
- Boxplots & histograms of bill amounts and payments  
- Heatmap of feature correlations  

### 3️⃣ Modeling  
- Logistic Regression   
- Random Forest Classifier
- XGBOOST   

### 4️⃣ Model Evaluation  
Metrics used:  
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC Curve  

### 5️⃣ Insights  
- Repayment history (`PAY_0`, `PAY_2`, etc.) strongly influences default probability  
- Credit limit (`LIMIT_BAL`) also plays an important role  
- Younger clients showed higher risk compared to older clients  

---



