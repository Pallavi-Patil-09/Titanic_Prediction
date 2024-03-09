# Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning algorithms.

## Overview

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, resulting in the deaths of over 1,500 passengers and crew.

In this, we use a dataset containing various information about Titanic passengers, such as their age, sex, class, and whether they survived or not. We apply machine learning techniques to this dataset to predict whether a given passenger survived the sinking or not.

## Dataset

It contains the following columns:

- PassengerId: Unique identifier for each passenger
- Survived: Whether the passenger survived (0 = No, 1 = Yes)
- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name: Passenger's name
- Sex: Passenger's sex
- Age: Passenger's age
- SibSp: Number of siblings/spouses aboard
- Parch: Number of parents/children aboard
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Approach

We approach the problem in the following steps:

1. Data Exploration: Analyze the dataset to understand the distribution of features and identify any patterns.
2. Data Preprocessing: Handle missing values, encode categorical variables, and scale numerical features as necessary.
3. Feature Engineering: Create new features or transform existing ones to improve model performance.
4. Model Selection: Experiment with different machine learning algorithms such as logistic regression, random forest, and gradient boosting.
5. Model Evaluation: Evaluate the performance of each model using appropriate metrics such as accuracy, precision, recall, and F1 score.
6. Prediction: Use the trained model to make predictions on the test set and evaluate its performance.

## Results

The best performing model achieved an accuracy of X% on the test set, outperforming baseline models. Further details and analysis can be found in the project's notebooks.

## Usage

To reproduce the results
