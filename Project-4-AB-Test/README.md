# Project 4: A/B Test on Tipping Behavior

## Overview
This project focuses on conducting an A/B test to determine whether customers who use credit cards tip more than those who pay with cash. The goal is to use statistical testing to validate whether there's a significant difference in tipping behavior between the two payment methods.

## Objective
The primary objective of this A/B test is to:
1. Compare the tipping behavior of credit card users with cash payers.
2. Determine if the difference in tipping amount is statistically significant.

## Hypothesis
- **Null Hypothesis (H₀)**: There is no difference in the average tip amount between customers who pay with credit cards and those who pay with cash.
- **Alternative Hypothesis (H₁)**: Customers who pay with credit cards tip more than those who pay with cash.

## Methodology
- **Test Type**: Two-sample t-test for the difference in means.
- **Dataset**: TLC taxi data including fields for payment method and tip amount.
- **Significance Level (α)**: 0.05 (5%)

### Steps:
1. **Data Cleaning**: Removed records with missing or incorrect values for tip amount and payment method.
2. **Split Data**: Grouped the data based on payment type (`credit card` vs. `cash`).
3. **T-test**: Conducted a two-sample t-test to compare the average tips for both groups.
4. **Result Interpretation**: Analyzed the p-value to determine whether to reject the null hypothesis.
