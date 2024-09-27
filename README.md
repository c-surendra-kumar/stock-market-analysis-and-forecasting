# Stock Market Analysis and Forecasting

This project focuses on analyzing and forecasting stock market trends using both fundamental and technical analysis techniques. Stock prediction is a challenging task with significant potential in guiding investment decisions. By exploring historical stock data and leveraging analysis techniques, this project aims to provide insights into stock price movements and trends.

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Methodology](#methodology)
- [Modules](#modules)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The stock market is a collection of buyers and sellers trading ownership of companies through stocks (shares). This project explores methods of stock market prediction by using data from several major companies: **Google, Microsoft, IBM, and Amazon**.

Two primary approaches to stock market prediction are used:
1. **Fundamental Analysis**: Focuses on a company’s intrinsic value, analyzing factors such as market position, expenses, and growth rates.
2. **Technical Analysis**: Relies on historical stock data to identify patterns and predict future price movements.

In this project:
- **Module I** focuses on stock data analysis.
- **Module II** forecasts stock prices using machine learning models.

## Datasets
The project uses the stock data of four major companies:
1. **Google**
2. **Microsoft**
3. **IBM**
4. **Amazon**

The datasets include various stock attributes, such as:
- Open
- High
- Low
- Close
- Volume

## Methodology
The project is divided into two key parts:
1. **Data Analysis**:
   - Visualizing stock data trends (open, high, low, close, volume).
   - Identifying correlations between different attributes (e.g., close and open prices).
   - Exploring patterns, seasonality, and trends in stock prices.
   
2. **Stock Forecasting**:
   - Using machine learning models to forecast future stock prices based on historical data.
   - Models used for forecasting include:
     - ARIMA
     - LSTM (Long Short-Term Memory)

## Modules

### Module I - Analysis
- **Objective**: To analyze stock data from the provided datasets.
- **Tasks**:
  1. Visualize the distribution of opening and closing prices.
  2. Analyze the correlation between different attributes.
  3. Compare "High" and "Close" prices for each dataset.
  4. Explore trends and seasonality.

### Module II - Forecasting
- **Objective**: To predict future stock prices using machine learning models.
- **Tasks**:
  1. Train and test forecasting models (e.g., ARIMA, LSTM) on stock data.
  2. Evaluate model performance and accuracy.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/stock-market-analysis.git
