# Stock Price Prediction using Machine Learning

## Project Overview
I built a machine learning model to predict the stock price of **Apple Inc. (AAPL)** using historical stock market data. The model is based on **Linear Regression** and predicts the closing price of a stock based on features such as the opening price, high and low prices, trading volume, and moving averages.

## Dataset
I used the stock data for **Apple Inc. (AAPL)** from **January 2015** to **January 2023**. The data was downloaded using the **yfinance** library.

## Project Workflow
1. **Data Collection**: I used the `yfinance` API to download the stock price data.
2. **Data Preprocessing**: I cleaned the dataset by removing missing values and created new features like the 20-day and 50-day moving averages.
3. **Model Building**: I implemented a **Linear Regression** model to predict the closing price.
4. **Model Evaluation**: I evaluated the model using the **Mean Squared Error (MSE)** metric and visualized the actual vs predicted stock prices.

## Technologies Used
- Python
- yfinance
- Pandas
- Scikit-learn
- Matplotlib

## How to Run the Project

### Prerequisites
Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
