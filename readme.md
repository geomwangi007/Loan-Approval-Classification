# Loan Approval Prediction Project
### Overview

This project focuses on predicting loan approval status based on applicant data using machine learning. The dataset includes features like age, income, credit score, employment experience, and loan intent. By leveraging advanced data preprocessing techniques and classification algorithms, the project aims to achieve high accuracy and provide decision support for loan approval.

## Introduction
Loan approval is a critical decision-making process for financial institutions. Automating this process ensures faster and more consistent decisions. This project provides a robust machine learning pipeline that can:

 - Predict loan approval (approved or rejected).

 - Assist human decision-makers by providing confidence levels for predictions.

## Dataset

Source: Kaggle dataset for loan approval classification.

Size: 45,000 entries, 14 features.

Features Include:
Demographic data: person_age, person_gender, person_education.

Financial data: person_income, credit_score.
Loan details: loan_amnt, loan_int_rate, loan_intent.

Historical data: previous_loan_defaults_on_file.

## Models Used

- Logistic Regression

- Decision Tree Classifier

- Random Forest Classifier

- XGBoost Classifier

- LightGBM Classifier

- CatBoost Classifier

- Voting Classifier (Ensemble)

## Results

Best Model: Voting Classifier

Accuracy: 93%

### Key Findings:

Higher credit scores and lower debt-to-income ratios are strong predictors of approval.

Loan intent influences approval, with education loans having higher approval rates.
