# Market News Sentiment Analysis using API and transformers pipeline
## Stock Market News Sentiment Analysis
This project utilizes the Financial Modelling Prep API to collect market-related news articles corresponding to specific stock tickers. The collected news articles are then subjected to sentiment analysis using three different Transformer models to determine the prevailing sentiment. The final sentiment assigned to each article is based on the majority sentiment from the three models.

### Requirements
Ensure you have the following Python packages installed:

- transformers
- newsapi-python
- pandas
  
### Usage
The code snippet demonstrates how to collect market news using the NewsAPI and apply sentiment analysis using various transformer-based models. The process involves the following steps:

### Data Collection
Retrieves news articles for specific stock tickers within a defined date range using the NewsAPI.

### Sentiment Analysis
Utilizes three different transformer-based models (distilbert-base-uncased-finetuned-sst-2-english, finbert, and distilroberta-finetuned-financial-news-sentiment-analysis) to perform sentiment analysis on the article titles.

### Majority Sentiment Determination
Derives the majority sentiment among the three models for each news article by counting the occurrences of positive and negative sentiments.

### Potential Analyses
#### The collected dataset provides opportunities for diverse analyses, including:
- Stock Price x Sentiment Analysis: Analyzing the relationship between stock price fluctuations and the sentiment of the corresponding news articles.
- RAG (Retrieval Augmented Generation) System: Use LLM techniques to retrieve information using conversational agents
- Comprehensive Data analysis The dataset generated from this project can serve as a foundation for comprehensive data analysis, aiding in understanding market sentiments and potential correlations between news sentiment and stock performance.

### Note: Replace 'api_key' with your actual NewsAPI key for successful news retrieval. Additionally, adjust the tickers, date ranges, or models used for sentiment analysis according to your requirements.

### Disclaimer: This code is intended for educational purposes and serves as a starting point for sentiment analysis on financial news articles. It's crucial to exercise caution when drawing conclusions from sentiment analysis and market-related data. Always perform additional research and consult financial experts before making investment decisions based on sentiment analysis.

Acknowledgment
This code utilizes Hugging Face's Transformers library for sentiment analysis.
The Financial Modelling Prep API is used for fetching market-related news articles.
Special thanks to the developers and contributors of the used libraries and APIs.
