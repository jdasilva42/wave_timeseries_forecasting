# Timeseries forecasting - SARIMA

This use case focus on time series forecasting using Autoregressive Integrated Moving Average algorithm (ARIMA) with seasonality (SARIMA).

The dataset used is an extraction of wave amplitude, period and direction from French wave propagation model [MARC](https://marc.ifremer.fr/). 
"netcdf_to_pickle_format_Notebook" performs the netcdf to pickle transformation. The components U and V from wind are also transformed.

"Timeseries forecasting using SARIMA" contains:
* Introduction
* Import libraries
* Preprocessing data and load
* Check the seasonality
* Setup the hyperparameters
* Make predictions - week step
* Make predictions - month step
