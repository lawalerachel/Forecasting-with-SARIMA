# Forecasting Mean Temperature using SARIMA
## Project Overview and Aim
This project aims to forecast the mean temperature in Delhi using Seasonal Autoregressive Integrated Moving Average (SARIMA) modeling. The analysis utilizes weather data collected in Delhi over a four-year period from January 2013 to April 2017. The dataset includes parameters such as mean temperature, humidity, windspeed, and mean pressure.
## Data Source
The dataset used in this analysis contains weather data collected in the city of Delhi from the period of 1st January 2013 to 24th April 2017.
## Tools
The analysis is conducted using the following tools and libraries:
- pandas (pd): Data manipulation and analysis library.
- matplotlib.pyplot (plt): Plotting library for visualization.
- statsmodels.api (sm): Module for estimating statistical models.
- pandas.plotting.autocorrelation_plot: Function for visualizing autocorrelation in time series data.
- statsmodels.graphics.tsaplots.plot_acf: Function for visualizing autocorrelation function (ACF) plots.
- statsmodels.graphics.tsaplots.plot_pacf: Function for visualizing partial autocorrelation function (PACF) plots.
- statsmodels.tsa.stattools.adfuller: Function for performing the Augmented Dickey-Fuller test for stationarity.
- pmdarima: Python package for auto ARIMA model selection and diagnostics.
- scipy.stats: Module within SciPy library for statistical functions and tests.
## Result
The analysis resulted in the following findings:
- Time series decomposition revealed seasonality in the dataset.
- Autocorrelation analysis indicated a significant autocorrelation structure.
- The Augmented Dickey-Fuller (ADF) test suggested that the data is not stationary.
- SARIMA modeling was found appropriate for forecasting mean temperature.
## Model Predictions
The SARIMA model was trained on the dataset, and predictions were made for the next 30 days of mean temperature in Delhi.These predictions can be further evaluated for accuracy and used for planning and decision-making purposes.
## Limitations
- The analysis assumes that the data is representative and accurate.
- External factors such as climate change or urbanization may influence the accuracy of the forecast.
- The model's performance may vary depending on the quality and quantity of available data.
