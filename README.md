# 🏦 Loan Approval Prediction using Machine Learning

A Machine Learning classification project that predicts whether a loan application will be **Approved** or **Rejected** based on applicant demographic, income, loan, and credit-history information.

The project implements a complete machine learning pipeline including data preprocessing, exploratory data analysis, feature engineering, categorical encoding, class-imbalance handling, model training, and performance evaluation.

---

## 📌 Project Overview

Loan approval is an important decision in the banking and financial sector. Manual evaluation of loan applications can be time-consuming and difficult to perform consistently at scale.

This project uses historical loan application data to build a supervised machine learning classification system that can predict the loan approval status of an applicant.

The project compares three classification algorithms:

- Logistic Regression
- Decision Tree
- Random Forest

Among the evaluated models, **Random Forest achieved 87.68% test accuracy** on the resampled test dataset.

---

## 🎯 Objectives

- Analyze historical loan application data.
- Clean and preprocess the dataset.
- Handle missing values.
- Perform Exploratory Data Analysis (EDA).
- Identify and handle skewed numerical features.
- Create a `Total_Income` feature.
- Encode categorical variables.
- Handle class imbalance using Random Oversampling.
- Train multiple classification models.
- Compare model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

---

## 📊 Dataset

The project uses the **Loan Prediction Dataset** containing:

- **614 records**
- **13 attributes**

### Main Features

| Feature | Description |
|---|---|
| Loan_ID | Unique loan application identifier |
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Applicant education level |
| Self_Employed | Employment status |
| ApplicantIncome | Applicant's income |
| CoapplicantIncome | Co-applicant's income |
| LoanAmount | Requested loan amount |
| Loan_Amount_Term | Loan repayment term |
| Credit_History | Applicant's credit history |
| Property_Area | Property location |
| Loan_Status | Loan approval status |

### Target Variable

`Loan_Status`

- `Approved`
- `Rejected`

---

## 🔄 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Exploration
     ↓
Missing Value Handling
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Log Transformation
     ↓
Categorical Encoding
     ↓
Class Imbalance Handling
     ↓
Train-Test Split
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Model Comparison
