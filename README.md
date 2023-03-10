# TESLA-stock-price-forecasting


# Topic
In this notebook I have gone throught the last year of Tesla's stock prices to understand that they have a downtrend over time and a seasonality that decreases over time. With the help of three time series forecasting models (ETS, SARIMA and Prophet) I was able to make predictions and compare my results cross model. For my ETS model I used and addutive method for both trend and seasonality, for the SARIMA model I used some AR and MA terms plus the differencing terms and with Prophet I accounted for the holidays seasonality in the data. The results lead me towards my ETS model : Holt Winter's seasonal trend which yielded the lowest errors and lowest AIC score. I then used my tuned ETS model to make forecasts of January 2023 which indicate yet a loss in the value of Tesla's stock options.

# Models
- ETS: Holt Winter's Seasonal method
- ARIMA : Seasonal ARIMA
- Prophet 

# Evaluation Metrics
- Mean Absolute Error
- Root Mean Squared Error
- Akaike Information Criterion

# Libraries
- numpy
- pandas
- scipy
- sklearn
- prophet
- statsmodels

# Data source
https://finance.yahoo.com/quote/TSLA/history?p=TSLA
