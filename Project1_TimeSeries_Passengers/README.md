In this notebook we can see the decomposition of the dataset: trend, seasonality and residuals. The Auto-ARIMA library has been used in order to optimize the search for the best ARIMA parameters and adjust an efficient model to the Air-passengers dataset. 

Dataset: Air Passengers is a classic dataset about monthly number of passengers from the time period of 1949 - 1960. The dataset is a open source can be found on platforms such as Kaggle, UCI. 

Methodology: It has been used the AUTO-ARIMA method to easy the prediction of the time series searching for the best combinations of the ARIMA (p,d,q) parameters. 

Results: It was set the parameters and the AIC metric has been used to evaluate the model. After that the model was tested using with and without the 'stepwise' option in order to find the best adjustment. Finally the prediction was tested using the model with the data of 1960 which after was compared with the original data to demonstrate the model efficiency. 


