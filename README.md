## Project Overview

This project analyzes the relationship between Google search traffic for MercadoLibre and its stock price. The analysis includes identifying patterns in search traffic, relating them to stock price movements, and using the Prophet model to forecast future trends. The project is divided into the following key steps:

1. **Data Analysis**:
   - Analyzing unusual patterns in hourly Google search traffic for MercadoLibre.
   - Relating search traffic data to MercadoLibre's stock price.
   - Mining the search traffic data for seasonal patterns.

2. **Forecasting with Prophet**:
   - Preparing the search traffic data for forecasting using the Prophet model.
   - Fitting the Prophet model to the data.
   - Generating future forecasts and visualizing them.
   - Analyzing components of the forecast, including daily, weekly, and yearly trends.

## Files Included

- **`mercado_stock_price.csv`**: Historical stock price data for MercadoLibre.
- **`google_hourly_search_trends.csv`**: Hourly Google search trend data for MercadoLibre.
- **`forecast_mercado_trends.csv`**: Output file containing the forecasted search trends using the Prophet model.

## Key Insights

- **Search Traffic Patterns**:
  - The highest search traffic occurs at midnight, while Tuesday is the most active day of the week for searches.
  - The lowest point in search traffic occurs around late December.

- **Stock Price Correlation**:
  - The analysis showed a low correlation between lagged search traffic and stock price volatility or returns, suggesting that other factors play a more significant role in driving stock performance.

- **Forecasting**:
  - The Prophet model provided forecasts that indicated stable search trends in the near future.
  - The model also highlighted seasonal patterns, such as weekly peaks on Tuesdays and yearly dips around the holiday season.

