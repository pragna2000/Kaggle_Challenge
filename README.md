# Kaggle_Challenge
* This repository is an attempt to solve the Kaggle Competition 'House Prices'. The challenge was to use any regression model to prodict house prices in Ames, Iowa using 79 vairables like zoning, lot size, the type of neighborhood, condition the house was in, etc. In this notebook, there are three regression models that predict the prices of the houses based on the given information.

## The DataSet
* Instances: 1460
* Features: 79
* 957.39 kB

## Summary of Workdone

* Data cleaning was done to get rid of any Nan vairbales. 
* As these variables did not exist in the orginial dataset, they either had to be removed or replaced.
* Empty or unnecessary columns were also removed. 
* Data procssessing consisted of ecoding and normalizing data 
* As well as finding out what variables were the most impactful to the dataset. 

* Models
  - XGBoostRegression
  - Random Forest Regressor
  - Decision Tree Regressor

* Performace
  - XGB R-squared: 0.85
  - Random Forest R-squared: 0.84
  - Decision Tree : R-squared: 0.50
 
## Conclusion
- Based on the model's r-score, the best performing model is the XGB. 

# Sources 
- https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
- https://machinelearningmastery.com/xgboost-for-regression/
