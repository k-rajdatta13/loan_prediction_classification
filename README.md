# 🚀 Loan Approval Prediction

## 📌 Overview
This project builds a **machine learning model** to predict **loan approval** for a financial institution. The goal is to automate loan eligibility decisions based on applicant details such as income, credit history, loan amount, and other demographic factors.

## 🏦 Business Problem
Dream Housing Finance Company wants an automated system that predicts whether a loan should be **approved (Y) or not approved (N)** based on key applicant details. This will help streamline the loan approval process, reduce risks, and improve efficiency.

## 🎯 Problem Statement
This is a **binary classification problem**, where the target variable is **Loan_Status (Y/N)**. The key features used for prediction include:

- **Demographic Factors**: Gender, Marital Status, Education, Dependents  
- **Financial Information**: Applicant & Co-applicant Income, Loan Amount, Loan Term  
- **Credit History**: Past repayment behavior  

## 📊 Data Collection
- Dataset obtained from **Analytics Vidhya Hackathon**  
- **614 records** with **13 feature columns**  

## 🔍 Exploratory Data Analysis (EDA)
The notebook includes a detailed EDA:
- ✔ **Univariate Analysis** (Histograms, Box Plots)  
- ✔ **Bivariate Analysis** (Scatter Plots, Heatmaps)  
- ✔ **Missing Value Handling**  
- ✔ **Outlier Detection**  

## 🏗️ Machine Learning Models Used
The notebook experiments with:
- ✅ **Logistic Regression**  
- ✅ **Decision Tree Classifier**  
- ✅ **Random Forest Classifier**  
- ✅ **Naive Bayes Classifier**  

## 📌 Key Findings
- **Credit History** is the strongest predictor of loan approval  
- **Higher Income** improves loan approval chances  
- **Lower Loan Amounts** increase the likelihood of approval  
- **Feature Selection & Engineering** improve model performance  

## 🛠️ Technologies Used
- **Python**  
- **Pandas, NumPy** (Data Handling)  
- **Matplotlib, Seaborn** (Visualization)  
- **Scikit-Learn** (Machine Learning)  

