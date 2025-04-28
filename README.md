# House Price Prediction using Linear Regression

## Overview
This project implements a Multiple Linear Regression model to predict house prices based on various features like area, bedrooms, bathrooms, etc.

## Dataset

Source: Housing Price Prediction from Kaggle

Features: 12 independent variables (area, bedrooms, mainroad, etc.)

## Steps Covered

1. Imported necessary libraries.
2. Loaded and preprocessed the dataset (converted categorical features).
3. Split the dataset into training and testing sets (80-20 split).
4. Built a Linear Regression model using scikit-learn.
5.  Evaluated the model using: Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R² score
6. Visualized the results using a scatter plot of actual vs predicted values.
7. Interpreted the regression coefficients.


## Important Notes

Interpretation:
Each coefficient represents the expected change in house price for a one-unit increase in the respective feature, keeping other features constant.

Visualization:
A perfect prediction would align along the 45° line in the scatter plot.
