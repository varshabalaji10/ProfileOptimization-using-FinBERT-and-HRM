# Sentiment Analysis, Portfolio Optimization, and Web Scraping

This project combines three major components: Sentiment Analysis of news articles, Portfolio Optimization using financial data, and Web Scraping for news articles. It includes Python code that uses pre-trained models for sentiment analysis, leverages the PyPortfolioOpt library for portfolio optimization, and scrapes news articles from a website. The project aims to help users analyze sentiment in news articles, optimize their investment portfolio, and fetch the latest news articles for analysis.

## Sentiment Analysis

Sentiment analysis is a natural language processing technique used to determine the sentiment or emotional tone of a piece of text. In this project, we use a pre-trained model for sentiment analysis to analyze news articles. We extract and filter articles with a specific sentiment score, helping users identify articles with a significant impact on financial markets.

### Prerequisites

To run the sentiment analysis code, make sure you have the following libraries installed:

- Transformers
- pandas
- numpy
- torch
- yfinance
- matplotlib
- seaborn

You can install the required libraries using pip, as shown in the code.

### Usage

Install the required libraries if you haven't already:

```bash
pip install transformers pandas numpy torch yfinance matplotlib seaborn
```
1.Run the web scrapping code first ti scrape the news from yfinance 
2.Run the provided Python code for sentiment analysis. Make sure to adjust the data file paths, the threshold, and other parameters as needed for your specific dataset and requirements.
3.The code will analyze the sentiment of news articles and generate output, including positive, neutral, and negative sentiment scores.

#Portfolio Optimization
Portfolio optimization is a critical aspect of managing investments. In this project, we use the Hierarchical Risk Parity (HRP) method to optimize a portfolio based on historical financial data.

###Prerequisites
To run the portfolio optimization code, you need to install the PyPortfolioOpt library:
```bash
pip install PyPortfolioOpt
```
##Usage
Install the PyPortfolioOpt library if you haven't already.

Run the provided Python code for portfolio optimization. This code will use historical stock price data to optimize a portfolio based on the HRP method.

The code will generate an optimized portfolio with asset allocations and display performance metrics, such as expected annual return, annual volatility, and the Sharpe ratio.

It will also provide a discrete allocation of funds for each asset, helping you manage your portfolio effectively.

Web Scraping for News Articles
Web scraping is a technique used to extract data from websites. In this project, we fetch the latest news articles from a website to provide up-to-date data for sentiment analysis.

Prerequisites
To run the web scraping code, you need to install the following library:

BeautifulSoup (bs4)
You can install the required library using pip, as shown in the code.

# Usage
Install the BeautifulSoup library if you haven't already:
```bash
pip install beautifulsoup4
```
Run the provided Python code for web scraping. This code will fetch the latest news articles from a specified website.

Make sure to customize the code for the specific website and data you want to scrape.

### Customization
Make sure to customize the code and parameters based on your specific use case, such as the choice of assets, dataset paths, and portfolio optimization constraints.

Please refer to the respective code sections and libraries for detailed documentation and customization options.

##Author

Varsha Balaji

Feel free to reach out for any questions or further assistance.
