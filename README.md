# credit-risk-classification
## Overview of the Analysis

This analysis aims to develop and evaluate a logistic regression model for credit risk classification. The dataset contains information about loans, including various features related to borrowers' credit profiles. The goal is to train a model that can accurately classify loans into two categories: "healthy" (low-risk) and "high-risk" based on the provided features.


## Results

For this homework assignment, we only used one machine learning model. 

* Machine Learning Model: Logistic Regression
  * Accuracy: The overall accuracy of the logistic regression model is 99%. This means that the model correctly predicts the loan status (healthy or high-risk) for 99% of the instances in the dataset.
  * Precision: Precision for healthy loans (0) is 100%, indicating that when the model predicts a loan as healthy, it is correct 100% of the time. Precision for high-risk loans (1) is 85%, meaning that when the model predicts a loan as high-risk, it is correct 85% of the time.
  * Recall scores:Recall for healthy loans (0) is 99%, indicating that the model correctly identifies 99% of the actual healthy loans. Recall for high-risk loans (1) is 91%, meaning that the model correctly identifies 91% of the actual high-risk loans.

## Summary

The logistic regression model demonstrates strong performance in classifying healthy loans, with high precision and recall. However, its performance on high-risk loans is slightly lower but still reasonable. The overall evaluation suggests that the model provides a balanced assessment of credit risk classification, making it a valuable tool for identifying potentially risky loans.

