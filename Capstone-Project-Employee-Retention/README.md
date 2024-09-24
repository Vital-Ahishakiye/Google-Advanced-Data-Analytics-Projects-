# Capstone Project: Employee Retention Prediction

## Overview
This capstone project focuses on building and evaluating machine learning models to predict employee retention at **Salifort Motors**. The goal is to help the company understand the factors influencing employee churn and provide insights into how they can improve retention rates.

## Objective
The objectives of this project are to:
1. Develop machine learning models to predict whether an employee is likely to leave the company (churn).
2. Evaluate the models using classification metrics such as accuracy, precision, recall, and F1-score.
3. Provide actionable insights to improve employee retention based on the model’s output.

## Dataset
The dataset contains employee information such as:
- **Employee ID** (anonymized)
- **Age**
- **Department**
- **Job Role**
- **Monthly Salary**
- **Job Satisfaction** (1-5 scale)
- **Years at Company**
- **Attrition** (Target Variable: whether the employee left the company or not)

### Target Variable:
- **Attrition**: Binary classification where:
  - `1` = Employee has left the company (churn)
  - `0` = Employee has stayed with the company.

## Methodology
### Steps:
1. **Data Preprocessing**:
   - Cleaned the dataset by handling missing values and outliers.
   - Encoded categorical features such as department and job role.
   
2. **Modeling**:
   - Developed the following models:
     1. **Logistic Regression**: A baseline model for predicting attrition.
     2. **Decision Tree Classifier**: A tree-based model that offers interpretability.
     3. **Random Forest Classifier**: An ensemble model to capture more complex patterns.
     4. **Gradient Boosting Classifier**: A powerful tree-based model for enhanced accuracy.
   
3. **Evaluation**:
   - Used cross-validation to evaluate the models and the following metrics:
     - **Accuracy**: How often the model correctly predicts churn.
     - **Precision**: Proportion of correctly predicted churn cases out of all predicted churns.
     - **Recall**: Proportion of actual churns that were correctly predicted.
     - **F1-Score**: Harmonic mean of precision and recall.

4. **Feature Importance**:
   - Analyzed the importance of features such as job satisfaction, salary, and years at the company in predicting employee churn.

