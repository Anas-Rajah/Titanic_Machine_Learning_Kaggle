# Titanic Survival Prediction

# Overview
This project involves predicting survival on the Titanic using machine learning techniques. The dataset used is from Kaggle and includes features such as passenger age, sex, class, and more. The goal is to build a model that can predict whether a passenger survived the disaster.

# Data
train.csv: Training dataset with survival outcomes.
test.csv: Dataset for generating predictions.

# Features
Numerical Features: Age, Fare
Categorical Features: Sex, Pclass, Embarked, Title, Family Size.

# Approach
Load Data: Load training and test datasets.
Data Preprocessing:
  Handle missing values.
  Encode categorical variables.
  Scale numerical features.
Feature Engineering:
  Extract titles from names.
  Categorize family size.
Model Training: Train a Logistic Regression model.
Evaluation: Assess model performance on validation data.
Prediction: Generate predictions for the test dataset and save results.

# Installation
To run the project, ensure you have the following Python libraries installed:
pandas
numpy
seaborn
matplotlib
scikit-learn
Install the required libraries using: 
pip install pandas numpy seaborn matplotlib scikit-learn

# Files
  train.csv: Contains training data with survival labels.
  test.csv: Contains test data for predictions.
  submission_clf.csv: File with predictions for the test dataset.
  
# Results
The model achieved an accuracy of approximately 78.15% on the validation set.
