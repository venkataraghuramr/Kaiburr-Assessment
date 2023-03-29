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

<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/Process%20Flow.png" width="900" height="1000">

# EDA
<p>
As Many Graph were there I am Only inclusing some graphs others we can refer it in the Results Directory EDA Folder
</p>
<h3>Relationship Between Time and Transactions</h3>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/Relationship%20Between%20Time%20and%20Transactions.png" width="430" height="469">
<h3>Correlation Matrix for the Dataset:</h3>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/Correlation%20Matrix.png" width="457" height="309">

# Results
<p>I am including the best Features of Approach 1 and Final Models Comparisions as including all the models performance will make this clumsy</p>
<h3>Approach 1 Models Performance Comparision</h3>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/Approach%201%20models.jpg" width="643" height="813">
<br>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/Approach%201%20Best%20Classiers%20HistPlot.png" width="707" height="374">
<br>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/Best%20Classifiers%20PR%20Comparision.png" width="964" height="391">
<br>
<h3>Comparision of Performance of All Models</h3>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/ALL%20models%20mix.jpg" width="436" height="356">
<h3>Best Models Perfromance Comparison</h3>
<br>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/bestmodelsoverall3approahes.jpg" width="171" height="818">
<br>
<img src="https://github.com/venkataraghuramr/Kaiburr-Assessment/blob/main/Task%206/Results/Final%20Comparision%20of%20all%20Models.png" width="1711" height="383">
<br>

# Conclusion

<p>
 <h5>Based on the Average Precision, Recall Score XG Boost has the highest score hence can be considered as the best model of al the other models</h5>
</p>
