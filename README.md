# Stock Pair Trading Strategy Analysis

## Project Overview
The goal of this project was to develop a profitable trading strategy based on the concept of pairs trading. Pairs trading is a market-neutral trading strategy that matches a long position with a short position in a pair of highly correlated stocks.

### Objectives
- Identify stocks that are cointegrated and exhibit similar movements.
- Capitalize on instances where the prices of these stocks diverge significantly from their historical average spread.

## Methodology
The project was executed in two main steps:
1. **Cointegration Identification:** First, we identify pairs of stocks whose price movements are historically correlated. This involves statistical tests to find pairs that are cointegrated.
2. **Spread Analysis:** We then monitor the spread between these pairs. Specifically, we look for moments where the spread exceeds one standard deviation from its mean. This indicates a potential trading opportunity.


## Tools and Technologies
- **SQL:** Used for querying stock price data from the CRSP database.
- **Pandas:** Employed for data cleaning, transformation, and analysis.
- **Matplotlib:** Used for visualizing data and results through graphs.

## Installation and Setup
To run this project, ensure you have Python installed along with the following packages:
- Pandas
- NumPy
- Matplotlib
- statsmodels (for statistical tests)

You can install the necessary libraries using the following command:
```bash
pip install pandas numpy matplotlib statsmodels
