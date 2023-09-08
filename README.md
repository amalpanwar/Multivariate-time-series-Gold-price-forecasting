# Multivariate-time-series-Gold-price-forecasting
## Overview

This project aims to forecast the price of gold based on a multivariate time series dataset that includes historical prices of GOLD, S&P 500, DXY (U.S. Dollar Index), Silver Price, and potentially other relevant features. We use a Long Short-Term Memory (LSTM) neural network, a type of recurrent neural network (RNN), for the forecasting task. LSTM networks are well-suited for capturing temporal dependencies in time series data.

## Dataset

- The dataset used in this project contains historical price data for the following variables:
  - GOLD Price
  - S&P 500 Index
  - DXY (U.S. Dollar Index)
  - Silver Price
  - Additional features (if any)

- The data should be organized in a CSV file with a timestamp (date) column and columns for each variable.

## Requirements

- Python 3.x
- TensorFlow (for LSTM modeling)
- Pandas
- NumPy
- Matplotlib (for visualization)
- Jupyter Notebook (optional, for running the provided notebooks)

You can install the required Python packages using pip:

```bash
pip install tensorflow pandas numpy matplotlib
