# Solar Energy Time Series Forecasting
open code in google colab: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fmJkz4sJHLfqAjP4M8zJ_wL15Mdox2x2?usp=sharing)
## Overview
This project applies time series regression techniques to forecast solar energy production using historical weather and energy data recorded at 15-minute intervals between 2017 and 2022.

## Dataset
The dataset includes solar energy capture along with meteorological variables such as sunlight intensity, temperature, rainfall, cloud coverage, and length of daylight.

## Methodology
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature selection using correlation analysis
- Model development using Linear Regression and Random Forest Regressor
- Model evaluation using R², MAE, and MSE
- Forecasting average solar energy production for January 2026

## Models Used
- Linear Regression
- Random Forest Regressor

## Results
The Random Forest model outperformed Linear Regression across all evaluation metrics and was therefore selected for forecasting future energy production.

## Forecast
The model was used to forecast the average solar energy production for January 2026 based on historical January conditions.

## Notebook
The complete implementation is available in the notebook directory.

## Author
Jimson James
