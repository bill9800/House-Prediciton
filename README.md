# House-Prediciton

Data : [Kaggle Prices-Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## simple version

Build a standard version for furture updating.

Kaggle board score : 0.30619

Model : XGboost (also do simple comparsion with linear model)

Preprocessing : Select 7 important features and clean the data


## Complex version (still updating)

Current Kaggle board score : 0.21777

Model : 
- Categorical data : XGboost (tree base)
- Numerical data : Regression or deep learning (still trying)
- Use a model to combine two kinds of datas results.
- Preprocessing : Combine highly related categorical data to 22 features by observing the correlation matrix (will compare with PCA in the future), transform null data, do label encoder and feature transforms.

