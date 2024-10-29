# Module 12 Report

## Overview of the Analysis

The goal of this analysis is to predict the credit risk associated with borrowers using data from a peer-to-peer lending service. By leveraging historical financial data, we aim to build a logistic regression model that can classify loans as either "healthy" or "high-risk." This analysis provides insights into the factors contributing to loan defaults, helping lenders make informed decisions about borrower creditworthiness.
Our dataset includes various financial attributes, such as loan amount, interest rate, borrower income, debt-to-income ratio, and other indicators relevant to lending. We followed a machine learning workflow that involved data preprocessing, training a logistic regression classifier, and evaluating model performance through metrics like precision, recall, and accuracy. This approach allows us to assess how well the model can differentiate between healthy and high-risk loans, providing a foundation for improved risk assessment strategies.

## Results

* Machine Learning Model 1:
    * Model Accuracy: 99%
The model achieved a high overall accuracy, correctly classifying 99% of loans as either healthy or high-risk.
Healthy Loan (0):
Precision: 1.00
The model perfectly identified all healthy loans without mistakenly labeling any high-risk loans as healthy.
Recall: 1.00
It also correctly captured all actual healthy loans, ensuring no healthy loans were misclassified.
High-Risk Loan (1):
Precision: 0.86
For high-risk loans, the model was fairly accurate, although a few healthy loans were classified as high-risk.
Recall: 0.91
The model managed to identify most high-risk loans correctly, with only a small portion left undetected.

## Summary

The logistic regression model did a stellar job, especially when it came to predicting healthy loans. With perfect precision and recall for healthy loans, the model correctly identified every single one without misclassifying any as high-risk. This makes it a reliable tool for identifying low-risk borrowers.
For high-risk loans, the model still performed well, though there was a slight dip in precision and recall. It caught most of the risky loans, but a few healthy ones were flagged as high-risk, and some high-risk ones were missed. Still, with an overall accuracy of 99%, it’s clear that this model knows how to separate safer loans from the riskier ones.
All in all, this logistic regression model is a solid choice for assessing creditworthiness. However, if the business has a high sensitivity to false positives or negatives, it might be worth fine-tuning the model further to reduce those misclassifications. But as it stands, it’s a powerful tool for lending decisions.