# Credit Card Users Churn Prediction (AIML)

## Overview
This project predicts customer churn for credit card users using machine learning. The goal is to identify customers likely to close their accounts, enabling proactive retention strategies. The analysis leverages the BankChurners dataset, applying supervised learning models to classify churned vs. retained customers.

---

## Goals
- Predict whether a credit card user will churn or remain active  
- Identify key behavioral and financial factors that influence churn  
- Provide interpretable insights for retention strategies  

---

## Methodology

### 1. Data Preprocessing
- Cleaned categorical and numerical features  
- Encoded customer attributes such as card type, transaction behavior, and demographics  
- Handled class imbalance with resampling techniques  

### 2. Model Development
- Evaluated multiple ML models: Logistic Regression, Random Forest, XGBoost  
- Hyperparameter tuning for optimal performance  
- Compared models based on accuracy, precision, recall, and F1-score  

### 3. Evaluation and Insights
- Feature importance analysis to interpret churn drivers  
- Insights into transaction activity, tenure, and card usage patterns  

---

## Repository Structure
```
Credit-Card-Users-Churn-Prediction/
│
├── Credit Card Users Churn Prediction.ipynb # Main notebook
├── Credit Card Users Churn Prediction.html # Exported notebook
├── BankChurners.csv # Dataset
└── README.md # Project documentation
```
---

## Results
- Achieved high classification performance, with models identifying churn with strong precision and recall  
- Top features influencing churn included:  
  - Customer tenure  
  - Total transaction count  
  - Credit limit utilization  
  - Type of credit card  

---

## Notes
- Dataset: BankChurners.csv
- The dataset is included here for reproducibility  

## Notes
- Dataset: BankChurners.csv 
- The dataset is included here for reproducibility  
