# Challenge 20 - Credit Risk Classification

## Overview of the Analysis

This analysis was to build a model that would accurately and precisely predict whether a loan is healthy or high risk. We used a dataset of historical lending activity from a peer-to-peer lending services company. We were aiming to predict 'loan_status' a binary column where healthy loans are denoted 0, and high risk loans are denoted 1. We created a Logistic Regression model using SKLean in python, and split the data up into training and testing sets using the module. We fit the model to the training data, and then created a confusion matrix and classification report to determine the models efficacy. 


## Results

* Logistic Regression
  * This model had overall accuracy of 99%.
  * For healthy loans, the model had 100%* precision, and 99% recall.
  * For high risk loans, the model had 85% precision, and 91% recall. 


## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
