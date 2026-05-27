# Bitcoin Market Sentiment vs Trader performance Analysis

## Project Overview
This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

The goal of this analysis is to understand how market emotions such as Fear, Greed, Extreme Fear, and Extreme Greed influence:

-Trader profitability
-Trading activity
-Risk-taking behavior
-Buy/Sell decisions
-Position directions
-Market volatility


This project combines behavioral financa concepts with data analysis to uncover hidden patterns in cryptocurrency marksets.


# Objectives
The main objectives of this project are:
 -Analyze how market sentiment affects trader behavior.
 -Study profitability under different emotional market conditions
 -Identify trading patterns during fear and Greed periods
 -explore risk taking behavior using trade size analysis 
 -discover the most profitable and volatile coins
 -analyze top performing traders 

 # Datasets Used 
 ## 1 Bitcoin fear and Greed index dataset
 Contains daily market sentiment classification:
 -Fear
 -Extreme Fear
 -Neutral
 -Greed 
 -Extreme Greed 

Columns Used:
-date
-classification
-value


## 2 Historical Trader Dataset 
contains detailed trading activities:
-Account
-Coin
-Execution Price
-Side
-Direction
-CLosed PnL
-Timestamp 


## Technologes Used
-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Jupyter Notebook /VS code


# Project Workflow
# 1. Data Cleaning and Preprocessing 
-checked missing values 
-checked and removed duplicates
-converted timestamps into datetime format 
-extracted date columns for merging

# 2.Data Merging 
Merged trader data with sentiment data using date column.This allowed each trade to be associated with the corresponding market sentiment.

# 3.EDA(Exploratory Data Analysis)
Performed multiple analysis :
a. Sentiment distribution analysis
b. Profit/loss analysis
c. Risk taking analysis 
d. Buy vs sell  behavior analysis
e. Position direction analysis 
f. Coin level analysis
g. Trader level analysis

# Key Analysis Performed

## Sentiment Distribution Analsyis
Analyzed trading activity across:
-Fear 
-Greed
-Extreme Fear
-Extreme Greed
-Neutral 

## Profit/Loss Analysis
studied:
-Mean CLosed PnL
-Median CLosed PnL
-Profit/loss distribution 
-volatility using standard deviation 

## Risk-Taking Analysis
Analyzed average trade sizes across sentiment categories to understand trader aggression and emotional trading behavior.

## Buy vs Sell Analysis
Compared BUY and SELL activity under different market emotions.

## Direction Analysis
studied:
- Open Long
- Open Short
- Close Long
- Close Short

(to understand trader positioning behavior)


## Coin Analysis
Identified:
- Most traded coins
- Most profitable coins
- Most volatile coins


## Trader Analysis
Analyzed:
- Top profitable traders
- Most active traders
- Average profit per trade

# Insights

## 1. Fear Led to Bigger Trades

Traders used larger trade sizes during Fear market conditions, showing that many traders took aggressive positions or tried to buy assets at lower prices.

## 2. Fear and Greed Increased Market Volatility

Both Fear and Greed periods showed larger profits and losses, meaning trading outcomes became more unpredictable during emotional market conditions.

## 3. Extreme Greed Increased Selling Activity

During Extreme Greed conditions, traders showed higher selling and short-position activity, suggesting profit booking and expectations of market correction.

## 4. Trading Activity Focused on a Few Coins

A small number of coins, especially HYPE, dominated most of the trading activity in the dataset.

## 5. Some Coins Had Higher Risk and Reward

Coins such as EIGEN, ENA, DOGE, and ETH showed high profits along with high volatility, indicating high-risk and high-reward trading opportunities.

## 6. Only a Few Traders Made Most of the Profits

A small group of traders earned significantly higher profits compared to others, showing uneven trader performance across the market.

# Sample Visualizations

The project includes multiple visualizations such as:

- Countplots
- Boxplots
- Barplots
- Profit/Loss distributions
- Coin volatility charts
- Trader performance charts

Example analyses:
- Trading Activity by Market Sentiment
- Profit/Loss Distribution by Sentiment
- Average Trade Size by Sentiment
- Buy vs Sell Activity by Sentiment
- Top Coins by Profitability
- Top Traders by Profit

# Conclusion

This project demonstrates that cryptocurrency market sentiment significantly influences trader behavior, trading aggression, profitability, and market volatility.

The analysis reveals that emotional conditions such as Fear and Greed create distinct behavioral patterns that impact both trading decisions and financial outcomes.

These findings highlight the importance of behavioral finance in understanding cryptocurrency markets.


# Future Improvements

Possible future enhancements include:

- Time-series forecasting
- Machine learning-based sentiment prediction
- Trader clustering analysis
- Portfolio risk modeling
- Real-time dashboard development

# Author

Kripa Khadka

Data Science & Behavioral Market Analysis Project