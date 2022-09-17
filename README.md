# Telecom Churn 
> Predicts whether the customer is going to churn or not given his past 3 months usage.


## Table of Contents
* Python File - Containing python code

## General Information
- EDA , handling null values 
- handle the class imbalance by using class weight = balanced in all the models 

## Models 
- Basic logistic regression model 
- RFE + Logistic Regression
- PCA + Random Forest Classifier
- RFC without PCA
- XGBoost Classifier with PCA and without PCA

## Conclusions
- RFC without PCA has accuracy 94, sensitivity 74 and specificity 96... Since we need to know who all customers are going to churn so we need to have a model with high sensitivity.
- In the python notebook added the metrics for each model and also added the driving variables.
