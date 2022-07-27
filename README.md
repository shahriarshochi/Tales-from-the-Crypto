# Tales-from-the-Crypto

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.
In this assignment, I will be applying natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. I will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

## Methods and Techniques Used:

1. Sentiment Analysis: Use the newsapi to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin. Descriptive statistics was used to find out the highest mean positive score, highest negative score and highest mean positive score.

2. Natural Language Processing: In this section I have used NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. I have used NLTK to look at the ngrams and word frequency for each coin. Lastly for this section I have generated a word cloud for each coin to summarize the news for each coin.

3. Named Entity Regcognition: In this section, I have built a named entity recognition model for both coins and visualized the tags using SpaCy.

## Goal Of This Project: 

The main purpose of this project is to understand the sentiment in the latest news articles and relate how different factors involved in these news articles could effect the market price of a certain commodity/goods/currency, in our case, cryptocurrencies.
