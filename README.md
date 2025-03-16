# Binary Rainfall Prediction Model

A machine learning model that predicts the occurrence of rainfall based on meteorological features.

## Project Overview

This project implements a binary classification model to predict whether rainfall will occur based on various weather measurements. Using a dataset of 2,190 observations with features such as cloud cover, sunshine hours, pressure, temperature, humidity, and wind patterns, the model achieves high accuracy in determining rain likelihood.

## Dataset

The dataset contains daily weather observations with the following features:
- Atmospheric pressure
- Maximum temperature
- Current temperature
- Minimum temperature
- Dewpoint
- Humidity
- Cloud cover
- Sunshine hours
- Wind direction
- Wind speed
- Rainfall (target variable: 1 = rain, 0 = no rain)

## Future Work

- Add feature engineering to create more predictive variables
- Develop a web API for real-time predictions
- Incorporate time-series analysis for temporal patterns

## Requirements

- Python 3.8+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
