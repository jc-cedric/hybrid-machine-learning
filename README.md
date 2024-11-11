# Hybrid-machine-learning

## About the dataset

The given dataset consists of the historical stock data for Apple Inc. from the past year. It includes daily records with key features such as Date, Open, High, Low, Close, and Volume.

## About the problem to solve

The primary goal is to build a predictive model that can accurately forecast the next 10 days of Apple Inc.’s stock prices.

Given the complexity of stock market data, which can exhibit both short-term sequential dependencies and broader trends, using a single model type may not suffice. The challenge lies in capturing these intricate patterns effectively.

## Chosen approach

A hybrid modelling approach combining LSTM (to capture time dependencies and short-term trends) and Linear Regression (to capture long-term trends) will be employed.
