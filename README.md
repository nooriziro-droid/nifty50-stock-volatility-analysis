# NIFTY 50 Stock Volatility Analysis and Forecasting

## Overview

This project analyses NIFTY 50 daily stock data from 2015–2025 to study return patterns and volatility using time series methods.

## Objectives

- Analyse NIFTY 50 price and return movements
- Test for stationarity and ARCH effects
- Model time-varying volatility
- Forecast future volatility

## Methods

- Log Returns
- Augmented Dickey-Fuller (ADF) Test
- ARCH-LM Test
- GARCH(1,1) Model
- 10-Day Volatility Forecast

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- ARCH

## Results

The fitted GARCH(1,1) model was used to forecast NIFTY 50 volatility for the next 10 trading days.

Forecasted volatility increased from 0.598 to 0.695 over the forecast horizon.

## Project Structure

- `NIFTY50_Stock_Volatility.ipynb` – Complete analysis and forecasting
- `images/` – Project visualisations
