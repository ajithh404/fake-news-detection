# Fake News Detection

This project focuses on detecting fake news using machine learning algorithms. It works with two datasets: `true.csv` and `fake.csv`. The project preprocesses news articles, extracts features using **TF-IDF**, and applies various classifiers to determine whether a news article is **real** or **fake**. It also evaluates model performance using metrics such as accuracy, precision, recall, F1 score, and support.

## Overview

Fake news detection is a crucial step in combating misinformation in today's digital world. This project leverages multiple machine learning algorithms to classify news articles effectively. The models used are:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

The data is cleaned, transformed using **TF-IDF Vectorizer**, and passed into these models for classification.

## Features

- Preprocessing of text (removal of stopwords, punctuation, and irrelevant content)
- Feature extraction using **TF-IDF**
- Implementation of multiple classifiers for comparison
- Model evaluation using standard classification metrics
- Simple and modular structure for easy experimentation

## Tools & Libraries

- Python (3.x)
- Pandas
- Scikit-learn
- NumPy
- Optional: NLTK (for advanced text cleaning)

