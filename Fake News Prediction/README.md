# Fake News Prediction Project

## Overview
This project aims to develop a machine-learning model to classify news articles as real or fake. By leveraging natural language processing (NLP) techniques, the model analyzes the text of news articles to identify patterns associated with misinformation.

## Dataset
The dataset used in this project contains the following columns:

id: Unique identifier for each news article
title: Title of the news article
author: Author of the news article
text: The content of the article (may be incomplete)
label: Indicates whether the news article is real or fake:
  1: Fake news
  0: Real news

## Technologies Used
Python 3
NumPy
Pandas
NLTK (Natural Language Toolkit)
Scikit-learn
Jupyter Notebook (or Google Colab)

# Usage
Load the dataset and perform initial data analysis.
Preprocess the data by:
Handling missing values
Merging the author's name and article title
Stemming the content
Converting text to numerical format using TF-IDF Vectorization
Split the dataset into training and testing sets.
Train a logistic regression model on the training data.
Could you evaluate the model's accuracy on both training and testing datasets?
Could you make predictions on new articles?

# Model Evaluation
The model's performance is assessed using accuracy scores on the training and testing datasets. The project includes code to print the accuracy scores for both datasets.
