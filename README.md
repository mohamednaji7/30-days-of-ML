# 30-days-of-ML
30 days of ML is a Kaggle in class competition which we built regression models to predict and minimize root mean square error       
## Random Forest Regressor Model 
- it's first model we tried 
- we did some feature optimization
- code  
-- import libraries  
-- load the data  
-- prepare the data(Transformation)  
-- getting best n_estimators feature's value  
-- fiting  
-- predict  
-- submitting it  
- Private Score: 0.73279 | Public Score: 0.73389
- file name: Random Forest Model.ipynb 

## XGBRegressor Model 
- code  
-- import libraries  
-- load the data  
-- prepare the data(Transformation): 1HotEncoding & Ordinal Encoding
-- fiting  
-- predict  
-- submitting it  
- Private Score: 0.71978 | Public Score: 0.72132
- file name: xgb-model.ipynb
## Tunning for XGBRegressor Model
- code  
-- import libraries  
-- load the data  
-- prepare the data(Transformation): 1HotEncoding & Ordinal Encoding  
-- tunning fucntion 
-- optuna studying  
- file name: tunning for xgb.ipynb

