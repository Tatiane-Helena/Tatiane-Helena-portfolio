# 📈 Transport of Passengers Prediction 

## 🎯 Objective

The goal of this project is to analyze historical data of transport of passengers within an airline business in US. It has been used Time series analysis ARIMA to identify trends and seasonality and build a forecasting model to predict future transport of passengers.

## 💡 Business Value

The time series analysis can support better decision-making in areas such as isentify seasonal patterns in sales, staff planning and future demand forecasting. 

---

## 📂 Dataset

* Source: Air Passengers is a classic dataset that contains number of passengers transportation from the time period of 1949 - 1960. The dataset is an open source can be found on platforms such as Kaggle, UCI. 
* Time period: 1949 - 1960 
* Features:
- Date&Time
- Number of passengers (by Month) 

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib / Seaborn
* Statsmodels
* Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Cleaning

* Converted date column to datetime format
* Checked for missing values
* Aggregated data by time period

### 2. Exploratory Data Analysis (EDA)

* Visualized passengers transportation trends over time
* Identified seasonality patterns
* Observed overall growth/decline trends

### 3. Time Series Modeling

* Checked stationarity of the series
* Applied differencing where necessary
* Built ARIMA model

### 4. Forecasting

* It has been used the AUTO-ARIMA method to easy the prediction of the time series searching for the best combinations of the ARIMA (p,d,q) parameters. 
* Generated future transport of passengers predictions
* Compared predicted vs actual values

---

## 📈 Results & Insights

* Identified clear seasonal patterns in passengers transportation
* ARIMA decomposition successfully captured trend and seasonality behavior
* Forecast provides a reasonable estimate of future demand
* The AIC metric has been used to evaluate the model. The prediction was tested using the model with the data of 1960 which after was compared with the original data to demonstrate the model efficiency. 


---


