# Monthly-Gas-Production-Forecast
Time series Project

For this assignment, you are requested to download the Forecast package in R. The package contains methods and tools for displaying and analyzing univariate time series forecasts including exponential smoothing via state space models and automatic ARIMA modelling. Explore the gas (Australian monthly gas production)  dataset in Forecast package to do the following:

[Hint code]

install.packages("forecast")

library(forecast)

data<- forecast::gas

Read the data as a time series object in R. Plot the data (5 marks)
What do you observe? Which components of the time series are present in this dataset? (5 marks)
What is the periodicity of dataset? (5 marks)
HINT: Please use the dataset from January 1970 for your analysis.
Please partition your dataset in such a way that you have the data 1994 onwards in the test data.
Is the time series Stationary? Inspect visually as well as conduct an ADF test? Write down the null and alternate hypothesis for the stationarity test? De-seasonalise the series if seasonality is present? (20 marks)
Develop an initial forecast for next 20 periods. Check the same using the various metrics, after finalising the model, develop a final forecast for the 12 time periods. Use both manual and auto.arima (Show & explain all the steps) (20 marks)
HINT: You can apply auto.arima(Train_data (refers to the train data set), seasonal=TRUE if seasonality is present in the data, FALSE is seasonality is not present.)
Report the accuracy of the model (5 marks)
