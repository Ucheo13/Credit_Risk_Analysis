# Credit_Risk_Analysis
## Overview
We need to employ different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub we’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results 
Random Oversampling 
-Accuracy Score of 0.6379, Precision High risk: 0.1 low risk:1.00, Recall high risk: 0.64 low risk: 0.63
SMOTE Oversampling 
-Accuracy Score of 0.6623, Precision High risk: 0.1 low risk:1.00, Recall high risk: 0.63 low risk: 0.69
Undersampling 
-Accuracy Score of 0.5274, Precision High risk: 0.1 low risk:1.00, Recall high risk: 0.59 low risk: 0.47
Combination Sampling 
-Accuracy Score of 0.6375, Precision High risk: 0.1 low risk:1.00, Recall high risk: 0.71 low risk: 0.56
Random Forest Classifier 
-Accuracy Score of 0.6548, Precision High risk: 0.68 low risk:1.00, Recall high risk: 0.31 low risk: 1.00
Easy Ensemble Classifier 
-Accuracy Score of 0.995, Precision High risk: 0.68 low risk:1.00, Recall high risk: 0.31 low risk: 1.00
## Summary

Oversampling numbers displayed were okay. Gets better with SMOTE oversampling and worse with Undersampling. Combination sampling shows a better recall score for high risk loans.The balanced random forest classifier and easy ensemble classifier does well with low risk but not with high risk loans on recall but the precision shows improvement. Easy ensemble learning has the highest accuracy.
