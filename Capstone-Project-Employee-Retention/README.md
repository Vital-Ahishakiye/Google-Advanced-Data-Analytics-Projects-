# Capstone Project: Employee Retention Prediction

## Scenario
At Salifort Motors, employee turnover—both voluntary resignations and terminations—has become a growing concern. The company invests heavily in recruiting, training, and upskilling employees, and high turnover incurs significant financial costs. The leadership team wants to better understand why employees are leaving and develop strategies to improve retention.

To address this, the Human Resources department conducted a survey capturing various factors that might influence employee turnover, such as job title, department, number of projects, average monthly hours, and more. Your task, as the data analysis specialist, is to analyze this data and build a predictive model that forecasts whether an employee will leave the company.

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

