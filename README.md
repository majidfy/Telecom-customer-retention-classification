# Telecom-customer-retention-classification
This project is based on telecom customer dataset. The dataset can be found at https://www.kaggle.com/radmirzosimov/telecom-users-dataset.
The data contains information about almost six thousand users, their demographic characteristics, the services they use, the duration of using the operator's services, the method of payment, and the amount of payment.
The task is to analyze the data and predict the churn of users (to identify people who will and will not renew their contract).
The following tasks are done in this project
* Analysis of all the variables to check for corelations with the label variable.
* Encoding of the categorical variables to implement classification algorithms.
* Reducing the dimenssiality of the variables by implementing PCA
* Adjusting the class imbalance issue by introducing upsampling technique and also using the class weights for a weighted training of the model
* Implementing Logistic regression and SVM to create the model
* Obtaining the confusion matrix and evaluating the model on the basis of precision, recall and AUC score.

The logistic regression model gives an AUC score of 75%
