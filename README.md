# S&P 500 Stock Market Analysis
This project analyzes historical S&P 500 stock market data to build a machine learning model that predicts daily price movements.

## Overview
The notebook downloads historical S&P 500 data using Yahoo Finance API, processes the data to create features and targets, and implements a Random Forest classifier to predict whether the market will go up or down the next day.

## Features
- Downloads and processes S&P 500 historical data from Yahoo Finance

- Creates technical features like Open, Close, High, Low, and Volume

- Generates target variable (whether price increases the next day)

- Implements a Random Forest classification model

- Evaluates model performance using precision scoring

## Requirements
- Python 3+

- pandas

- yfinance

- scikit-learn

- matplotlib

## Installation
`pip install yfinance`

## Usage
1. Run the Jupyter notebook `SP500.ipynb`
2. The notebook will:
- Download S&P 500 historical data
- Preprocess and feature engineer the dataset
- Train a Random Forest Classifier
- Evaluate model performance

## Model
The model uses a Random Forest classifier with:
- 1000 estimators
- Minimum samples split of 100
- Random state set to 1 for reproducibility

## Results
The model achieves a precision score of approximately 58% on the test set, demonstrating predictive capability better than random guessing for market direction prediction.

## File Structure
- `SP500.ipynb` - Main analysis notebook
- `sp500.csv` - Historical data file

## Note
This is an educational project for financial data analysis and machine learning. The predictions should not be used for actual trading decisions without further validation and risk assessment
