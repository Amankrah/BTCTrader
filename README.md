# BTC Trader: An Automated Bitcoin Trading Bot

## Overview

BTC Trader is an automated trading bot designed to operate in the Bitcoin market. This project leverages machine learning algorithms to make buying and selling decisions. It uses daily Bitcoin price data along with technical indicators such as RSI, Bollinger Bands, and MACD to make predictions.

## Features

- **Data Collection:** The bot uses historical BTC/USD data from Yahoo Finance.
- **Data Preprocessing:** Includes feature engineering and data normalization.
- **Machine Learning Model:** Uses a Deep Q-Network (DQN) for action selection (Buy, Hold, Sell).
- **Paper Trading:** Simulates trading in real-time using ccxt to fetch real-time data from Binance.
  
## Installation

1. Clone this repository to your local machine.
   ```
   git clone <repository_url>
   ```
   
2. Navigate to the project directory.
   ```
   cd path/to/project
   ```
   
3. Install the required packages.
   ```
   pip install -r requirements.txt
   ```

## Dependencies

- pandas
- NumPy
- TensorFlow
- scikit-learn
- ccxt
- TA-Lib

## How to Use

1. **Data Preparation:** Download the BTC/USD historical data from Yahoo Finance and place it in the `data` folder.

2. **Training the Model:** Run the `BTCTrader.ipynb` notebook to train the model. The notebook includes code for data preprocessing, training, and evaluation.

3. **Paper Trading:** The notebook also includes a section on paper trading, which simulates how the bot would perform in real-time.

## File Structure

- `BTCTrader.ipynb`: Jupyter notebook containing the main code.
- `data/BTC-USD.csv`: Sample historical data for BTC/USD.
- `README.md`: This file.
- `requirements.txt`: File containing the list of dependencies.

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
