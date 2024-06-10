# Final-Year-Credit-Card-Fraud-Detection-Project

![CREDIT CARD](https://user-images.githubusercontent.com/28294942/190845223-1daf8cbd-5dfb-4071-9885-aa1883d64bdc.png)


Credit Card Fraud Detection Project with Research paper, Code and Documents 

### Objective:
Credit Card Fraud Detection using Neural Networks (Keras) This involves pattern classification in an unbalanced dataset to determine the fraudulent transactions.

### Experimental Design:
Algorithm Selection: This research is basically based on whether the performance of a Neural Network would significantly differ if one part of the algorithm’s configuration is changed. Firstly, a multi-layer perceptron with 1-hidden layer was trained followed by a multi-layer perceptron with 2 hidden layers. Most of the parameters were tuned using Gridsearch algorithm followed by Trial and Error and, the rest were used as default provided by the Keras library.
Testable Hypothesis: A neural network’s performance on the Credit-Card Fraud dataset is affected by the number of hidden layers.
Null Hypothesis (H0): Insufficient evidence to support the hypothesis.
Alternate Hypothesis (H1): Evidence suggests the hypothesis is likely true.
This means that if the null hypothesis is accepted, there is no significant difference between the performance of the two MLPs with a different number of hidden layers. However, if the null hypothesis is rejected, i.e., the alternate hypothesis is accepted, it implies that changing the number of hidden layers in the neural network has a significant difference in the performance of the model.

### Dataset Information

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

Coorelation Matrix


Two main Machine Learning Algorihtm are used: 

1. Logistic Regresion
2. Random forest 
