# Credit_Risk_Analysis

## Purpose

THe purpose of this project was to assess Credit risk (an inherently unbalanced classification problem) by employing different techniques to train and evaluate models with unbalanced classes. We used  imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 

Using a credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. We then used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Lastly, we will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results (Balanced Accuracy Scores, Precision, Recall Reports)

- **Naive Random Oversampling**
<img width="815" alt="Screen Shot 2022-04-24 at 3 01 44 PM" src="https://user-images.githubusercontent.com/95551195/164996425-f52f24cf-c34d-4227-9003-88f5afd99f59.png">

Balance Accuracy is 62%, while the High-Risk Precision is 1%. Sensitiviy is around 61% with an F1 Score of 2%.


-  **SMOTE Oversampling**
<img width="823" alt="Screen Shot 2022-04-24 at 3 49 52 PM" src="https://user-images.githubusercontent.com/95551195/164998084-a70957c5-683d-4ad2-ba37-b1ca90303566.png">

Balance Accuracy is 62%, while the High-Risk Precision is 1%. Sensitiviy is around 61% with an F1 Score of 2%.

- **UnderSampling**
<img width="826" alt="Screen Shot 2022-04-24 at 3 57 16 PM" src="https://user-images.githubusercontent.com/95551195/164998345-d83bd5a0-f73a-476d-b9a4-ccb53bc7cda5.png">

Balance Accuracy is 53%, while the High-Risk Precision is 1%. Sensitiviy is around 61% with an F1 score of 1%.

- **SMOTEENN**
<img width="809" alt="Screen Shot 2022-04-24 at 4 01 45 PM" src="https://user-images.githubusercontent.com/95551195/164998541-6393101d-a090-4c9c-b311-68a62b16bbf4.png">

Balance Accuracy is 65%, while the High-Risk Precision is 1%. Sensitiviy is around 69% with an F1 score of 2%.

- **Balanced Random Forest Classifier**
<img width="799" alt="Screen Shot 2022-04-24 at 4 06 58 PM" src="https://user-images.githubusercontent.com/95551195/164998724-70118094-6573-4cb4-b4b4-fbfff9bf156b.png">

Balance Accuracy is 79%, while the High-Risk Precision is 4%. Sensitiviy is around 67% with an F1 score of 7%.

- **Easy Ensemble AdaBoost Classifier**
<img width="805" alt="Screen Shot 2022-04-24 at 4 08 18 PM" src="https://user-images.githubusercontent.com/95551195/164998754-406080db-9489-44c8-809d-67d1cf7f72a3.png">

Balance Accuracy is 93%, while the High-Risk Precision is 7%. Sensitiviy is around 91% with an F1 score of 14%.
