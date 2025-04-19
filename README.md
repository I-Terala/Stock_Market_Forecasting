# Stock Market Forecasting (2015–2030)

This project analyzes stock market data from 2015 to 2025 and predicts how different industries might perform in the coming years, up to 2030. The goal is to help identify which sectors are likely to grow and which ones might face challenges, offering useful insights for investors and analysts.

## Overview

The analysis covers stock prices from 25 companies across 9 industries:

- Technology
- Finance
- Retail
- Healthcare
- Automotive
- Semiconductors
- E-commerce
- Entertainment
- Telecommunications

I used a time series forecasting model (ARIMA) to make predictions for each sector from 2025 to 2030.

## Tools Used

- Python
- Pandas, NumPy
- Statsmodels (ARIMA)
- Matplotlib, Seaborn

## Steps Followed

1. **Data Cleaning**  
   - Fixed missing values and removed outliers  
   - Converted dates and organized data by industry  

2. **Data Exploration**  
   - Created visualizations to understand trends  
   - Compared industries on performance and stability  
   - Identified the strongest and weakest sectors  

3. **Forecasting**  
   - Applied the ARIMA model to each industry  
   - Predicted stock performance for the next 6 years  
   - Measured accuracy using standard error metrics

## Key Findings

- **Technology** and **Semiconductors** are expected to grow the most.
- **Retail** had the most accurate and stable forecast.
- **E-commerce** and **Automotive** showed consistent, steady performance.
- **Healthcare** is projected to decline.
- **Finance** and **Entertainment** had more unpredictable results.

## Forecast Highlights

| Industry        | 2025  | 2030  |
|----------------|-------|-------|
| Technology      | 186.04 | 233.40 |
| Semiconductors  | 128.50 | 172.58 |
| Retail          | 77.10  | 77.23  |
| Healthcare      | 4.57   | -16.35 |
| Finance         | 65.43  | 63.56  |

## Takeaways

- Some industries show strong long-term potential, especially tech-related sectors.
- Retail and E-commerce appear to be low-risk, steady growth areas.
- Healthcare may need closer review due to its downward trend.
- Forecasting models work better on stable sectors than on highly volatile ones.

## Limitations

- Only past stock price data was used, without including external economic factors.
- ARIMA may not capture sudden shifts caused by news or global events.
- Accuracy of predictions decreases the further we look into the future.

## Future Improvements

- Add more data like economic indicators or news trends.
- Try advanced models (e.g., LSTM) for more complex forecasting.
- Build a simple tool to view real-time industry forecasts.
