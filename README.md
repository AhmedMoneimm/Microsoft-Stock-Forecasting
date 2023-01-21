# Stock Forecasting LSTM

This notebook demonstrates how to use LSTM (Long Short-Term Memory) neural networks for stock price forecasting. It utilizes historical stock price data to train an LSTM model and make predictions on future stock prices.

## Dataset

The dataset used in this notebook is obtained from Yahoo Finance. To download the dataset, follow these steps:
1. Go to https://finance.yahoo.com/quote/MSFT/history/
2. Choose the time period.
3. Download the dataset (CSV format) by clicking on the link provided.

## Getting Started

1. Install the required dependencies by running the following command:
```
pip install pandas matplotlib numpy tensorflow
```
2. Open the `stock_forecasting_lstm.py` file in your preferred Python environment or Jupyter Notebook.

3. Run the notebook cells sequentially to train the LSTM model and make predictions.

## Notebooks Files

- `stock_forecasting_lstm.py`: The main notebook file that contains the code for loading the dataset, preprocessing the data, building the LSTM model, training the model, and making predictions.

## Usage

1. Open the notebook file `stock_forecasting_lstm.py`.

2. Modify the parameters such as the time period, window size, and model architecture according to your needs.

3. Run each cell in the notebook sequentially to train the LSTM model and make predictions.

4. The notebook will generate various plots, including training predictions, validation predictions, testing predictions, and recursive predictions.

## Results

The notebook provides visualizations of the model's predictions against the actual stock prices for different time periods. The training predictions, validation predictions, testing predictions, and recursive predictions are plotted to evaluate the performance of the LSTM model.

[Google Colab](https://colab.research.google.com/drive/1sTlRq5xTpv96r7NZx9WaaNjqUvG0B7U1).



