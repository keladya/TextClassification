# Disaster Tweet Classification

This repository contains a Python script for classifying tweets into disaster-related and non-disaster-related categories. The project utilizes a dataset from a Kaggle competition and implements various machine learning models to perform the classification.

## Dataset
The dataset used in this project is sourced from the [Kaggle Competition: Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started). It includes a training set and a test set containing tweets that are labeled as either linked to real disaster events (1) or not (0). The dataset consists of several features:
- **id:** The id of the tweet.
- **keyword:** A keyword from the tweet (may be blank).
- **location:** The location the tweet was sent from (may be blank).
- **text:** The text of the tweet.
- **target:** This denotes whether a tweet is about a real disaster (1) or not (0).

## Objectives
The primary objectives of this repository are to:
- Develop a model that can accurately classify tweets as disaster-related or not.
- Explore different feature engineering techniques and model architectures.
- Evaluate and compare the performance of various machine learning models like Naive Bayes, SVM, Logistic Regression, and Decision Trees.

