# Google Search Traffic Analysis and Forecasting

## Overview

This project focuses on analyzing hourly Google search traffic data for a company, MercadoLibre, and aims to uncover patterns, seasonality, and potential relationships with financial events and stock price movements. The analysis is conducted in four main steps:

1. **Finding Unusual Patterns in Hourly Google Search Traffic**: This step involves reading the search data into a DataFrame, slicing it to May 2020 (when financial results were released), visualizing the results, calculating total search traffic for the month, and comparing it to the monthly median across all months to determine if there's an increase during the financial event.

2. **Mining the Search Traffic Data for Seasonality**: Here, we group the hourly search data to analyze average traffic by the hour of the day, day of the week, and week of the year. The goal is to identify any predictable seasonal patterns of interest in the company.

3. **Relating the Search Traffic to Stock Price Patterns**: This step involves reading and plotting stock price data, concatenating it with search data, slicing it to the first half of 2020, creating lagged search trends, stock volatility, and hourly stock return columns, and examining relationships between these variables.

4. **Creating a Time Series Model with Prophet**: Finally, we set up the Google search data for a Prophet forecasting model, estimate the model, plot the forecast, and analyze individual time series components to identify peak popularity times, busiest days, and lowest points for search traffic in the calendar year.

## Instructions

### Step 1: Find Unusual Patterns in Hourly Google Search Traffic

- Read the search data into a DataFrame.
- Slice the data to May 2020.
- Calculate total search traffic for the month and compare it to the monthly median.
- Determine if the Google search traffic increased during the month of financial results release.

### Step 2: Mine the Search Traffic Data for Seasonality

- Analyze average traffic by hour of the day.
- Analyze average traffic by day of the week.
- Analyze average traffic by week of the year.
- Identify time-based trends in the data.

### Step 3: Relate the Search Traffic to Stock Price Patterns

- Read and plot stock price data.
- Concatenate stock price data with search data.
- Slice data to the first half of 2020.
- Create lagged search trends, stock volatility, and hourly stock return columns.
- Examine relationships between lagged search traffic and stock volatility/returns.

### Step 4: Create a Time Series Model with Prophet

- Set up the Google search data for a Prophet forecasting model.
- Estimate the model and plot the forecast.
- Analyze individual time series components to identify peak popularity times, busiest days, and lowest points for search traffic.

## Conclusion

This project provides a comprehensive analysis of Google search traffic data for MercadoLibre, uncovering patterns, seasonality, and potential relationships with financial events and stock price movements. By utilizing various analytical techniques and tools like visualization, statistical analysis, and time series modeling, valuable insights can be gained to inform marketing strategies, financial decisions, and forecasting efforts.
