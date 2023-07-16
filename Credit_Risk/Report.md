# Module 12 Report

## Overview of the Analysis

* In this Challenge, various techniques to train and evaluate a model based on loan risk are used. A dataset of historical lending activity from a peer-to-peer lending services company is used to build a model that can identify the creditworthiness of borrowers.
* The data included information such as the size of the loan, its interest rate, the borrower's income, the debt to income ratio, the number of accounts the borrower held, derogatory marks against the borrower, the total debt
* The program is designed to predict of the lean was healthy or high-risk.
* The stages of the machine learning process went through as part of this analysis:
1. Split the Data into Training and Testing Sets
2.Create a Logistic Regression Model with the Original Data
* LogisticRegression model was used to predict the data.

## Results
Logistic Regression Model 1:

* Precision: 100% precise on predicting low-risk loans and  87% precise in predicting high-risk loans
* Accuracy: 94%
* Recall: 100% precise on predicting low-risk loans and  89% precise in predicting high-risk loans

## Summary

This model was drawing from a dataset that had 75,036 low-risk loan data points and 2,500 high-risk data points.  It was split into training and testing sets. The training set was used to build an initial logistic regression model (Logistic Regression Model 1) using the LogisticRegression module from scikit-learn. Logistic Regression Model 1 was then applied to the testing dataset. The results are summarized above.

