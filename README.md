# Credit-Card-Fraud-Detection

## Problem Statement:

The Credit Card Fraud Detection Project includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a  transaction is fraudulent or not using 3 Algorithms seperately : SVR, Isolation Forest and Local Outlier Factor.

## Data Set:

The dataset has been picked from https://www.kaggle.com/mlg-ulb/creditcardfraud 

## Observations

The dataset consists of numerical values from the 28 ‘Principal Component Analysis (PCA)’ transformed features, namely V1 to V28. Furthermore, there is no metadata about the original features provided, so pre-analysis or feature study could not be done.
The ‘Time’ and ‘Amount’ features are not transformed data.
There is no missing value in the dataset.


## Some Definitions:

The following are essential definitions of the output to compare:

True Positive: The fraud cases that the model predicted as ‘fraud.’

False Positive: The non-fraud cases that the model predicted as ‘fraud.’

True Negative: The non-fraud cases that the model predicted as ‘non-fraud.’

False Negative: The fraud cases that the model predicted as ‘non-fraud.’

Threshold Cutoff Probability: Probability at which the true positive ratio and true negatives ratio are both highest.

Accuracy:The ratio of fraud transactions and non-fraud to the total transactions in the test data.

Sensitivity: Sensitivity, or True Positive Rate, or Recall, is the ratio of correctly identified fraud cases to total fraud cases.

Specificity: Specificity, or True Negative Rate, is the ratio of correctly identified non-fraud cases to total non-fraud cases.

Precision: Precision is the ratio of correctly predicted fraud cases to total predicted fraud cases.

### Conclusion

Fastest Algorithm -> Local Outlier

Most efficient Algorithm -> Isolation Forest

Slowest Algorithm -> SVM

## Project By
Mohammad Maaz Rashid
