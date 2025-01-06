Comparative Analysis of Stock Price Prediction Models: A Study Using Linear Regression, LSTM, GRU:

This project focuses on analyzing historical stock market data for various companies and implementing predictive models to forecast future prices. The analysis includes data cleaning, visualization, and the use of machine learning models such as GRU, LSTM, and Linear Regression for price prediction.

Methods

Data Collection:

Historical stock market data is fetched using the yfinance library for a period of 10 years.

Data Analysis:

Descriptive statistics, null values, and duplicate data are examined for quality.

Visualizations include closing prices, sales volume, and daily returns.

Moving Averages:

10-day, 20-day, and 50-day moving averages are computed for trend analysis.

Prediction Models:

GRU (Gated Recurrent Unit): A sequential neural network architecture tailored for time series data.

LSTM (Long Short-Term Memory): A deep learning model capable of capturing long-term dependencies.

Linear Regression: A baseline predictive model for price forecasting.

Evaluation Metrics:

Models are evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).

Future Price Forecasting:

Predictions for the next 30 days are generated based on the trained model with the best performance.

Input

File Format

CSV: Historical stock data including columns like:

Date: Timestamp for the data.

Open: Opening price.

Close: Closing price.

High: Daily high.

Low: Daily low.

Volume: Number of shares traded.

Libraries

pandas for data manipulation.

numpy for numerical computations.

yfinance for fetching stock data.

matplotlib and seaborn for visualizations.

keras and tensorflow for building neural networks.

scikit-learn for preprocessing and evaluation metrics.
