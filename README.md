# Credit Risk Assessment 

## Overview

This project predicts borrower credit risk using machine learning techniques. The system analyzes customer demographic, financial, and lending information to classify borrowers into low-risk and high-risk categories, supporting credit decision-making and risk assessment.

## Business Problem

Financial institutions need to evaluate borrower creditworthiness before approving loans. Poor risk assessment can result in increased loan defaults and financial losses.

This project helps identify potential high-risk borrowers by analyzing historical credit data and applying machine learning models.

## Dataset

German Credit Risk Dataset

### Features

* Age
* Sex
* Job
* Housing
* Saving Accounts
* Checking Account
* Credit Amount
* Duration

### Target Variable

* Risk (Good / Bad)

## Project Workflow

### 1. Data Preprocessing

* Missing value handling
* Data cleaning
* Label encoding
* Feature selection

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis
* Risk-based comparisons
* Boxplots and countplots
* Customer behavior analysis

### 3. Model Development

The following models were trained and evaluated:

* Decision Tree
* Random Forest
* Extra Trees
* XGBoost

### 4. Hyperparameter Tuning

GridSearchCV was used to optimize model performance.

## Model Performance

| Model         | Accuracy |
| ------------- | -------- |
| Decision Tree | 58.09%   |
| Random Forest | 61.90%   |
| Extra Trees   | 64.76%   |
| XGBoost       | 67.61%   |

XGBoost achieved the highest accuracy and was selected as the final model.

## Deployment

A Streamlit application was developed to perform real-time credit risk prediction based on borrower information.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Streamlit
* Matplotlib
* Seaborn
* Joblib

## Key Outcomes

* Performed credit risk analysis using borrower demographic and financial attributes.
* Compared multiple machine learning models and selected the best-performing model.
* Built an interactive Streamlit application for real-time risk assessment.
* Applied feature engineering, model evaluation, and hyperparameter tuning techniques.

## Future Improvements

* One-Hot Encoding
* SHAP-based model explainability
* Additional financial risk metrics
* Improved feature engineering
* Enhanced model performance using ensemble techniques

## Author

Leelarani Chigilipalli
