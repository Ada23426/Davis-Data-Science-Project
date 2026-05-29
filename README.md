# Davis Data Science Project

## Overview

This project explores how demographic and health-related factors may affect insurance charges using statistical modeling. We used a dataset that contains information such as sex, BMI, smoking status, region, number of children and age and build predictive models to estimate the individual insurance premiums and also evaluate which variables have the strongest impact on costs. 

Our analysis focused on data preprocessing, exploratory data analysis (EDA), regression modeling, F-tests and cross-validation, which were used to measure prediction accuracy and model performance. 

## Objectives

- Predict insurance premiums based on demographic and health-related variables
- Identify variables that have the strongest influence on costs
- Evaluate model using statistical metrics
- Assess whether gender impacts charges

## Results & Conclusion 

Our results showed that smoking status was the strongest predictor for insurance charges while gender and region showed little significance. 

The final model achieved:
- Cross Validation $R^2$: 0.75
- Unseen test data $R^2$: 0.72
- Cross-validation RMSE: $6,067
- Unseen test data RMSE: $6,354

This tells us that we can use demographics and health related factors to reasonably predict costs. Overall, this project demonstrated the usage of statistical learning, regression analysis and predictive modeling techniques in healthcare analytics. 
