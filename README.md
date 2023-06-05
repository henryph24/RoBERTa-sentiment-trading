# RoBERTa-sentiment-trading
The project implemented “cardiffnlp / twitter-roberta-base-sentiment” model for assigning
sentimental labels (0 -> Negative; 1 -> Neutral; 2 -> Positive) for each tweet regarding a ticker in
the dataset.
The CardiffNLP Twitter-roBERTa-base-sentiment model is a pre-trained natural language
processing model designed specifically for sentiment analysis of English tweets. It combines the
power of RoBERTa, a robustly optimized variant of BERT, with fine-tuning on the TweetEval
benchmark.
The approach chosen was relatively standard where sentiments are 
resampled on a daily basis using arithmetic mean. Additionally, we need to obtain close price data 
of the tickers of our interests to showcase how might sentimental analysis empower our predictive modelling 
of stock prices. This is achieved via yfinance library.
Additionally, we need to obtain close price data of the tickers of our interests to showcase how
might sentimental analysis empower our predictive modelling of stock prices. This is achieved
via yfinance library.
