
# Quantitative Analysis of Stocks 


## Project Overview

The goal of this data project is to perform a quantitative stock analysis that leverages historical market data to make data-driven, actionable financial investment decisions. The process will use statistical,mathematical techniques, and financial theories to evaluate stock performance and uncover critical insights that will guide investors, providing insights that optimize portfolio management, mitigate risk, and enhance investment returns. For the purpose of this project we will be analyzing four stock symbols AAPL (Apple), GOOG (Alphabet/Google), MSFT (Microsoft), and NFLX (Netflix).

Insights and recommendations are provided on the following key areas:

- **Descriptive Statistics:** Summarize and describe the main features of a dataset for each stock.
- **Time Series Analysis:** An analysis of closing price to identify trends and patterns for understanding stock price dynamics over time.
- **Volatility Analysis:** An analysis of price fluctuation over time. 
- **Correlation Analysis:** An assessment to look at the historical price data of these stocks and calculate their correlation coefficients over a specified time period.
- **Comparative Analysis:** Evaluating the stocks by comparing the performance based on their returns over the period.
- **Risk-Return Trade-off Analysis:** Analyzing stocks based on your risk tolerance and return expectations, aiding in portfolio management.

# Data Structure 

The dataset structure as seen below consists of eight colums: 

- Ticker: The stock symbol.
- Date: The trading date.
- Open: The opening price of the stock for the day.
- High: The highest price of the stock during the day.
- Low: The lowest price of the stock during the day.
- Close: The closing price of the stock for the day.
- Adj Close: The adjusted closing price, which accounts for all corporate actions such as stock splits, dividends or new stock offerings.
- Volume: The number of shares traded during the day.

| Ticker   | Date   | Open  | High  | Low   | Close   | Adj Close|    Volume  |
| -------- | ------ | ------| ------|-------|---------|----------| ---------- |

Prior to beginning the analysis, a variety of checks were conducted in excel for quality control and familiarization with the dataset. 

# Executive Summary

## **Overview of findings**

**Descriptive Statistics:**
Descriptive Statistics for AAPL, GOOG, MSFT, and NFLX stocks based on their closing prices. This analysis provides insights into how each stock behaves in terms of its closing price movement.

 - NFLX shows the highest mean closing price at 327.61, followed by MSFT at 275.0
 - AAPL has an average closing price of 158.2, followed by GOOG with the lowest average of 100.6
 - NFLX has the highest standard deviation(18.55), followed by MSFT with a standard deviation of (17.6),reflecting 
   the larger fluctuations in its price.
 - GOOG has the lowest standard deviation of (6.2), followed by AAPL (7.3) indicating less variability in closing 
    prices.
  
**Key Insights**:
  - NFLX is the most expensive and volatile stock, with a high standard deviation(18.55).
  - MSFT is highly volatile and higher standard deviation(17.6).
  - GOOG is the most stable in terms of closing price, with the lowest standard deviation(6.2).
  - AAPL has consistent, moderate volatility with a low standard deviation(7.3).
  
