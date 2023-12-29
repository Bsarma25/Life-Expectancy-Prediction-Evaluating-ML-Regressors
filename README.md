# Life Expectancy Prediction Project

## Overview
This project aims to predict life expectancy using socio-economic and health-related factors, leveraging WHO data from 2000 to 2015. The dataset consists of approximately 3000 data points with 22 features.

## Data Preprocessing
Key steps in data preprocessing included:
- Handling null values using a Simple Imputer (median).
- Label encoding categorical variables.
- Splitting the dataset in an 80:20 train-test ratio.
- Normalizing the data.
- Addressing multicollinearity by removing highly correlated features.

## Feature Selection
Feature selection was performed using wrapper methods like forward selection and backward elimination across various models:
- Linear Regression
- Decision Tree
- Random Forest
- Xgboost

## Model Selection and Validation
- Hyperparameter tuning was conducted using GridSearchCV.
- Best performing models: Random Forest and XGBoost with forward selection, achieving an R-squared of ~0.96.

## Conclusion
The project demonstrates the effectiveness of machine learning in predicting life expectancy, with significant implications for healthcare policy and resource planning.
