# Intelligent Loan Analytics and Prediction System using Machine Learning

## Project Overview

The **Intelligent Loan Analytics and Prediction System** is an end-to-end Machine Learning project built using the **HDFC Loan Dataset**. The project simulates real-world banking workflows by applying machine learning techniques for loan approval prediction, loan default risk analysis, and loan amount prediction.

The objective of this project is to analyze customer financial information and build predictive models that support data-driven lending decisions.

---

## Problem Statements

This project addresses three use cases:

### 1. Loan Approval Prediction (Classification)

Predict whether a customer's loan application will be approved or rejected.

**Target Variable:** `Loan_Status`

---

### 2. Loan Default Risk Analysis (Classification)

Identify customers with a high probability of loan default based on their financial behavior and historical records.

**Derived Target Variable:** `High_Risk`

---

### 3. Loan Amount Prediction (Regression)

Predict the loan amount a customer is eligible for based on demographic and financial factors.

**Target Variable:** `Loan_Amount`

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Project Workflow

### 1. Data Understanding

- Dataset inspection
- Missing value analysis
- Duplicate checking
- Data type verification
- Statistical summary

### 2. Exploratory Data Analysis (EDA)

- Loan approval distribution
- Income distribution
- Correlation analysis
- CIBIL score analysis
- Loan trends visualization

### 3. Data Preprocessing

- Missing value handling
- Categorical encoding
- Feature scaling
- Feature selection
- Train-test split

### 4. Model Building

Multiple machine learning algorithms were implemented and compared.

#### Classification Models

- Logistic Regression
- Decision Tree
- Random Forest

#### Regression Models

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 5. Hyperparameter Tuning

- GridSearchCV was used to optimize model performance.

### 6. Model Evaluation

#### Classification Metrics

- Accuracy
- Precision
- Recall
- F1 Score

#### Regression Metrics

- MAE
- MSE
- RMSE
- R² Score

---

## Project Structure

```text
Intelligent_Loan_Analytics_and_Prediction_System/
│
├── datasets/
│   └── preprocessed_hdfc_loan_data.csv
│
├── notebooks/
│   ├── eda.ipynb
│   ├── loan_approval_prediction.ipynb
│   ├── loan_default_risk_analysis.ipynb
│   └── loan_amount_prediction.ipynb
│
├── models/
│   ├── loan_approval_model.pkl
│   ├── loan_default_risk_model.pkl
│   └── loan_amount_prediction_model.pkl
│
├── requirements.txt
└── README.md
```

---

## Key Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques for real-world datasets.
- Exploratory Data Analysis using visualization libraries.
- Building classification and regression models.
- Comparing multiple machine learning algorithms.
- Evaluating models using appropriate performance metrics.
- Applying GridSearchCV for hyperparameter tuning.
- Understanding feature importance.
- Saving trained models using Joblib.
- Building complete end-to-end machine learning workflows.

---

## Real-World Applications

- Automated loan approval systems
- Credit risk assessment
- Banking analytics
- Customer financial profiling
- AI-driven lending systems

---

## Author

**Sowmya Sri Yenumula**

Machine Learning Enthusiast | Python Developer | Data Science Learner