![Descriptive_Analysis](https://github.com/user-attachments/assets/4db617f2-cca0-4b6f-bdd3-3219ca36b3e2)

**Time Series Analysis:**
The primary goal of the Time series analysis is to evaluate how the closing prices of the stocks have behaved over time and to understand their potential future movements. For the time series analysis for AAPL, MSFT, GOOG, and NFLX, we'll focus on the following key components: Trend, Volatility and Comparative Performance.

**Key Insights**:
  - All four stocks are exibiting an upward trend with varying degrees of growth.
  - AAPL and MSFT show upward trend. 
  - NFLX shows a higher volatility and increased risk therefore it is a high-risk, high-reward opportunity stock.
  - MSFT and NFLX trading at higher price levels than AAPL and GOOG in this dataset.It could be due to outliers 
    indicating important events or market inefficiencies.

![Time_Series_Analysis](https://github.com/user-attachments/assets/4b6593c9-1a29-427d-aa2e-79fbe2218985)

**Volatility Analysis:**
   The bar chart and the accompanying data show the volatility (measured as standard deviation) of the closing 
   prices for each stock. It indicated that NFLX and MSFT stocks were more prone to price fluctuations that compared 
   to AAPL and GOOG. Here’s how they rank in terms of volatility to assess risk into the financial markets.

   **Key Insights**:
    - NFLX: Highest volatility with a standard deviation of approximately 18.55.
    - MSFT: Next highest volatility stock, with a standard deviation of 17.68.
    - AAPL: Lower volatility compared to NFLX and MSFT, with a standard deviation of 7.36.
    - GOOG: The least volatile in this set, with a standard deviation of approximately 6.28.

![Volatility_Analysis](https://github.com/user-attachments/assets/18355e0c-34c8-4f4a-9149-3676333e664d)

**Correlation Analysis:**
    Here we are using the correlation analysis to measure the relationship between the price movements of different 
    assets. To determine whether the price movements of one stock are related to the price movements of another. 
    The heat map displays the correlation matrix of the closing prices of the four stocks (AAPL, GOOG, MSFT, 
    NFLX) with correlation values ranging from -1 to +1.

   **Key Insights**:
     - AAPL and MSFT have a very strong positive correlation (0.95). This indicates that Apple and Microsoft tend to 
       move in similar directions, due to their similar market dynamics in the tech sector.
     - AAPL and GOOG show a strong correlation (0.90). Both stocks belong to the tech sector, but Google (Alphabet) 
       is more focused on advertising, which might introduce some divergence at times.
     - GOOG and MSFT also have a strong positive correlation (0.88). This is expected since both companies are large 
       players in technology, particularly in cloud computing and digital services.
     - NFLX shows a lower correlation(0.1 - 0.2) with all three tech stocks compared to AAPL, GOOG, and 
       MSFT. This suggests that Netflix's stock movements might be more influenced by factors specific to the 
       entertainment and streaming industry, rather than broader tech trends.

![Correlation_Matrix_Analysis](https://github.com/user-attachments/assets/dad873b7-60b0-4acd-b32a-8832cd301f55)      
  
**Comparative Analysis:**
  In this step, we’ll compare the performance of different stocks based on their returns over the period. We’ll 
  calculate the percentage change in closing prices from the start to the end of the period for each stock:

 **Key Insights**:     
   - MSFT: +16.10% the highest positive change with strongest overall performance in terms of returns, growth, and 
     profitability.
   - AAPL: +12.23% indicates a solid performance, though slightly lower than MSFT. 
   - GOOG: -1.69%. indicates a minor decline in its stock price over the observed time period.
   - NFLX: -11.07% indicates most significant negative change.

![Comparative_Analysis](https://github.com/user-attachments/assets/6528526e-ce24-4219-8f5a-3d00525442cf)
  
**Risk-Return Trade-off Analysis**:
  The risk-return trade-off, we calculated the average daily return and the standard deviation of daily returns for 
  each stock. The standard deviation will serve as a proxy for risk, while the average daily return represents the 
  expected return.
  
**Key Insights**: 
  key metrics for the given time period suggest: 
  - AAPL shows the lowest risk combined with a positive average daily return. Suggests more stable investment with 
    consistent returns
  - MSFT shows moderate risk with the highest average daily return. Potentially more rewarding investment, although 
    with higher volatility
  - GOOG has higher volatility than AAPL and, on average, a slightly negative daily return.
  - NFLX exhibits the highest risk and a negative average daily return.

![Risk_vs_Return_Analysis](https://github.com/user-attachments/assets/57f4938d-7197-4fc7-b27f-78f1c0bb41b9)

# **Recommendations:**

Based on the uncovered insights, the following recommendations have been provided for the Investment Implications.

  - AAPL offers a balanced risk-return trade-off. It provides good returns with moderate risk, makes a solid 
    choice for investors looking for growth with a manageable risk level.

  - MSFT offers a moderate risk the highest average daily return, potentially strong expected return with higher 
    risk (volatility).  

  - GOOG has slight negative average daily returns, has higher risk (volatility) than AAPL making it a less 
    rewarding riskier investment for the given time period. However, it could still appeal to investors willing to 
    take on moderate risk for growth potential in the digital advertising space.

  - NFLX exhibits the highest volatility and a negative average daily return, indicating it is the most volatile and
    least rewarding investment among these stocks over the analyzed period. Its high volatility suggest it may not 
    provide a sufficient return for the level of risk involved, making it a less attractive option unless you're 
    particularly bullish on its future prospects or looking for speculative opportunities.

 







