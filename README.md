# Timeseries-Forecasting
Using TimeSeries Generator and LTSM

## About

This is a Time series Forecasting LTSM model which trains on a series of data and then after analysing the dataset.

It tries to predict the upcoming trend of the dataset

 
### Dataset
 
***For training and testing this model, the data has been taken from the[Federal Reserve Economic Data](https://fred.stlouisfed.org/)***

### Note

**This model is trained and tested on two dataset:**

* Retail Sales: Clothing and Clothing Accessory Stores 

* Effective Federal Funds Rate 

## Graphical Representation
  
 **Retail Sales: Clothing and Clothing Accessory Stores**
 
* Loss Vs Val_Loss

<img src="Sample Images/VAL_LOSS_REtail.png">
 
 * Prediction on The Test set
 
 <img src="Sample Images/Predvsactual.png">
 
 
**Effective Federal Funds Rate**

* Fed Rates Graph

<img src="Sample Images/Fed_Rates.png">

* Loss Vs Val_Loss

<img src="Sample Images/Val_Loss_Fed.png">
 
 * Predicted Trend
 
 <img src="Sample Images/Screenshot from 2020-05-25 22-17-01.png">
 
 ### Update

~~***Right Now, I am learning about the time series forcasting, as i will learn more the model will be tuned more***~~

 * **Dataset stationarity is achieved**
 
 * **Agumented Dickey Fuller Test is implemented to chech whether  the dataset is stationary or not**
 
 * **Various Methods like "Rolling mean", "Difference", "Seasonal Difference" is applied to the dataset to remove any seasonality or trend**
 
 ### Note
 
 ***Inversion of dataset and log inverse dataset will be implmented as soon as I done with the code***
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
