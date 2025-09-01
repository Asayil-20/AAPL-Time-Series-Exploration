# AAPL Time Series Exploration and Forecasting

This repository contains my personal journey of exploring and forecasting **Apple's (AAPL) daily closing prices**. I went step by step, learning and applying different time series techniques, from data exploration to forecasting with Prophet.

---

## Project Overview

I started by understanding the dataset, exploring its trends, seasonality, and patterns.  
Then I cleaned the data, handled missing values, and applied various time series analysis techniques, including:

- Visualizing daily, monthly, and quarterly patterns
- Decomposing the series into trend, seasonality, and residuals
- Checking autocorrelation and partial autocorrelation
- Forecasting future prices using **Prophet**

This project was a hands-on learning experience that helped me strengthen my skills in **Python**, **pandas**, **matplotlib**, **statsmodels**, and **Prophet**.

---

## Key Steps

1. **Exploring the Data**  
   - Checked the structure, shape, missing values, and date range.
2. **Preparing the Data**  
   - Set the index to business-day frequency and handled missing values.
3. **Exploratory Analysis**  
   - Plotted daily closing prices and visualized monthly & quarterly seasonality.
4. **Seasonal Decomposition**  
   - Separated trend, seasonality, and residuals to better understand the series.
5. **Autocorrelation Analysis**  
   - Used ACF and PACF plots to study relationships in past data.
6. **Forecasting with Prophet**  
   - Built a 30-day forecast model, visualized predictions, and explored components.

---

## Tools & Libraries Used

- **Python**  
- **pandas** – for data manipulation  
- **matplotlib & seaborn** – for visualization  
- **statsmodels** – for decomposition and autocorrelation analysis  
- **Prophet** – for forecasting future stock prices  
- **yfinance** – for fetching historical stock data

---

## How to Run

1. Make sure you have **Python** installed (version 3.8 or higher recommended).  
2. Install the required libraries:
```bash
pip install pandas matplotlib seaborn statsmodels yfinance prophet
