# Portfolio-Analysis-Pandas

## Background

We have been presented with the task of identifying which portfolio is performing the best across multiple areas: volatility, returns, risk, and Sharpe ratios. This file will outline the creation of a python notebook that analyzes which portfolio outperformed the others. We are given the historical daily returns of several portfolios: some from the firm's algorithmic portfolios, some that represent the portfolios of famous "whale" investors like Warren Buffett, and some from the big hedge and mutual funds. Use this analysis to create a custom portfolio of stocks and compare its performance to that of the other portfolios, as well as the larger market (S&P 500 Index).

## Data Processing

Read the CSV files into DataFrames and clean the data. Ensure that all null values are detected and removed. Remove nonnumric symbols and convert datatypes to appropriate types. After cleaning, combine all DataFrames into a single DataFrame. 


## Quaitative Analysis

Analyze the data to see if any of the portfolios outperform the the S&P 500. Conduct performance analysis, risk analysis, and evaluate the rolling statistics for all portfolios. Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot and determine if the algorithmic strategies outperform both the S&P 500 and the whales portfolios.

The code and results can be found here: [whale_analysis.ipynb](https://github.com/sujitsubhash7/Portfolio-Analysis-Pandas/blob/main/Starter_Code/whale_analysis.ipynb)