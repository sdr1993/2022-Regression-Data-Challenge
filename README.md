# 2022-Regression-Data-Challenge
Estimate score for a medical condition of a patient!

# Description:
This data challenge involves regression task. The target variable is 'score' that captures medical condition of a patient. Independent variables capture patient related data that can influence the target variable 'score'. First variable in the train.csv data file identifies each patient record uniquely.

The challenge is to correctly predict value for 'score' based on independent variables.

# Model Evaluation
## Linear Regressor:

mean_absolute_error: 0.7990138878486618

mean_squared_error: 0.9725434418148272

## SVR Regressor:

mean_absolute_error: 0.7272450796927424

mean_squared_error: 0.8628980763795706

## Ridge Regressor:

mean_absolute_error: 0.7991351508846334

mean_squared_error: 0.9724804683321314

## ANN Regressor:

mean_absolute_error: 0.8343563015562891

mean_squared_error: 1.0585733065177851

## Hypertuned XGBoost:

mean_absolute_error: 0.7783635169377756

mean_squared_error: 0.929069837163907

## Hypertuned RandomForest Regressor:

mean_absolute_error: 0.7015575539583458

mean_squared_error: 0.7787078832538008

# Best Mode: Hypertuned RandomForest Regressor

Kaggle Score: 9.21663
