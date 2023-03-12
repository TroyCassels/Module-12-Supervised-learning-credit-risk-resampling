# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to predict risky loans.
* The inputs to this include loan size, interes rate, borrower income, debt-to-income ratio and total debt.
* In the dataset provided, there were 2,500 risky loans and approx. 75,000 healthy loans.
* The stages of the analysis involved loading the data, analysing the dataset, splitting the data into a testing and training dataset, running models and oversampling.
* Models used were Logistic Regression and Random Oversampling..

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

    precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619
    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384



* Machine Learning Model 2:

          precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619
    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The resampled model performed better with better results in the classification report.
* It is more important to model the 1's or risky loans.


