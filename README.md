# House-Price-Prediction-
This is  a machine learning model which predicts the house price considering several parameters. 
# Contents
## Problem Defination
## Data set
## Evaluation
## Feature Engineering
## Model selection
## Result

# Problem Defination:
  Predict the house Price based on several different parameters
  
# Data set:
  data set is downloaded from  house price prediction competition on kaggle.com. https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
  it contains 3 files in it
  
  train.csv - the training set
  test.csv - the test set
  data_description.txt - full description of each column.
  
# Evaluation:
  Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.
  
# Feature Engineering
  in this step i created a two special functions. first function which directly detects the numerical column and check for NA values in column if any present then it automatically fill with median value of that column.
  second function: it converts all categorical variables into numerical ones.
  
# model selection:
  for this problem i experimented with different regression algorithms,after experiment i came to know that xgboost algorithm with parameter tunning is suited best for the parameter.
  
# Result:
  the Root-Mean-Squared-Error value obtained using xgboost algorithm is 0.1410  
