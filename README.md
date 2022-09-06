# AutoForecastingVisual
PowerBI Custom Visual for Automatic Forecasting

This visual accepts as an input a timeseries dataset.
The timeseries dataset should contain two columns (one with data type: date or datetime and another one with data type: numeric).

Visual has the ability to handle several user settings like the following:
History Settings:
  - History steps, a number indicating the historical steps to take for training.
    Use -1 for all the history or any other positive number.
Forecasting Settings:
  - Forecasting steps, a number indicating the future steps to calculate for prediction.
    Use any positive number
Transform Settings:
  - Handle Data Frequency, an option for specifing the frequency observations in the dataset
    Use Automatically or any other option based on your dataset
  - Handle Timeseries Sign Values,  an option for specifing the signs of the values in the dataset
    Use Automatically or any other option based on your dataset
  - Handle Timeseries Decimal Values,  an option for specifing the decimal of the values in the dataset
    Use Automatically or any other option based on your dataset
  - Handle Timeseries Missing Values, an option for specifing the way of handling missing values in the dataset
    Use Automatically or any other option based on your dataset
