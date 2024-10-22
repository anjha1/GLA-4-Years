# Gender Classification using Logistic Regression

This project demonstrates the development of a gender classification model using the Logistic Regression 
algorithm in Python. The dataset used for this project is available on Kaggle, and the implementation is 
done in a Python 3 environment pre-installed with essential data science libraries.



# Dataset

The dataset used for this classification task can be found in the following 
path: /kaggle/input/gender-classification-dataset/gender_classification_v7.csv
It consists of various features to classify gender as Male or Female.

# Project Overview

This repository covers the following steps:

Data Loading: Load the dataset and explore its structure.
Data Preprocessing:
Handle missing values.
Convert categorical variables into numerical using mapping techniques.
Data Visualization:
Generate correlation heatmaps using Seaborn to find relationships between variables.
Visualize the data using box plots.
Splitting the Data: Split the dataset into training and testing sets (80% training, 20% testing).
Model Training:
Train a Logistic Regression model on the training dataset.
Model Evaluation:
Evaluate the model's performance using various metrics:
Accuracy
Confusion Matrix
Precision
Recall
F1 Score


Results

The model provides a detailed classification of gender based on various input features.
Performance is evaluated using accuracy, precision, recall, and F1 score.
Model Evaluation
Here are the key performance metrics:

Accuracy: The overall accuracy of the model.
Precision: How many of the predicted positives were actual positives.
Recall: How many actual positives were predicted correctly.
F1 Score: Harmonic mean of precision and recall.
