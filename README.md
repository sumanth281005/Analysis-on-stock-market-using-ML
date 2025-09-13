# Stock Market Prediction Project

## Overview

This project applies Machine Learning regression algorithms to predict stock market portfolio opening values.
The dataset contains 516 instances with 18 financial features including stock indices, commodities, cryptocurrencies, bond yields, and currency exchange rates.

## Objective

* Analyze financial data to study price trends and correlations.
* Predict PortfolioOpen values based on other financial metrics.
* Identify the best-performing machine learning model for accurate forecasting.

## Dataset

* Instances: 516
* Features: 18
* Target Variable: PortfolioOpen

## Best Model

Bagging achieved the highest R² of **0.9622** with the lowest MAPE of **0.0108**.
Other strong performers were Random Forest, Gradient Boosting, and XGBoost, but Bagging gave the most reliable results across all splits.

## Key Results

* Bagging and Random Forest proved to be the most reliable models.
* Ensemble methods consistently outperformed simpler models such as Linear Regression and KNN.
* Careful preprocessing (handling missing values and multicollinearity) improved model stability and accuracy.

## Future Scope

* Incorporating macroeconomic indicators.
* Using advanced time-series models such as LSTM or GRU.
* Applying hyperparameter tuning and feature engineering for better performance.

## Business Impact

* Accurate forecasting of portfolio opening values strengthens investment strategies.
* Helps in better risk management and decision-making.
* A hybrid of ensemble and neural approaches can ensure robust portfolio prediction.

## Resources

Google Colab Notebooks:
[https://colab.research.google.com/drive/12ZJJ\_fgQi8yAmF-T2qXtK4fJxMwM0ODc](https://colab.research.google.com/drive/12ZJJ_fgQi8yAmF-T2qXtK4fJxMwM0ODc)
[https://colab.research.google.com/drive/18\_yRnN44ro6rRs8mSxNgm967AokjIgAR](https://colab.research.google.com/drive/18_yRnN44ro6rRs8mSxNgm967AokjIgAR)

*"Smart ensembles today, smarter hybrids tomorrow — building the future of portfolio prediction."*
