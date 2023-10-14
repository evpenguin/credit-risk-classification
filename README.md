# Challenge 20 - Credit Risk Classification

## Overview of the Analysis

This analysis was to build a model that would accurately and precisely predict whether a loan is healthy or high risk. We used a dataset of historical lending activity from a peer-to-peer lending services company. We were aiming to predict 'loan_status' a binary column where healthy loans are denoted 0, and high risk loans are denoted 1. We created a Logistic Regression model using SKLean in python, and split the data up into training and testing sets using the module. We fit the model to the training data, and then created a confusion matrix and classification report to determine the models efficacy. 


## Results

* Logistic Regression
  * This model had overall accuracy of 99%.
  * For healthy loans, the model had 100%* precision, and 99% recall.
  * For high risk loans, the model had 85% precision, and 91% recall.

*This precision of 100% is inaccurate according to the confusion matrix- it is highly likely that the model is rounding this figure up from some high level of 99. something % precision instead. 


## Summary

This logistic model is more adept at predicting healthy loans than high risk loans, but that may be affected due to the distribution of healthy vs high risk loans in the training and test data.

Within the models predicted healthy loans, it is 100% precise, and missclassifies only 1% (complement of recall) of the healthy loans as high risk loans.

Within the models predicted high risk loans, it is 85% precise, and misclassifies 9% (complement of recall) of the high risk loans as healthy loans.

This Logistic Regression performs reasonably well, however this data set leaves some things to be desired. Without further training and testing data, and discussion with the client, I would not reccomend this model be put into prodiction to predict loan health. The low level of precision and recall on High Risk Loans is concerning, and could pose significant risk to the buisness to continually misclassify these loans. 
