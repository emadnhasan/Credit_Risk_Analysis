# Credit Risk Analysis

# Overview

The purpose of this analysis was to use machine learning models in order to predict and assess credit risk. This was done through the use of a collection of algorithms:
* undersampling the data using ClusterCentroids
* oversampling the date using RandomOverSampler and Smote
* both over and under sampling using SMOTEEN
BalanceRandomForestClassifier and EasyEnsembleClassifier were used to reduce bias and predict credit risk.

# Results
## Naive Random Oversampling
![Niave Random Sampling](https://user-images.githubusercontent.com/100659114/177179987-45177e41-fa3e-43f4-aa61-8f49f26efee4.png)
* Balanced Accuracy: 63%
* Precision: **High Risk Loans**: Low $~~~~~~$  **Low Risk Loans**: High
* Recall: High/Low risk = .54/.73

## SMOTE Oversampling
![SMOTE](https://user-images.githubusercontent.com/100659114/177180014-8a71b1e3-c68b-4430-85ba-97ab4492490e.png)
* Balanced Accuracy: 62%
* Precision: **High Risk Loans**: Low $~~~~~~$  **Low Risk Loans**: High
* Recall: High/Low risk = .56/.68

## Undersampling
![Undersampling](https://user-images.githubusercontent.com/100659114/177180026-78e1b002-393d-414d-9f1a-2f69508e45e6.png)
* Balanced Accuracy: 52%
* Precision: **High Risk Loans**: $~~~~~~$  **Low Risk Loans**: High
* Recall: High/Low risk = .57/.47

## Combination Over/Undersampling
![Combination](https://user-images.githubusercontent.com/100659114/177180051-49c786e0-2220-4c59-92ea-bc806b13db9e.png)
* Balanced Accuracy: 66%
* Precision: **High Risk Loans**: $~~~~~~$  **Low Risk Loans**: High
* Recall: High/Low risk = .73/.60
​
## Balanced Random Forest Classifier
![Balanced random Forest Classifier](https://user-images.githubusercontent.com/100659114/177180079-8b4793d2-429c-4b2b-9f91-e2e74f4de57c.png)
* Balanced Accuracy: 63%
* Precision: **High Risk Loans**: $~~~~~~$  **Low Risk Loans**: High
* Recall: High/Low risk = .41/.98
​
## Easy Ensemble Classifier
![Easy ensemble](https://user-images.githubusercontent.com/100659114/177180092-3684020c-215b-44bd-a82d-79b75eecc9cf.png)
* Balanced Accuracy: 92%
* Precision: **High Risk Loans**: $~~~~~~$  **Low Risk Loans**: High
* Recall: High/Low risk = .90/.94
​
# Summary
Most of the models use to perform the credit risk analysis exhibited low balanced accuracy scores. These models do not seem to be a good indicator of credit risk. In contrast, the Easy Ensemble Classifer had a balanced accuracy of 94%. This model also had recall scores over 90%, while the other models all had low recall scores. As a result, the Easy Ensemble Classifier is the best model to use when analyzing credit risk.
