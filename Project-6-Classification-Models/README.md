# Project 6: Predicting Generous Tippers Using Classification Models

## Overview
This project aims to predict whether a taxi passenger will be a **generous tipper** based on features from the New York City Taxi and Limousine Commission (TLC) dataset. The goal is to build and evaluate classification models that can accurately classify passengers into **generous tippers** and **non-generous tippers** based on their trip data.

## Objective
The objectives of this project are to:
1. Develop classification models to predict whether a passenger will give a generous tip (defined as a tip greater than 20% of the fare).
2. Evaluate the models using classification metrics such as accuracy, precision, recall, and F1-score.
3. Identify the most important features that influence tipping behavior.

## Dataset
The dataset contains key trip and fare details, including:
- **Tip Amount** (used to define whether the tip is generous or not).
- **Trip Distance**.
- **Passenger Count**.
- **Payment Type**.
- **Pickup and Drop-off Locations**.
- **Time of Day** (capturing rush hour and overnight trips).

### Target Variable:
- **Generous Tipper**: A binary variable where:
  - `1` = Generous Tipper (tip > 20% of the fare)
  - `0` = Non-Generous Tipper (tip ≤ 20% of the fare)

## Methodology
### Steps:
1. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Created a new target variable `Generous Tipper` based on the tip amount.
   - One-hot encoded categorical variables such as payment type and pickup/drop-off zones.
   
2. **Modeling**:
   - Developed the following classification models:
     1. **Random Forest Classifier**
     2. **Gradient Boosting Classifier**
   
3. **Evaluation**:
   - Evaluated the models using cross-validation and the following metrics:
     - **Accuracy**: Overall correctness of the model.
     - **Precision**: The proportion of positive predictions that were correct.
     - **Recall**: The proportion of actual positives that were correctly identified.
     - **F1-Score**: Harmonic mean of precision and recall.

4. **Feature Importance**:
   - Analyzed the importance of features like payment type and trip distance in predicting generous tippers.
