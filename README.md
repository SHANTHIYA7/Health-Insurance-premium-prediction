# Health-Insurance-premium-prediction
# Health Insurance Charges Prediction

## Project Overview

This project analyzes and predicts individual health insurance charges using demographic, health, lifestyle, and regional factors. The dataset contains information such as age, sex, BMI, number of children, smoking status, region, and insurance charges.

## Objectives

- Explore the structure and distribution of the insurance dataset
- Identify duplicate records and clean the data
- Analyze relationships between customer characteristics and medical charges
- Convert categorical variables into numerical form
- Build and compare multiple linear regression models
- Select the best model based on test-set performance

## Models Used

1. **Model 1:** Uses age as the only predictor
2. **Model 2:** Uses age and BMI
3. **Model 3:** Uses all available encoded features

## Evaluation Metrics

The models are evaluated using:

- Mean Squared Error (MSE)
- R² Score

## Best Model

Model 3, the full-feature Linear Regression model, performs best. It achieves:

- **Test MSE:** 38,940,170
- **Test R²:** 0.772

This means the model explains approximately **77.2% of the variation** in insurance charges. It performs better because it combines age, BMI, children, smoking status, sex, and region instead of relying on only one or two variables.

## Conclusion

The full-feature linear regression model is selected as the final model because it provides the most accurate predictions on unseen data. The results show that lifestyle, health, demographic, and regional factors all contribute to differences in medical insurance charges.
