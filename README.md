# Unit-10-Time-Series-Homework
The Homework consists of 2 main parts:
- Time Series Forecasting
- Linear regression modelling


## Time Series Forecasting

The notebook uses the data from [cad_jpy.csv](cad_jpy.csv) and then on the data applies:
- Hodrick-Prescott Filter to decompose the data into trend and noise.

- Forecasting returns using ARMA model but was concluded that model is not a good fit.

- Forecasting returns using ARIMA model which predicted the Japanese Yen will have a price reduction in the near future.

- Using the GARCH Model to forecast the volatility in the returns which forecasted that volatity will increase in the near term.

## Linear Regression Modelling

The notebook uses the data from [cad_jpy.csv](cad_jpy.csv) and then on the data applies:

- Seasonal Effects with Sklearn Linear Regression
- Split the data into training and testing data
- Predictions using the testing data
- Performs the evaluation of the model based on the results.

