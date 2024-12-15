# Capstone-Project-Final project

# House Market Prediction and Analysis

This project analyzes historical housing market data alongside S&P 500 index trends to model and predict house prices. It explores various machine learning and statistical techniques, including ARIMA and regression models, to identify relationships between financial markets and real estate prices.

---

## Table of Contents

- [About the Dataset](#about-the-dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Visualization](#visualization)
- [Prediction Models](#prediction-models)
- [Results](#results)
- [Future Work](#future-work)

---

## About the Dataset

1. **Zillow Housing Data**: Contains historical monthly house price trends for various regions in the U.S.
2. **S&P 500 Data**: Historical price data of the S&P 500 index.

The datasets are sourced from:
- Zillow Housing Market Data: [Metro Zillow Data](https://github.com/JaFaSch/house-market-prediction)
- S&P 500 Historical Data: [S&P Data](https://github.com/JaFaSch/house-market-prediction)

---

## Features

1. Data cleaning and preprocessing:
   - Removal of unnecessary columns.
   - Handling missing values with interpolation.
   - Conversion of data types and reindexing.

2. Data alignment and merging:
   - Align housing and financial market data by date.
   - Synchronize timeframes for meaningful analysis.

3. Time series analysis:
   - Evaluate historical trends.
   - Forecast future values using lagged predictors.

4. Prediction models:
   - ARIMA: Focused on time series with external regressors and stationary data
   - Machine Learning: Includes Random Forest, Gradient Boosting, and Linear Regression.
  
5. Define best model:
   - ARIMA model delivers best results with a MAE of 1842 for the city house prices of Aberdeen, SD.
   - Multiple citys can be chosen for evaluation and predicting future house prices

---

## Installation

To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/JaFaSch/house-market-prediction.git

Link to Jupyter Notebook: (https://github.com/JaFaSch/Capstone-Project-Jan-Schreder/blob/main/Zillow%20house%20price%20prediction%20Final%20capstone%20project.ipynb)
