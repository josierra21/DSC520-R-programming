# Stock Market Sector Analysis: Identifying the Best Investment Opportunity

## Overview

This project analyzes and compares three major sectors of the U.S. stock market to determine which sector has historically provided the strongest investment performance. The analysis focuses on three exchange-traded funds (ETFs):

- QQQ (Technology Sector)
- IYC (Consumer Discretionary Sector)
- XLE (Energy Sector)

The project examines historical returns, market trends, and the influence of macroeconomic indicators such as inflation and interest rates. Statistical analysis and regression modeling were used to evaluate the relationships between economic conditions and sector performance.

The goal was to identify which sector offered the strongest investment opportunity based on historical performance and economic factors.

---

## Research Questions

1. How do historical returns compare across the technology, consumer discretionary, and energy sectors?
2. How do these sectors compare to the overall stock market?
3. Are there statistically significant differences in performance between the sectors?
4. How do inflation and interest rates affect sector performance?
5. Can macroeconomic indicators be used to explain or predict stock market behavior?

---

## Dataset Sources

### ETF Data

Historical ETF data was obtained from Yahoo Finance.

- QQQ (Technology)
- IYC (Consumer Discretionary)
- XLE (Energy)

### Economic Data

- U.S. Inflation Data
- U.S. Treasury Interest Rate Data
- U.S. Gross Domestic Product (GDP) Data
- S&P 500 Historical Market Data

---

## Technologies Used

- R
- R Markdown
- dplyr
- ggplot2
- lubridate
- Linear Regression
- Statistical Analysis

---

## Methodology

### Data Preparation

- Imported ETF and economic datasets
- Removed unnecessary variables
- Standardized date formats
- Merged datasets for analysis
- Aggregated annual economic indicators

### Exploratory Data Analysis

- Historical price analysis
- Return calculations
- Trend visualization
- Sector comparison against the S&P 500

### Statistical Modeling

Linear regression models were used to evaluate:

- ETF performance versus inflation
- ETF performance versus interest rates
- ETF performance versus trading volume

Model evaluation included:

- R-squared values
- P-values
- Regression coefficients
- Visual trend analysis

---

## Key Findings

### Historical Returns (2010–2024)

| ETF | Sector | Total Return |
|------|---------|---------|
| QQQ | Technology | 832% |
| IYC | Consumer Discretionary | 468% |
| XLE | Energy | 64% |
| S&P 500 | Market Benchmark | 344% |

The technology sector significantly outperformed both the broader market and the other sectors analyzed.

### Interest Rates

Interest rates affected each sector differently:

- QQQ showed the weakest relationship.
- IYC showed a moderate relationship.
- XLE showed the strongest relationship.

The energy sector appeared to be most sensitive to changes in long-term interest rates.

### Inflation

Inflation demonstrated a stronger relationship with ETF performance than interest rates.

Results suggested inflation explained a meaningful portion of sector price variability, particularly within the technology sector.

### Trading Volume

Trading volume showed little predictive value for ETF price performance across the sectors analyzed.

---

## Visualizations

The project includes:

- ETF price trend analysis
- Inflation regression models
- Interest rate regression models
- Trading volume regression models
- Comparative sector performance charts

---

## Conclusion

Among the sectors analyzed, the Technology sector (QQQ) demonstrated the strongest long-term performance, substantially outperforming both the S&P 500 and the other sectors included in the study.

The findings suggest that macroeconomic indicators, particularly inflation, can help explain changes in sector performance. While no single variable perfectly predicts stock market behavior, combining economic indicators with financial data can provide valuable insight for investment decision-making.

Future work could incorporate machine learning techniques, sentiment analysis, and additional economic indicators to improve predictive performance and uncover more complex market relationships.

---
