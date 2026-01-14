# Credit Risk Scoring using Machine Learning

## Problem Statement
The goal of this project is to predict whether a customer is likely to default
on a loan based on financial and demographic features. This helps financial
institutions assess credit risk and make informed lending decisions.

## Dataset
The dataset contains customer-related features such as income, loan amount,
credit history, and other relevant attributes. Data preprocessing and cleaning
were performed before training the models.

## Approach
- Performed data cleaning and preprocessing
- Conducted exploratory data analysis (EDA)
- Applied feature engineering techniques
- Trained multiple models:
  - Decision Tree
  - Random Forest
  - XGBoost
- Evaluated models using accuracy with ROC-AUC
- Selected the best-performing model based on results

## Results
XGBoost achieved the highest accuracy among the tested models and was
chosen as the final model for credit risk prediction.

## Key Learnings
- Importance of comparing multiple models
- Understanding trade-offs between model complexity and performance
- Feature selection significantly impacts model performance
- How the parameter tuning improves the model accuracy

## Future Improvements
- Hyperparameter tuning
- Deploy the model as a REST API
- host in AWS EC2
