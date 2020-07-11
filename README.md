# Time Seriers Analysis
Time Series Forecasting and Linear Regression Modeling analysis for Japanese Yen
![yen](images/dollar-yen.jpg)


## Background

The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.

## Prerequisites
Numpy

Pandas

Pathlib

sklearn.linear_model

sklearn.metrics

statsmodels

arch
### Time-Series Forecasting

loaded historical Dollar-Yen exchange rate futures data and ploted Yen futures settle prices.

![plot](images/yen-futures-settle-prices.png)



#### Using a Hodrick-Prescott Filter, decomposed the Settle price into a trend and noise. and ploted settle Vs trend 

![settle vs trend](images/settle-vs-trend.png)


#### Using futures Settle *Returns*, estimated an ARMA model.

![arma](images/arma-model.png)




and applied time series analysis and modeling to determine whether there is any predictable behavior.

1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
2. Forecasting Returns using an ARMA Model.
3. Forecasting the Settle Price using an ARIMA Model.
4. Forecasting Volatility with GARCH.


#### Linear Regression Forecasting


2. Fitting a Linear Regression Model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.
