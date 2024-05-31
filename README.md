# Medical-Insurance-Cost

## Overview
Hospital ABC is a leading healthcare provider aiming to optimize its resource allocation and improve patient care by understanding the factors influencing medical costs for its patients. To facilitate this goal, Hospital ABC has collected a comprehensive dataset containing various attributes related to patients' demographics, lifestyle, health status, and medical expenses.

This repository contains the dataset and code for analyzing the dataset to identify factors influencing medical costs.
Dataset Description
The dataset provided by Hospital ABC contains the following attributes:

Age: Age of the patient.
Gender: Gender of the patient (Male/Female).
BMI: Body Mass Index of the patient.
Smoking Status: Smoking status of the patient (Smoker/Non-Smoker).
Region: Geographic region of the patient.
Occupation: Occupation of the patient.
Exercise Frequency: Frequency of exercise of the patient.
Chronic Conditions: Any chronic conditions the patient may have.
Medical Expenses: The medical expenses incurred by the patient.
Analysis
We aim to perform the following analyses on the dataset:

Descriptive Statistics: Understanding the basic statistics of the dataset.
Exploratory Data Analysis (EDA): Exploring the relationships between different attributes and medical expenses.
Predictive Modeling: Building predictive models to estimate medical expenses based on patient attributes.

## Summary of Results
RandomForestRegressor outperformed other models with the lowest MSE (3.3230) and MAE (1.1732), and the highest R² (0.9897). This indicates that the RandomForestRegressor has the highest predictive accuracy and reliability among the evaluated models.
Support Vector Regressor showed the highest MSE (8.8477) and the highest MAE (1.6147), indicating it had the least accuracy in this specific regression task.
Decision Tree Regression and MLP Regressor provided a balance between performance and computational efficiency, with Decision Tree Regression having a relatively low MSE (5.5828) and a strong R² (0.9827).
Linear Regression performed well with an R² of 0.9771, which suggests it explained a large portion of the variance in the data despite having higher MSE and MAE compared to some other models.
## Conclusion
The RandomForestRegressor emerged as the best-performing model based on the evaluated metrics, making it a suitable choice for this regression task. Future work could include hyperparameter tuning, cross-validation, and testing on different datasets to further validate these findings.
