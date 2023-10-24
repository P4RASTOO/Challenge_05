<img width="542" alt="Screenshot 2023-10-23 at 11 31 27 PM" src="https://github.com/P4RASTOO/Challenge_05/assets/132952512/9aeb26cd-a6ff-4f5b-a871-c84023124807">

# Challenge_05 Report
## Overview of the Analysis:
In this analysis we are creating a financial planning tool for a credit union, consisting of two parts. The first part helps credit union members assess their emergency fund needs by evaluating the value of their cryptocurrency wallet, stocks, and bonds. It calculates if they have enough savings for an ideal emergency fund (three times their monthly income). 
The second part focuses on a financial planner for retirement, using historical price data to run Monte Carlo simulations for a portfolio of stocks and bonds to forecast retirement performance. We analyze the retirement portfolio forecasts, calculate confidence intervals, and determine if members can retire after ten years by adjusting the portfolio weights.

## Methods Used:
1) Utilizing the Requests library to fetch cryptocurrency prices.
2) Making API calls to Alpaca using Alpaca SDK for retrieving stock and bond prices.
3) Creating DataFrames to hold financial data.
4) Visualizing savings with pie charts.
5) Conducting Monte Carlo simulations.
6) Plotting simulation results and histograms.
7) Analyzing summary statistics and confidence intervals.
8) Adjusting portfolio weights to simulate a shorter investment horizon.

This project aims to provide credit union members with a comprehensive set of financial tools for assessing their financial health, making informed decisions about their emergency funds, and planning for a secure retirement. By combining cryptocurrency evaluation, stock and bond analysis, and Monte Carlo simulations, this tool empowers users to take control of their financial futures with data-driven insights.
