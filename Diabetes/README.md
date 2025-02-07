# Diabetes Prediction Project

## Overview
This project aims to develop a machine learning model that predicts the likelihood of diabetes in individuals based on various health-related features. The model utilizes the PIMA Indian Diabetes Database, which contains data on several medical predictor variables and one target variable indicating the presence or absence of diabetes.

## Technologies Used
Python 3
NumPy
Pandas
Scikit-learn
Jupyter Notebook

## Dataset
The dataset used for this project is the PIMA Indian Diabetes Database. It contains the following features:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age (years)
Outcome: Class variable (0 or 1) indicating the absence or presence of diabetes

## Usage
Load the dataset and perform initial data analysis.
Preprocess the data by standardizing the features.
Split the data into training and testing sets.
Train the Support Vector Machine (SVM) classifier.
Evaluate the model's accuracy on both training and testing data.
Make predictions based on new input data.

## Model Evaluation
The model's performance is evaluated using accuracy scores on both the training and testing datasets. This project's model achieved an accuracy of approximately 78.66% on the training data and 77.27% on the test data.
