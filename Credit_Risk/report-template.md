# Module 20 Report

## Purpose of the Analysis:
The purpose of this machine learning analysis was to develop a predictive model for assessing loan risk. The dataset, sourced from the "lending_data.csv" file, contains financial information related to loans, and the primary goal was to predict whether a loan is healthy (0: low risk) or high-risk (1: likely to default).

## Financial Information in the Data:
The dataset includes various financial features, and the target variable for prediction is the "loan_status" column. This column represents the health of the loan, with 0 indicating a healthy loan and 1 indicating a high-risk loan.

## Variables to Predict:
Target Variable: loan_status (Binary: 0 or 1)
Features: Other columns in the dataset, excluding the target variable.

## Stages of the Machine Learning Process:
Data Loading and Exploration:
* Loaded the dataset into a Pandas DataFrame.
* Explored the structure of the data using head() to understand the features.

Data Preprocessing:
* Created labels (y) and features (X) from the dataset.
* Split the data into training and testing sets using train_test_split.

Model Development:
* Utilized a logistic regression model to predict loan status.
* Fit the model using the training data (X_train and y_train).
* Made predictions on the testing data (X_test).

Model Evaluation:
* Generated a confusion matrix to assess the performance of the model.
* Printed a classification report, including precision, recall, and F1-score.

## Methods Used
Logistic Regression: 
* Utilized the logistic regression algorithm for its suitability in binary classification tasks.
  
Train-Test Split: 
* Split the dataset into training and testing sets to assess the model's generalization performance.

Evaluation Metrics: 
* Employed confusion matrix, precision, recall, and F1-score to evaluate model performance.


## Results
Accuracy Score:
* The accuracy of the logistic regression model is high, indicating the overall correctness of predictions. The accuracy score is 0.99.

Precision Score:
* Precision is the ratio of true positive predictions to the total predicted positives. For the high-risk loans (1), the precision score is 0.87.

Recall Score:
* Recall, also known as sensitivity or true positive rate, measures the ability of the model to capture all positive instances. The recall score for high-risk loans (1) is 0.89.


## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

The analysis successfully developed and evaluated a logistic regression model for predicting loan risk based on financial features. 

The model exhibited promising performance, providing a valuable tool for assessing and managing the risk associated with loans.
