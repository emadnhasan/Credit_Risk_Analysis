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
* Precision: **High Risk Loans**: Low <space><space><space> **Low Risk Loans**: High
* Recall: High/Low risk = .66/.67

## SMOTE Oversampling
![SMOTE](https://user-images.githubusercontent.com/100659114/177180014-8a71b1e3-c68b-4430-85ba-97ab4492490e.png)
Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67


## Undersampling
![Undersampling](https://user-images.githubusercontent.com/100659114/177180026-78e1b002-393d-414d-9f1a-2f69508e45e6.png)
Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67


## Combination Over/Undersampling
![Combination](https://user-images.githubusercontent.com/100659114/177180051-49c786e0-2220-4c59-92ea-bc806b13db9e.png)
Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67

## Balanced Random Forest Classifier
![Balanced random Forest Classifier](https://user-images.githubusercontent.com/100659114/177180079-8b4793d2-429c-4b2b-9f91-e2e74f4de57c.png)
Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67

## Easy Ensemble Classifier
![Easy ensemble](https://user-images.githubusercontent.com/100659114/177180092-3684020c-215b-44bd-a82d-79b75eecc9cf.png)
Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67


### Website
![Homepage](https://user-images.githubusercontent.com/100659114/169694803-5ac4d2bb-5a3b-4458-8df9-b5bf1b81e4f9.png)

On the left side of the screen the user is able to input the criteria by which they would like to filter the results
![filters](https://user-images.githubusercontent.com/100659114/169694930-b2835b29-1395-423c-b819-32a2c64b9be9.png)

The user can select one or multiple filters. The results are then dispayed on the right.
![results](https://user-images.githubusercontent.com/100659114/169694965-e01ed84d-1fb0-4523-a14f-85741a4a427f.png)



## Summary
The website offers an efficient and easy to use way to filter and search for data. However it does have drawbacks that may be addressed.
* The data set is rather limited. The data only includes information from a 13 day period in 2010. Offering data from a larger date set would make the website more beneficial.
* Ater completing a search, the boxes must be manually cleared in order to perform another search. A "Clear" button would make this process more efficient.
* The user has to know the paramenter they are searching for, as there is not a list of options to choose from. A frop down menu for each filter would make this easier and allow the user to see the options. 
