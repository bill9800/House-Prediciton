# House-Prediciton

Data : [Kaggle Prices-Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Simple version

Build a standard version for furture updating.

Kaggle board score : 0.30619

Model : XGboost (also do simple comparsion with linear model)

Preprocessing : Select 7 important features and clean the data


## Complex version 

Current Kaggle board score : 0.21777

Model : 
- Categorical data : XGboost (tree base)
- Numerical data : Regression or deep learning (updating)
- Use a model to combine two kinds of datas results.(updating)
- Preprocessing : Combine highly related categorical data to 22 features by observing the correlation matrix
