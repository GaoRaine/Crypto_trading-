# Crypto_trading-

This repository contains detailed information on two trading strategies we are testing. The focus is on analyzing and developing robust trading models for the following currencies and cryptocurrency pairs:

- Bitcoin (BTCUSD)
- Ethereum (ETHUSD)
- Euro (EURUSD)
- Japanese Yen (USDJPY)

## Data Collection

Data for the aforementioned assets has been collected over the period from June 1, 2024, to March 31, 2025. The data is collected form Financial Model Prep (FMP). This comprehensive dataset serves as the foundation for our trading strategy analysis and backtesting.

## Validation Period

The validation period for testing our strategies is set from January 1, 2025, to February 28, 2025, while the testing period is set from March 1, 2025 to March 31, 2025. This timeframe is crucial for assessing the effectiveness of the strategies under different market conditions.

## Trading Strategies

We are currently testing the following two strategies:

1. **XGBoost Strategy**
   - Detailed in [Xgboosting_Strategy_code.ipynb](Xgboosting_Strategy_code.ipynb): This notebook outlines our approach using the XGBoost machine learning algorithm to predict price movements and execute trades.

2. **Volume Profile Strategy**
   - Documented in [VolumeProfile_strategy.ipynb](VolumeProfile_strategy.ipynb): This notebook explains how we use volume profile analysis to identify key price levels for trade execution.

## Results

Trading logic and backtest results for each strategy are provided in the respective notebooks. These results help in understanding the performance and potential adjustments needed for each strategy.
