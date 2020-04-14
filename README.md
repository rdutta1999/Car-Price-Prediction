# Car-Price-Prediction
Predicting the Price of Cars based on its features.

The Dataset can be downloaded from [Used Cars Price Prediction](https://www.kaggle.com/avikasliwal/used-cars-price-prediction/download).

I cleaned the Dataset by removing the unncessary columns/features and filling out the missing values with the corresponding means/medians depending on the standard deviation of the particular feature. 

After this, I trained a number of Regression models such as **Random Forest Regressor**, **Gradient Boosting Regressor** and **XGBoost Regressor**.
Out of these, I chose the best model, in this case, **Gradient Boosting Regressor**.

I then loaded the Test Data, and cleaned it in accordance to the Training Data, and performed inference on it.
