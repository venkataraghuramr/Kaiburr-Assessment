# Kaiburr Assessment Task 6
 
# Credit-Card-Fraud-Detection-System-Using-ML-and-DL-Models

# Problem Statement:
<p>
We have much research that are going in this field and we many more existing systems in the same idea with good models and with high accuracies. In this System I have included some economic parameters like Margins, Chargeback, Lost (False Positives), True Positives such as no lost customers. Considering these parameters in the Net Gain for creating a new formula with the existing features in the dataset and these economical parameters and to choose the model with all these factors to select a model which is economically feasible for both the credit card company and other companies who are using the algorithms.
</p>

# Data Set Used:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# About Dataset
<p>
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.
</p>

# System Design

1. Importing DataSet

2. Exploration of Dataset

3. Pre-Processing Of Data

4. Feature Selection

5. Training and Testing Data for Lstm

6. Prediction
