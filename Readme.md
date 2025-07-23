# Customer Churn Prediction Using XGBoost
This project focuses on predicting customer churn using a publicly available dataset from Kaggle. The goal is to identify customers who are likely to discontinue their services in the future, enabling businesses to take proactive retention measures.

## Project Overview
**Dataset:** Customer Churn Dataset (from Kaggle)

**Objective:** Predict whether a customer will churn or not

**Model Used:** XGBoost Classifier

**Achieved Accuracy:** 80%

## Workflow
### Data Preprocessing

Cleaned and wrangled the dataset to handle missing values, encode categorical variables, and scale numerical features.

### Exploratory Data Analysis (EDA)

Performed comprehensive EDA to understand customer behavior and service usage patterns.

Key insights were drawn from visualizations of demographic and service-related features.

### Feature Visualization

Focused on important service features (like internet service, contract type, etc.) and critical customer groups (e.g., tenure-based segmentation, payment methods).

Visualizations helped uncover patterns linked to higher churn probability.

### Modeling with XGBoost

Trained an XGBoost classifier using the processed dataset.

Tuned hyperparameters to improve model performance.

Achieved an accuracy of approximately 80% on the test set.

## Conclusion
This project demonstrates how data-driven approaches can be used to tackle customer retention challenges. The XGBoost model provides a strong baseline for churn prediction, and with further optimization, it can be integrated into business strategies for customer relationship management.