# Credit_Risk_Analysis

## Purpose

THe purpose of this project was to assess Credit risk (an inherently unbalanced classification problem) by employing different techniques to train and evaluate models with unbalanced classes. We used  imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 

Using a credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. We then used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly, we will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results (Balanced Accuracy Scores, Precision, Recall Reports)

- Naive Random Oversampling
<img width="815" alt="Screen Shot 2022-04-24 at 3 01 44 PM" src="https://user-images.githubusercontent.com/95551195/164996425-f52f24cf-c34d-4227-9003-88f5afd99f59.png">

Balance Accuracy is 62%, while the High-Risk Precision is 1%. Sensitiviy is around 61% with an F1 Score of 2%.
