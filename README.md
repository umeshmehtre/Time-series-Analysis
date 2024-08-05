# Heart Rate Prediction Using Time Series Analysis

## Project Overview

This repository contains the code and documentation for a time series analysis project focused on predicting heart rate variations. The project utilizes advanced time series forecasting techniques, specifically the SARIMA (Seasonal AutoRegressive Integrated Moving Average) model, to analyze and predict heart rate patterns over time.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Data Preprocessing](#data-preprocessing)
5. [Time Series Analysis](#time-series-analysis)
6. [Model Development](#model-development)
7. [Results](#results)
8. [Conclusion](#conclusion)

## Introduction

Time series analysis is a powerful technique for understanding and predicting patterns in data collected over time. In this project, we apply time series analysis to heart rate data, aiming to forecast future heart rate variations. This type of analysis can be crucial in healthcare for monitoring patient health, detecting anomalies, and predicting potential cardiac events.

## Dataset

The project uses a CSV file containing heart rate data collected over time. Each entry in the dataset represents a heart rate measurement at a specific time point.

## Methodology

The project follows these main steps:

1. Data Preprocessing
2. Stationarity Check
3. Data Transformation
4. Model Building (SARIMA)
5. Prediction and Forecasting

## Data Preprocessing

1. Import necessary libraries (pandas, numpy, matplotlib, statsmodels)
2. Read the CSV file using pandas
3. Remove outliers from the dataset to improve model accuracy

## Time Series Analysis

1. Apply the Augmented Dickey-Fuller test to check for stationarity
2. If non-stationary, apply differencing to the data
3. Apply data transformation techniques
4. Re-run the Dickey-Fuller test to confirm stationarity

## Model Development

1. Build an Auto-Regressive model
2. Analyze Autocorrelation and Partial Autocorrelation Functions
3. Develop the SARIMA (Seasonal ARIMA) model
4. Fine-tune model parameters for optimal performance

## Results

The SARIMAX (Seasonal ARIMA with eXogenous variables) model provided the best predictions for heart rate variations. The model's performance is visualized in the project notebook, demonstrating its ability to capture both the trend and seasonality in the heart rate data.

## Conclusion

This project demonstrates the effectiveness of the SARIMA model in predicting heart rate variations. The SARIMAX model, in particular, proved useful when exogenous seasonality factors were present in the time series, providing reliable forecasts and predictions.
