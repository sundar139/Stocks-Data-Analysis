# 📈 Stock Market Analysis of Big Tech Companies (2010–2025)

Figures: https://sundar139.github.io/Stocks-Data-Analysis/

## Introduction

This project focuses on the analysis of historical stock market data for five of the largest technology companies in the world: **Apple (AAPL), Amazon (AMZN), Google (GOOGL), Microsoft (MSFT), and NVIDIA (NVDA)**. The dataset spans from **January 1, 2010, to January 1, 2025**, covering **15 years** of daily stock activity. It includes opening and closing prices, daily highs and lows, and trading volumes for each company.

The primary goal of this analysis is to understand **long-term trends**, **volatility**, and **market behavior** among these influential companies, and to derive insights that could inform **investment strategies**, **risk assessments**, or **future performance predictions**.

## Objectives

- **Trend Analysis:** Identify how each company’s stock has evolved over time.
- **Volatility Assessment:** Measure and compare stock price volatility.
- **Volume Dynamics:** Explore how trading volume has changed across the years and among companies.
- **Comparative Growth:** Determine which company exhibited the most growth or decline over 15 years.
- **Correlation Study:** Understand how closely the stock prices of these companies move in relation to each other.
- **Visual Insights:** Use plots and graphs to bring clarity to historical movements, trends, and relationships.

## Key Insights & Exploratory Steps

1. **Initial Data Inspection**

   - Checked for null values, missing dates, or anomalies.
   - Confirmed data frequency (daily) and cleaned where necessary.

2. **Stock Price Trends (Line Charts)**

   - Visualized closing price trends for all five companies to compare long-term performance.
   - Observed major inflection points, such as COVID-19 and market booms in 2020–2023.

3. **Volatility & Moving Averages**

   - Used rolling window statistics to evaluate volatility.
   - Compared 30-day and 180-day moving averages to identify consistent trends.

4. **Correlation Heatmap**

   - Found strong correlations between major tech stocks, indicating possible market-wide influences.

5. **Volume Analysis**

   - Examined spikes in trading volumes during earnings, splits, or major news.
   - NVDA and AAPL showed the most volume sensitivity to events.

6. **Growth Comparison**

   - Calculated percentage returns from 2010 to 2025.
   - NVIDIA led the pack with the highest percentage growth, largely due to the rise in AI and GPU demands.

## Findings

- **NVIDIA (NVDA)** experienced the most exponential growth, especially after 2020, due to the AI and data center boom.
- **Apple (AAPL)** and **Microsoft (MSFT)** maintained steady, strong upward trends, showcasing market stability.
- **Amazon (AMZN)** had volatile swings, especially impacted by e-commerce dynamics and macroeconomic shifts.
- **Google (GOOGL)** displayed moderate growth with relatively stable fluctuations.
- **Stock correlations** suggest that these companies are affected by similar macroeconomic and industry-specific events.
- **Volume spikes** aligned with significant announcements, earnings reports, or geopolitical events.

## Conclusion

This analysis provides a comprehensive look at the **historical performance, volatility, and interrelationships** of the five largest tech companies over the past 15 years. By visualizing trends and quantifying growth, this study can assist in understanding how these industry giants have shaped — and been shaped by — the broader market.

While historical data alone can't predict the future, it does offer valuable **context for forecasting**, **investment decision-making**, and **market behavior analysis**. The insights gleaned here are particularly useful for anyone interested in long-term investing or understanding the technology sector's evolution.

## Dataset Description

- Date: The trading date of the stock data entry.
- Close_AAPL: Apple’s stock price at market close at the end of the trading days.
- Close_AMZN: Amazon’s stock price at market close at the end of the trading days.
- Close_GOOGL: Google’s stock price at market close at the end of the trading days.
- Close_MSFT: Microsoft’s stock price at the end of the trading days.
- Close_NVDA: NVIDIA’s stock price at the end of the trading days.
- High_AAPL: The highest price of Apple’s stock reached during the trading days.
- High_AMZN: The highest price of Amazon’s stock reached during the trading days.
- High_GOOGL: The highest price of Google’s stock reached during the trading days.
- High_MSFT: The highest price of Microsoft’s stock reached during the trading days.
- High_NVDA: The highest price of NVIDIA’s stock reached during the trading days.
- Low_AAPL: The lowest price of Apple’s stock reached during the trading days.
- Low_AMZN: The lowest price of Amazon’s stock reached during the trading days.
- Low_GOOGL: The lowest price of Google’s stock reached during the trading days.
- Low_MSFT: The lowest price of Microsoft’s stock reached during the trading days.
- Low_NVDA: The lowest price NVIDIA’s stock reached during the trading days.
- Open_AAPL: Apple’s opening stock price at the beginning of the trading days.
- Open_AMZN: Amazon’s opening stock price at the beginning of the trading days.
- Open_GOOGL: Google’s opening stock price at the beginning of the trading days.
- Open_MSFT: Microsoft’s opening stock price at the beginning of the trading days.
- Open_NVDA: NVIDIA’s opening stock price at the beginning of the trading days.
- Volume_AAPL: The number of shares traded of Apple’s stock during the trading days.
- Volume_AMZN: The number of shares traded of Amazon’s stock during the trading days.
- Volume_GOOGL: The number of shares traded of Google’s stock during the trading days.
- Volume_MSFT: The number of shares traded of Microsoft’s stock during the trading days.
- Volume_NVDA: The number of shares traded of NVIDIA’s stock during the trading days.
