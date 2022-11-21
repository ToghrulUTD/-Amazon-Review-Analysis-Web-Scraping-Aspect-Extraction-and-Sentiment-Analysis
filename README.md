# Sentiment-analysis-of-Amazon-product-reviews
This repository contains two projects: 1) Sentiment analysis of Amazon customer reviews, 2) Tweets. I have implemented textual feature extraction and traditional NLP methods and applied Deep Learning models for sentiment classification in these projects.


# Amazon Reviews Sentiment analysis & Scraping reviews and Sentiment analysis with BERT.

## Datasets
1 - The first dataset used for model training consists of a few million Amazon customer reviews (input text) and star ratings (output labels) for training neural network models for sentiment analysis.
https://www.kaggle.com/datasets/bittlingmayer/amazonreviews

2 - I also web-scraped reviews from amazon website directly to asses and compare the model performances both with the custom LSTM sentiment classifier and pre-Trained Huggingface BERT sentiment classifer.

## Contents
These two notebooks includes the following tasks:

1. Scrape reviews
2. Exploratory data analysis
3. Hyphothesis testing with permutation analysis
4. Text Preprocessing (cleaning, tokenizing, padding)
5. Sentiment classification with Convolutional, LSTM neural network and pre-trained BERT model
 
 


# Tweets Sentiment

This project performs the following tasks on the tweets dataset

* Extract features from a text using tokenization, stemming + remove useless words and characters
* Implement logistic regression from scratch
  * Apply logistic regression on a natural language processing task
  * Test using your logistic regression
* Implement Naive Bayes from scratch
  * Apply Naive Bayes on a natural language processing task
  * Test using your Naive Bayes model
* Perform error analysis
