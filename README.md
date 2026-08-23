# Task-03: Bank Marketing – Decision Tree Classifier

## Overview

This project uses the **Bank Marketing dataset** to build a Decision Tree Classifier that predicts whether a customer will subscribe to a bank term deposit.

## Workflow

- Data loading and exploration
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Categorical feature encoding
- Train-test split
- Decision Tree classification
- Model evaluation
- Hyperparameter tuning
- Feature importance analysis
- Decision tree visualization

## Model Performance

- **Initial Decision Tree Accuracy:** 83.03%
- **Tuned Decision Tree Accuracy:** 89.35%
- **Tuned Training Accuracy:** 89.95%

## Overall Interpretation

The tuned Decision Tree performs better and shows **less overfitting** than the initial model. However, the dataset is highly imbalanced, with most customers not subscribing. Therefore, accuracy alone is not enough to evaluate the model.

The model has relatively low recall for the **"Yes"** class, meaning it still has difficulty identifying customers who are likely to subscribe.

Overall, the project demonstrates how a Decision Tree can be used to analyze customer behavior and predict potential product subscriptions.
