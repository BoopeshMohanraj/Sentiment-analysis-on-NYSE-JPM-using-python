# Sentimen-analysis-on-NYSE-JPM-using-python

# Goal :
The goal of this project is to analyze the relationship between public news sentiment and stock price movements. By leveraging VADER sentiment analysis, we extract insights from financial news headlines and correlate them with JP Morgan Chase’s (JPM) stock performance to determine if sentiment influences stock trends.

# Introduction : 
Stock markets are influenced by a variety of factors, including economic indicators, investor sentiment, and breaking news. Financial headlines shape market perception and can lead to price fluctuations.

# This project aims to:
1. Scrape financial news headlines from Finviz for JPMorgan Chase.
2. Perform sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner).
3. Obtain historical stock data from Yahoo Finance (yfinance).
4. Correlate stock price movements with aggregated sentiment scores.
5. Visualize findings using Matplotlib & Plotly, displaying sentiment vs. stock price trends.

Through this project, we explore whether news sentiment can serve as an indicator for stock price movement and help traders make informed decisions.

# Libraries & Packages Used
Python Libraries:

Data Processing: pandas, numpy

Web Scraping: requests, BeautifulSoup

Natural Language Processing (NLP): nltk

Sentiment Analysis: vaderSentiment

Visualization: matplotlib, matplotlib.dates

Financial Data Retrieval: yfinance

Datetime Handling: datetime

# Methodology
To conduct this analysis, we followed these key steps:

# 1️⃣ Data Collection
Stock Data: Extracted daily stock prices for JPMorgan Chase (JPM) using Yahoo Finance (yfinance).

News Data: Scraped financial news headlines from Finviz, a widely used market research tool.

# 2️⃣ Sentiment Analysis
Preprocessing: Cleaned and tokenized news headlines, removing stopwords and irrelevant characters.

Sentiment Scoring: Used VADER (Valence Aware Dictionary and sEntiment Reasoner) to assign each headline a sentiment score.

Positive sentiment → Score > 0
Negative sentiment → Score < 0
Neutral sentiment → Score ≈ 0

# 3️⃣ Data Integration & Analysis
Aggregated daily sentiment scores by averaging all headlines for each day.

Merged sentiment data with stock price data to ensure alignment.

Performed correlation analysis to understand the relationship between sentiment and stock trends.

# 4️⃣ Visualization
Stock Price Trends: Plotted daily closing prices of JPM stock.

Sentiment Trends: Overlaid aggregated sentiment scores using color-coded bars (green for positive, red for negative).

Comparison: Analyzed if stock price trends aligned with sentiment shifts.

#  Results & Key Insights

![image](https://github.com/user-attachments/assets/3bec1415-7841-4014-95e9-45b6f3b8d91d)

#  Observations
1. Positive sentiment days generally showed an upward movement in stock prices.
2. Negative sentiment days coincided with price dips, though not always immediately.
3. Neutral sentiment days did not significantly impact price movements.

#  Stock vs. Sentiment Visualization
The final output graph presents:
1. JP Morgan Chase’s stock price (blue line).
2. Aggregated sentiment scores (green for positive, red for negative).
3. A clear timeline showing price movements vs. sentiment changes.

# Socialization & Distribution
This project is relevant to financial analysts, traders, and fintech professionals.

# Value & Business Impact
This project demonstrates how news sentiment can be leveraged for financial decision-making:

1. Data-Driven Investment Strategies: Helps traders understand how public sentiment impacts stock trends.

2. Automated Sentiment Monitoring: Enables AI-driven market sentiment tracking for traders & analysts.

3. Cross-Asset Class Expansion: This method can be applied to crypto, commodities, and ETFs.

# Potential Use Cases:

1. Investment Firms: Enhancing stock research with sentiment tracking.
2. Retail Traders: Identifying news-driven trading signals.
3. Risk Management Teams: Measuring sentiment shifts that impact portfolio performance.

# Next Steps & Future Improvements
1. Expand Data Sources: Integrate alternative sources like Twitter, Bloomberg, and Reddit for broader market sentiment.
2. Include Economic Indicators: Combine sentiment with macroeconomic data (GDP, inflation, interest rates) to refine predictions.
3. Apply Machine Learning Models: Explore LSTM (Long Short-Term Memory) models to predict stock movements based on historical sentiment trends.
4. Multi-Stock Analysis: Extend this methodology to compare sentiment across multiple financial stocks.

















