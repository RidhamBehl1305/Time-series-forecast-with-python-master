# Time-series-forecast-with-python-master
Defining the problem

This repository contains a series of analysis, transforms and forecasting models frequently used when dealing with time series. The aim of this repository is to showcase how to model time series from the scratch, for this we are using a real usecase dataset (Beijing air polution dataset to avoid perfect use cases far from reality that are often present in this types of tutorials.)

Dataset

The dataset used is the Beijing air quality public dataset. This dataset contains polution data from 2014 to 2019 sampled every 10 minutes along with extra weather features such as preassure, temperature etc. We decided to resample the dataset with daily frequency for both easier data handling and proximity to a real use case scenario (no one would build a model to predict polution 10 minutes ahead, 1 day ahead looks more realistic.)

Analysis and transforms

Time series decomposition

Level

Trend

Seasonality

Noise

Stationarity

AC and PAC plots

Rolling mean and std

Dickey-Fuller test

Making our time series stationary

Difference transform

Log scale

Smoothing

Moving average

Models tested

Autoregression 

Moving Average 

Autoregressive Moving Average 

Autoregressive integraded moving average 

Seasonal autoregressive integrated moving average 

Bayesian regression 

Lasso 

SVM 

Randomforest 

Nearest neighbors 

XGBoost 

Lightgbm 

Prophet 

Long short-term memory with tensorflow (LSTM)

DeepAR

Forecasting results

We will devide our results wether the extra features columns such as temperature or preassure were used by the model as this is a huge step in metrics and represents two different scenarios. Metrics used were:

Evaluation Metrics

Mean Absolute Error (MAE)

Mean Absolute Percentage Error (MAPE)

Root Mean Squared Error (RMSE)

Coefficient of determination (R2)

![image](https://user-images.githubusercontent.com/106107245/208178006-f37ac950-7e20-4bd6-b897-a1c10cc38e42.png)


Live Link

https://github.com/RidhamBehl1305/Time-series-forecast-with-python-master/blob/main/03-Results_analysis%26discussion.ipynb
