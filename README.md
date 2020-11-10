# Transaction Prediction Model

## Summary of the project

This was Kaggle competition based on Santanders customer transaction data https://www.kaggle.com/c/santander-customer-transaction-prediction. The task is to identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. Dataset contains 200 numerical features. Having large number of features and data being structured leads us to one candidate, Gradient Boosted Trees. The method will help us to analyze the feature importance of the data as well.

## Overview 

Here we first perform an exploratory analysis by looking at the distribution of features and visualizing the projected data in two dimensions using a random projection. Then we prepare n-fold cross validation split. We train a prediction model using Gradient Boosted Trees and rank/visualize their feature importance. 
Finally we report on various validation metrics including AUC, roc curve and average precision to measure the performance of the model.

