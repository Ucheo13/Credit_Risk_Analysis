# Credit_Risk_Analysis
## Overview
We need to employ different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub we’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Summary

Oversampling numbers displayed were okay. Gets better with SMOTE oversampling and worse with Undersampling. Combination sampling shows a better recall score for high risk loans.The balanced random forest classifier and easy ensemble classifier does well with low risk but not with high risk loans on recall but the precision shows improvement.
