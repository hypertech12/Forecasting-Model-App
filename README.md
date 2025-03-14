# 📈 Financial Forecasting Model 

This Streamlit app simulates and compares two predictive financial models (Model A & Model B) using historical **S&P 500** stock data. The models generate forecasts with different noise levels, and their performance is evaluated using **error metrics, directional accuracy, latency measurements, and a t-test**.

## 🚀 Features

- **Fetch Historical Data**: Automatically downloads S&P 500 data using Yahoo Finance (`yfinance`).
- **Simulated Model Predictions**: Generates forecasts with slight variations in noise.
- **Traffic Splitting**: Assigns predictions to groups (A/B) for comparison.
- **Error & Accuracy Analysis**: Computes percentage errors, directional accuracy, and latency.
- **Statistical Testing**: Uses a **t-test** to determine if one model significantly outperforms the other.
- **Visualization**:
  - **Scatterplot** comparing both predictions against actual closing prices.
  - **Data Table** preview of processed results.
## Open in Streamlit
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://rcforecastingmodel.streamlit.app/)


