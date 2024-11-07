# ML Stock Market Prediction with ARIMA Integration

## Overview
This project explores the enhancement of stock price movement forecasting by combining technical indicators with machine learning models. The core innovation lies in integrating ARIMA (AutoRegressive Integrated Moving Average) time series forecasting with a RandomForest classifier to improve predictive accuracy.

## Key Features
- Integration of ARIMA forecasting with RandomForest classifier
- Comprehensive technical indicator analysis
- Performance comparison between baseline and ARIMA-enhanced models
- Visualization of model performance metrics
- Time horizon analysis (1-30 days prediction periods)

## Data
- **Source**: S&P 500 index data from Yahoo Finance
- **Time Period**: January 2020 to January 2023
- **Features**: Daily observations of Open, High, Low, Close prices, and Volume
- **Processed Features**: Exponentially smoothed closing prices

## Technical Indicators Implemented
- Relative Strength Index (RSI)
- Stochastic Oscillator
- Williams %R
- Moving Average Convergence Divergence (MACD)
- Rate of Change
- On-Balance Volume

## Models
### Baseline Model
- RandomForest classifier using only technical indicators

### Enhanced Model
- RandomForest classifier integrated with ARIMA forecasts
- Combines pattern recognition with time series forecasting

## Performance Metrics
- Accuracy
- Precision
- Recall
- F1 Score

## Results
The ARIMA-enhanced model demonstrated superior performance across all metrics:
- Higher and more stable accuracy
- Improved precision in identifying positive price movements
- Better recall in detecting actual positive movements
- More balanced F1 scores



## Future Improvements
- Hyperparameter tuning for both ARIMA and RandomForest models
- Integration of neural networks (especially LSTMs)
- Addition of macroeconomic factors and more financial indicators
- Development of a real-time prediction system
- Web application deployment using Flask/Docker
- Cloud service integration (AWS/Azure)

## References
- Hardikkumar. (2024, May 31). Stock market forecasting using time series analysis with Arima Model. Analytics Vidhya.
- Khaidem, L., Saha, S., & Dey, S. R. (2016, April 29). Predicting the direction of stock market prices using random forest. arXiv.org.

## Author
Haechan Oh
Minerva University
