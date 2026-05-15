# Stock Price Prediction Using Machine Learning

This project predicts the next day's stock closing price using historical stock market data from Yahoo Finance and Machine Learning techniques.

The project uses Python libraries such as Pandas, yfinance, Matplotlib, and Scikit-learn to fetch, analyze, visualize, and model stock data.

## Objective

The main goal of this project is to:

* Fetch historical stock data using the yfinance API
* Use stock features such as Open, High, Low, and Volume
* Predict the next day's closing price
* Train a Linear Regression model
* Compare actual vs predicted prices using visualizations

## Technologies Used

* Python
* Pandas
* yfinance
* Matplotlib
* Scikit-learn
* Google Colab

## Dataset Source

Stock market data was retrieved from Yahoo Finance using the yfinance Python library.

Example stock used:

* Apple (AAPL)

## Features Used for Prediction

The following stock market features were used:

* Open Price
* High Price
* Low Price
* Volume

### Target Variable

* Next Day Closing Price

## Machine Learning Model

The project uses:

* Linear Regression

The model learns patterns between stock features and future closing prices.

## Project Workflow

```text
Fetch Stock Data
        ↓
Explore Dataset
        ↓
Prepare Features & Target
        ↓
Train/Test Split
        ↓
Train Linear Regression Model
        ↓
Make Predictions
        ↓
Visualize Results

## Data Visualization

The project includes:

* Actual vs Predicted Stock Price Plot
* Trend Visualization using Matplotlib

## Skills Learned

Through this project, the following skills were practiced:

* Time Series Data Handling
* Regression Modeling
* Data Fetching using APIs
* Machine Learning Basics
* Data Visualization
* Model Evaluation

## Libraries Installation

Install required libraries using:

```python
pip install yfinance

## How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook
2. Install required libraries
3. Run all cells
4. View predictions and visualizations

## Future Improvements

Possible improvements include:

* Using Random Forest Regressor
* Using LSTM Deep Learning models
* Adding more technical indicators
* Improving prediction accuracy
**
## Conclusion****

This project demonstrates how Machine Learning can be used to analyze historical stock market data and predict future stock prices. It provides hands-on experience with regression models, API-based data collection, and visualization techniques.


