# Loan Approval Prediction

This project predicts loan approval status based on customer information such as income, credit history, loan amount, and more. The dataset consists of customer details and loan-related information, and the goal is to classify whether a loan will be approved or not.

## Project Overview

The project involves the following steps:
1. **Exploratory Data Analysis (EDA):** 
   - Analyzing and visualizing the data to understand relationships between features and loan approval status.
   - Performing correlation analysis and generating insights on feature importance.
   
2. **Modeling:**
   - Training multiple machine learning models including Logistic Regression, Random Forest, and Gradient Boosting.
   - Evaluating model performance using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

3. **Prediction:**
   - Making predictions on the test set and generating a CSV file with the loan approval predictions.

## Features

- `person_age`: Age of the individual applying for the loan.
- `person_income`: Income of the individual.
- `loan_amnt`: Amount of the loan applied for.
- `loan_grade`: The grade assigned to the loan.
- `loan_int_rate`: Interest rate on the loan.
- `person_home_ownership`: The home ownership status of the individual.
- `cb_person_cred_hist_length`: Length of credit history of the individual.
- `loan_status`: The target variable indicating whether the loan was approved or not.

## Models Used

- **Logistic Regression:** A baseline linear model used for binary classification.
- **Random Forest Classifier:** An ensemble model for classification that uses multiple decision trees.
- **Gradient Boosting Classifier:** Another ensemble method that builds trees sequentially to improve performance.

## Results

- The Gradient Boosting Classifier achieved the highest accuracy, precision, recall, and F1 score among the models tested.
- The final predictions are saved to a CSV file for further analysis.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Adieltheanalyst/Loan-Approval-Prediction.git
