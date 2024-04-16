# Toxic-Tweets-Classification-Sentiment-Analysis
# Overview
This project focuses on sentiment analysis of Twitter data using machine learning techniques. It involves training models(here used SVM) to classify tweets into positive and negative sentiment categories based on their content.
# Dataset
The dataset used in this project consists of labeled tweets categorized as positive or negative sentiment. It contains two columns: 'Toxicity' (0 or 1) indicating the label and 'tweet' containing the text content of the tweet.
source:https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset/data
# Data Preprocessing Steps
* Tokenization: Tokenize the tweets using the TweetTokenizer from NLTK.
* Special Character Removal: Remove special characters from the tokenized tweets using regular expression.
* Lemmatization: Perform lemmatization on the tokens to reduce them to their base form.
* Lowercasing: Convert the tokens to lowercase for uniformity.
* Stopword Removal: Remove stopwords from the tokenized tweets.
* Vectorization: Vectorize the preprocessed text using TF-IDF (Term Frequency-Inverse Document Frequency).
# Model
Support Vector Machine (SVM): Train a SVM model on the vectorized text data to perform sentiment analysis.
