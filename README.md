# Google_Stocks

## Stock Price Prediction with LSTM and Attention Mechanism

## Introduction
In the rapidly evolving world of financial markets, accurate predictions are akin to a holy grail. As we seek more sophisticated techniques to interpret market trends, machine learning emerges as a beacon of hope. Among various machine learning models, Long Short-Term Memory (LSTM) networks have gained significant attention. When combined with the attention mechanism, these models become even more powerful, especially in analyzing time-series data like stock prices. This article delves into the intriguing world of LSTM networks paired with attention mechanisms, focusing on predicting the pattern of the next four candles in the stock price of Alphabet Inc. (GOOG), utilizing data from Yahoo Finance (yfinance).

## Project Overview
This project aims to predict the next 4 days' stock prices of Google (Alphabet Inc., GOOG) using historical data from January 2020 to June 2024. The data is sourced from Yahoo Finance.

## Prerequisites
- Python 3.7 or higher
- Jupyter Notebook

## Installation
1. **Download the Files**: First, download the `LSTM_Tensorflow_GOOGLE_Stocks.ipynb` file and the `requirements.txt` file from this repository.

2. **Install Dependencies**: Open a terminal window or shell where the files are kept and run the following command to install all the necessary packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Open the Jupyter Notebook**: Launch Jupyter Notebook and open the `LSTM_Tensorflow_GOOGLE_Stocks.ipynb` file.

2. **Run All Cells**: Execute all cells in the notebook to get the output at once. This will preprocess the data, train the LSTM model with the attention mechanism, and predict the stock prices.

3. **View the Results**: At the end of the notebook, you will see the graph displaying the candle patterns and the predicted stock prices for the next 4 days.

## Data Source
The historical stock price data is obtained from Yahoo Finance for the ticker symbol GOOG (Alphabet Inc.).

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## Acknowledgements
Special thanks to the developers of the libraries used in this project, including TensorFlow, Keras, and yfinance.
