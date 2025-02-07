# House Price Prediction Project
## Overview
This project aims to predict house prices in Boston using machine learning techniques. The model is built using the Boston Housing dataset, which contains various features influencing house prices. The goal is to provide accurate predictions based on these features.

## Dataset
The dataset used in this project is the Boston Housing Dataset, which includes the following features:

CRIM: Per capita crime rate by town
ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
INDUS: Proportion of non-retail business acres per town
CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NX: Nitric oxides concentration (parts per 10 million)
RM: Average number of rooms per dwelling
AGE: Percentage of owner-occupied units built prior to 1940
DIS: Weighted distances to five Boston employment centres
RAD: Index of accessibility to radial highways
TAX: Full-value property tax rate per $10,000
B
PTRATIO: Pupil-teacher ratio by town
LSTAT: Percentage of lower status of the population
price: Median value of owner-occupied homes in $1000s (target variable)

## Technologies Used
Python 3
Pandas
Matplotlib
Seaborn
Scikit-learn
XGBoost

## Usage
Load the dataset and perform initial exploration.
Preprocess the data by checking for missing values and visualizing correlations.
Split the dataset into training and testing sets.
Train the XGBoost Regressor model on the training data.
Evaluate the model's performance using metrics such as R squared error and Mean Absolute Error.
Visualize the actual vs. predicted house prices.

## Model Evaluation
The model's performance is evaluated using metrics including:

R squared error: Measures how well the model explains the variability of the target variable.
Mean Absolute Error: Measures the average magnitude of the errors in a set of predictions.
