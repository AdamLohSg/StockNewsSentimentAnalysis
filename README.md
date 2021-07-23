# Stock News Sentiment Analysis using Naïve Bayes Classifier

Naïve Bayes classifier trained using datasets retrieved from Kaggle. The classifier is then tested using stock related news from an API provided by CityFalcon.

Two notebooks in this project:

1. SentimentalAnalysisClassifierTrainer.ipynb: Trains the classifier to perform sentiment analysis on stock-related news/tweets/texts.
2. PortfolioAnalysis.ipynb: Retrieves ETFs (etf_sectors.csv) related to sector(s) indicated in the sector_list variable. News on the ETFs are then queried using the CityFalcon API afterwhich sentiment analysis is performed.

References:

1. Tweet Dataset: https://www.kaggle.com/yash612/stockmarket-sentiment-dataset
2. News Dataset: https://www.kaggle.com/ankurzing/sentiment-analysis-for-financial-news
3. CityFalcon API: https://www.cityfalcon.com/products/api/financial-news

