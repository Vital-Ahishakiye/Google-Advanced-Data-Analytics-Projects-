# Project 5: Taxi Fare Prediction Using Multiple Linear Regression

## Overview
In this project, I built and evaluated a **Multiple Linear Regression (MLR)** model to predict taxi fares based on various features in the New York City Taxi and Limousine Commission (TLC) dataset. The aim was to create an interpretable model that provides accurate fare predictions by leveraging key trip-related variables.

## Objective
The objectives of this project are to:
1. Develop a Multiple Linear Regression model to predict taxi fares.
2. Evaluate the performance of the MLR model using metrics such as RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R² score.
3. Interpret the model coefficients to understand the influence of key variables on fare amount.

### Key Features Used:
- **Trip Distance**: The distance of the trip in miles.
- **Passenger Count**: Number of passengers in the taxi.
- **Pickup Location** and **Drop-off Location**: Taxi zones in NYC.
- **Time of Day**: Pickup time, which captures fare surcharges during rush hour or overnight.

## Methodology
### Steps:
1. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Transformed categorical variables (like pickup/drop-off locations) into numerical values using one-hot encoding.
   
2. **Modeling**:
   - Developed a Multiple Linear Regression model with the following formula:
     \[
     \text{Fare Amount} = \beta_0 + \beta_1(\text{Trip Distance}) + \beta_2(\text{Passenger Count}) + \beta_3(\text{Pickup Location}) + \ldots
     \]
   
3. **Evaluation**:
   - Evaluated the model using cross-validation and the following metrics:
     - **RMSE**: Measures the average error in fare predictions.
     - **MAE**: Captures the absolute difference between predicted and actual fare amounts.
     - **R² Score**: Explains the proportion of variance in the fare that is predictable from the features.

4. **Model Interpretation**:
   - Analyzed the model coefficients to understand the impact of features like trip distance and pickup location on fare amount.
