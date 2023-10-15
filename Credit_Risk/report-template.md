# Module 20 Report

## Overview of the Analysis

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


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
