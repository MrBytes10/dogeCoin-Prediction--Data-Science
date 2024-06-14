# Dogecoin Price Prediction with Machine Learning

This project implements a machine learning model to predict the price pattern and forecast the future price of Dogecoin, a popular cryptocurrency. The model utilizes historical price data and various technical indicators to make predictions.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Dogecoin, like other cryptocurrencies such as Ethereum and Bitcoin, has gained significant attention in recent years. This project aims to leverage machine learning techniques to analyze historical Dogecoin price data and predict future price trends. By utilizing a Random Forest Regressor and time series analysis with ARIMA, we can build a predictive model to forecast Dogecoin prices.

## Dataset

The dataset used in this project is stored in the `DOGE-USD.csv` file. It contains historical price data for Dogecoin, including the following columns:

- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume

## Dependencies

The following Python libraries are required to run this project:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

You can install these dependencies using pip:
This is the command: <b>pip install pandas numpy matplotlib seaborn scikit-learn statsmodels </b>

## Usage

1. Clone the repository:<b>git clone https://github.com/MrBytes10/dogeCoin-Prediction--Data-Science.git</b>
2. Navigate to the project directory: <b>cd dogeCoin-Prediction--Data-Science</b>
3. Run the Jupyter Notebook:<b>jupyter notebook</b>
4. Open the `dogeCoinPrediction.ipynb` notebook in Jupyter.

5. Follow the instructions in the notebook to execute the code cells and reproduce the results.

## Results

The project provides visualizations and predictions for Dogecoin price trends. The Random Forest Regressor is used to identify important features that influence the price, while the ARIMA model is employed for time series analysis and forecasting.

The predictions are plotted alongside the actual price data to assess the model's performance and provide insights into potential future price movements.

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.
