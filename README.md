# Titanic Survival Prediction

## Overview
This project predicts Titanic passenger survival using a Logistic Regression model. It involves data preprocessing, feature engineering, and model training.

## Datasets
- **`train.csv`**: Contains training data with survival labels.
- **`test.csv`**: Used for generating predictions.

## Features
- **Training Data**: `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`
- **Test Data**: `PassengerId`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

## Approach
1. **Load Data**: Read and preprocess the training and test datasets.
2. **Feature Engineering**: Extract titles from names, compute family size, categorize family size.
3. **Preprocessing**: Handle missing values, scale numerical features, and encode categorical features.
4. **Model Training**: Train a Logistic Regression model using the processed data.
5. **Prediction**: Make predictions on the test data and save results to `submission_clf.csv`.

## Installation
To run this project, install the necessary libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Files
  train.csv: Contains training data with survival labels.
  test.csv: Contains test data for predictions.
  submission_clf.csv: File with predictions for the test dataset.
  
## Results
The model achieved an accuracy of approximately 78.15% on the validation set.
