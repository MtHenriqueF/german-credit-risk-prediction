# German Credit Risk Prediction 🏦📊  

A machine learning project to predict whether a loan applicant is a **"Good"** or **"Bad"** credit risk based on the **German Credit Dataset**.  

## 📌 Overview  
This repository contains:  
- Data preprocessing & exploratory analysis (`german_credit_prediction.ipynb`)  
- Machine learning models for binary classification (Decision tree, random forest, XGBoost, etc.)  
- Model evaluation & performance metrics (F1-score, Precision, Recall, ROC-AUC)  


## 📂 Dataset  
The **German Credit Dataset** contains 1,000 entries with features (mixed categorical & numerical) and a target variable (`Risk` = Good/Bad).  


### Features:

- Age (numeric)
- Sex (text: male, female)
- Job (numeric: 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled)
- Housing (text: own, rent, or free)
- Saving accounts (text - little, moderate, quite rich, rich)
- Checking account (numeric, in DM - Deutsch Mark)
- Credit amount (numeric, in DM)
- Duration (numeric, in month)
- Purpose (text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others)