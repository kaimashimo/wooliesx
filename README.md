# WooliesX - Million Advisory

## NOTE!
Commit history was removed after API keys were accidentally pushed to remote. Sorry about that!

## Welcome

This repo is a collection of Jupyter Notebooks that were used to retrieve, analyse and derive insights from Twitter data.

The Twitter API (via Tweepy) and `snscrape.modules.twitter` were the main tools used for retrieval.

`nltk`, `pandas`, `numpy`, `re` were the primary analytical modules used.

## Our Pipeline

Please refer to `Sample workflow.ipynb` to see how the pipeline works, broken down step by step.

* Acquire data (from API for 7 days or from SNS for historical)
* Preprocessing (stopwords, special chars etc)
* EDA and NLP analysis
* Displaying results

