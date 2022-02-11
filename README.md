# Credit-Card-Defaulters
In this case study, we are going to build a classifier to calculate the probability of a customer defaulting their credit card bills
Dataset Description:
Each row is about a customer. We have details about their savings, employment, age, marital status etc. In default column (target column), we have value 1, if the customer has not defaulted and the value 2, if the customer has defaulted.

Guidelines
In the target column, replace 1 with 0 and 2 with 1. So that the defaulters will become positive class

Summarize the dataset using various summarization techniques

Identify whether the target column is balanced or imbalanced. Plot the same using a simple pie chart

Perform exploratory data analysis to identify which factors differentiate/influences customers who are defaulting with others

Convert all categorical columns to numerical columns using one hot encoding (i.e. using dummy variables technique)

Divide the dataset in to training (80%) and testing (20%). (Use random_state=1)

Standardize the input variables and use the same wherever required

Use the following algorithms to build a classifier

Logistic regression: Make sure that you include only those variables which are significant (use trial and error method for the same)

Decision Trees

KNN

SVM

Wherever required, use trial and error method to identify optimal values for input parameters (like max depth in decision trees, no. of neighbors in KNN etc)

Using all the models Predict the target class for test dataset and populate the following metrics and report the same in a consolidated table

Accuracy

Sensitivity

Specificity

F1-score

AUC

Plot the ROC curves for all the models in a single plot and identify the best model using the same chart

Justify your choice of classifier

