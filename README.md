# Bigmart-Sales-Demand-Prediction
Case Study related to Bigmart Sales Prediction or we can say simply Demand Forecasting for different Kind of Products

![image](https://user-images.githubusercontent.com/80028817/143681765-bae0d392-302a-491a-810a-d8b90c4f3bbf.png)

Big mart Sales prediction where the list of attributes like Item_Identifier, Item_Weight,Item_Fat_Content,.......,Outlet_Sales were given where we need to create an ML model that will predict the demand for next quarter.


Tasks performed
i)Missing data values identification and replacing it with appropriate values
ii)Data cleaning -identifying any data is missing in any of the  record or not , if missing filling it with appropriate details using feature engineering or research
iii)Label Encoding for categorical values to convert the string values in form of single digit so that it will be easy for machine learning models to apply the model and optimise
iv)Removing the unnecessary columns  according to my view- such as Item_Identifer dosen't seems to have relation with demand and Outlet Establishment year dosen't  act as decision variable that will affect sales or demand.

Imposing the model on cleaned dataset and trying to optimise the result with all the models to check which model is giving greater accuracy on the result obtained.
I applied Random Forest Regressor and Linear Regression Model for my task

