# Credit-Card-Fraud-Detection

The goal of this report is to develop and compare various machine learning models like logistic regression, decision tree, random forest and xgboost and find the most suitable model capable of identifying fraud in credit card transactions, with the goal of minimizing company risk and loss. The most challenging difficulty is developing a model that is very sensitive to fraud, because most transactions are valid, making detection difficult.

# DATASET

This paper uses the dataset that was collected and analyzed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. The dataset was obtained from Kaggle (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It contains transactions of 2 days in which 492 were fraudulent transactions out of 2,84,807 total transactions. 
‘Time’ is a column that contains the seconds elapsed between each transaction and the first transaction in the dataset. 'Amount' is the transaction Amount. Features from V1 to V28 are the principal components obtained with PCA as they contained private information that could not be revealed. ‘Class’ is the result variable that gives 1 in the case of Fraudulent transaction and 0 in the case of Normal transaction.  Time, Amount and Class are non-PCA applied features. The dataset is divided as 75% and  25% in the Train and Test set, respectively. 

# RESULT 

# Logistic Regression
Using the Logistic Regression algorithm, we get an accuracy of 99.91% and an F1 score of 68.3%

# Decision Tree
Using Decision Tree Classifier algorithm , we get an accuracy of 99.91% and an F1 score of 72.9%

# Random Forest
Using the Random Forest Classifier algorithm, we get an accuracy of 99.9% and an F1 score of 84.2%

# XGBoost
Using the XGBoost algorithm, we get an accuracy of 99.9% and F1 score of 84.89%
