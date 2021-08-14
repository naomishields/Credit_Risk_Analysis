# Credit Risk Analysis
## Overview 
The purpose of this project was to use *Machine Learning* techniques to address credit card risk. Multiple models were employed to attempt to classify high risk and low risk loans. 

## Results
After splitting the data into training and testing groups, the training data was used in six different models. Then after training the data in each respective model, a balanced accuracy score was generated along with a confusion matrix and a classification report. 
### RandomOverSampler Oversampling Algorithm
![naive random oversampling](https://github.com/naomishields/Credit_Risk_Analysis/blob/main/Resources/naive_random_oversampling.png)
This model had a balanced accuracy score of 0.5763. For high risk loans, it had a precision score of 0.01 and a recall score of 0.46. For low risk loans, it has a precision score of 1.00 and a recall score of 0.69.
### SMOTE Oversampling Algorithm
![smote](https://github.com/naomishields/Credit_Risk_Analysis/blob/main/Resources/smote_oversampling.png)
This model had a balanced accuracy score of 0.6462. For high risk loans, it had a precision score of 0.01 and a recall score of 0.56. For low risk loans, it has a precision score of 1.00 and a recall score of 0.73.
### ClusterCentroids Undersampling Algorithm
![undersampling](https://github.com/naomishields/Credit_Risk_Analysis/blob/main/Resources/undersampling.png)
This model had a balanced accuracy score of 0.6462. For high risk loans, it had a precision score of 0.01 and a recall score of 0.53. For low risk loans, it has a precision score of 0.99 and a recall score of 0.54.
### SMOTEENN Over and Undersampling Algorithm
![combinatorial](https://github.com/naomishields/Credit_Risk_Analysis/blob/main/Resources/combination.png)
This model had a balanced accuracy score of 0.5333. For high risk loans, it had a precision score of 0.01 and a recall score of 0.72. For low risk loans, it has a precision score of 1.00 and a recall score of 0.57.
### BalancedRandomForestClassifier Algorithm
![balanced rf](https://github.com/naomishields/Credit_Risk_Analysis/blob/main/Resources/balanced_rf.png)
This model had a balanced accuracy score of 0.7824. For high risk loans, it had a precision score of 0.04 and a recall score of 0.66. For low risk loans, it has a precision score of 1.00 and a recall score of 0.91.
### EasyEnsembleClassifier Algorithm
![eec](https://github.com/naomishields/Credit_Risk_Analysis/blob/main/Resources/eec.png)
This model had a balanced accuracy score of 0.9110. For high risk loans, it had a precision score of 0.08 and a recall score of 0.87. For low risk loans, it has a precision score of 1.00 and a recall score of 0.95.

## Summary
After comparing the models, it is clear that some performed better than others. The model that I would recommend would be the mdoel that used the EasyEnsembleClassifier algorithm. This model yieled the highest accuracy score along with the highest precision and recall scores. 
