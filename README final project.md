Capstone-Project-Final report
House Market Prediction and Analysis
This project analyzes historical housing market data alongside S&P 500 index trends to model and predict house prices. It explores various machine learning and statistical techniques, including ARIMA and regression models, to identify relationships between financial markets and real estate prices.

Table of Contents
About the Dataset
Features
Installation
Usage
Visualization
Prediction Models
Results
Future Work
About the Dataset
Zillow Housing Data: Contains historical monthly house price trends for various regions in the U.S.
S&P 500 Data: Historical price data of the S&P 500 index.
The datasets are sourced from:

Zillow Housing Market Data: Metro Zillow Data
S&P 500 Historical Data: S&P Data
Features
Data cleaning and preprocessing:

Removal of unnecessary columns.
Handling missing values with interpolation.
Conversion of data types and reindexing.
Data alignment and merging:

Align housing and financial market data by date.
Synchronize timeframes for meaningful analysis.
Time series analysis:

Evaluate historical trends.
Forecast future values using lagged predictors.
Prediction models:

ARIMA: Focused on time series with external regressors.
Machine Learning: Includes Random Forest, Gradient Boosting, and Linear Regression.
Define best model:

ARIMA model delivers best results with a MAE of 1842 for the city house prices of Aberdeen, SD.
Multiple citys can be chosen for evaluation and predicting future house prices
Installation
To run this project locally:

Clone the repository:
git clone https://github.com/JaFaSch/house-market-prediction.git
Link to Jupyter Notebook: https://github.com/JaFaSch/Capstone-Project-20.1-Initial-Report-and-Exploratory-Data-Analysis-EDA-/blob/main/Zillow%20house%20price%20prediction.ipynb
