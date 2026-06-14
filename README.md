# Loan Default Prediction

## Project Overview

This project focuses on predicting loan default risk using machine learning techniques. The dataset contains customer demographic, financial, and credit-related information. The objective is to identify customers who are likely to default on their loans.

---

## Dataset

The dataset contains customer information such as:

- Age
- Gender
- Marital Status
- Education
- Employment Type
- Annual Income
- Savings Balance
- Credit Score
- Credit Card Debt
- Existing EMI
- Monthly Expense
- Past Loans
- Past Defaults
- Loan Default (Target Variable)

---

## Project Workflow

### 1. Data Cleaning
- Removed duplicate records
- Identified missing values
- Created missing value indicator columns

### 2. Missing Value Treatment
Missing values were handled using:

- Group-wise median imputation
- OLS Regression-based analysis
- Customer segmentation using income, age, debt, and experience bands

### 3. Feature Engineering
Created:

- Age Bands
- Experience Bands
- Income Bands
- Debt Bands

Performed one-hot encoding for categorical variables.

### 4. Model Building

#### Logistic Regression
Used as a baseline classification model.

#### XGBoost Classifier
Used to improve prediction performance through gradient boosting.

### 5. Model Evaluation
Models were evaluated using:

- Training Accuracy
- Testing Accuracy

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- XGBoost

---

## Key Learnings

- Data preprocessing and missing value treatment
- Feature engineering techniques
- Regression-based imputation
- Classification modeling
- Model comparison and evaluation



## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature selection
- SHAP explainability
- Deployment using Flask/FastAPI


- Loan-Default-Prediction/
│
├── LoanDefaultPractice.ipynb
├── README.md
├── dataset/
│ └── industry_loan_risk_dataset_100k.csv
│
└── requirements.txt
