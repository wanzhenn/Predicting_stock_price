# Predicting_stock_price
Predicting stock pricing using EMA crossover and machine learning models (Tree based) on Apple stock closing price

*   **Method:** Compare between 2 strategies 
     1. EMA crossover, 
     2. simple buy sell method to determine success of prediction.
   
*   **Approach:** Obtain approximately 10 years of data (Source: AlphaVantage)

   1. Download AAPL stock data from AlphaVantage by calling an API, 
   2. then extracting the "Time Series (Daily)" data and save it as a CSV file.
   
*   **Technical Analysis:** EMA 20 and 50 day cross over.
   
*   **Metric:** Measure return of investment (ROI) based on methods above for data in year 2019 (before COVID) and 2021-2022 (after COVID).

*   **Conclusion:** Random Forest Regressor model performed better in both 2019 (bull market) and 2021 (bear market) as compared to EMA crossover strategy.
