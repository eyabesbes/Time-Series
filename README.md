# Time Series Analysis and Forecasting of Bitcoin (BTC) and Ethereum (ETH) Prices

This repository contains a comprehensive analysis and forecasting project for Bitcoin (BTC) and Ethereum (ETH) prices using time series analysis techniques. The project is implemented entirely in Jupyter Notebooks, providing an interactive and easily understandable approach to analyzing cryptocurrency price trends.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Techniques and Models](#techniques-and-models)
- [Usage](#usage)
- [Results](#results)

## Introduction

The cryptocurrency market is highly volatile and unpredictable. This project aims to explore and forecast the price trends of Bitcoin and Ethereum using time series analysis. By leveraging statistical and machine learning models, it provides insights into the historical and future performance of these cryptocurrencies.

## Dataset

The dataset used in this project includes historical price data for Bitcoin (BTC) and Ethereum (ETH). The data may include:
- Open, high, low, and close prices
- Volume data
- Market capitalization

Details about the data source and preprocessing steps are included in the notebooks.

## Techniques and Models

This project employs the following techniques and models for time series analysis and forecasting:
- Exploratory Data Analysis (EDA)
- Stationarity tests (ADF, KPSS)
- Autoregressive Integrated Moving Average (ARIMA)
- Seasonal Decomposition of Time Series (STL)
- Long Short-Term Memory (LSTM) neural networks
- Prophet forecasting model

## Usage

To run the notebooks and reproduce the results:
1. Clone the repository:
   ```bash
   git clone https://github.com/eyabesbes/Time-Series.git
   cd Time-Series
   ```
2. Ensure you have Python installed, and create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install the required dependencies when necessary:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Navigate to the desired notebook to explore the analysis and results.

## Results

The results of the analysis include:
- Trend and seasonality decomposition
- Forecasted prices for Bitcoin and Ethereum
- Performance metrics for each forecasting model

Visualizations and detailed explanations are provided within the notebooks.
