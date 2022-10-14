# Time_Series_Analysis
In this project we will try to predict the stock prices in pseudo future using the basic statistical models .
We first check the staionarity of data using the dickey fuller test in the statsmodels library of python and then predict the stock prices of our model using the the inbuilt models of the statsmodels library in python like MA(moving average), AR(autoregressive model) and ARIMA(Autoregressive Integrated Moving Average Model) . We also check the seasonality of data by plotting the ACF(Auto correlation function), PACF(Partial Autocorrelation Function) and AIC(Aikake Information Criteria).
We have used the closing prices(daily basis) of apple(ticker: 'AAPL') stocks from yfinance website.
