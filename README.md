# Customer Review Intelligence System using NLP

## Overview
This project applies Natural Language Processing (NLP) techniques to analyze large-scale
Amazon customer reviews. The goal is to classify customer sentiment and identify key
complaint themes using machine learning and topic modeling.

## Dataset
Amazon Reviews dataset in fastText format containing millions of customer reviews
with binary sentiment labels (positive and negative).

## Approach
- Text preprocessing (cleaning, tokenization, lemmatization)
- TF-IDF feature extraction
- Sentiment classification using Logistic Regression and Naive Bayes
- Topic modeling on negative reviews using LDA

## Results
- Logistic Regression achieved an F1-score of 0.90
- Topic modeling revealed major complaint themes related to product quality,
  usability, content dissatisfaction, and value-for-money

## Tools & Technologies
Python, Pandas, NLTK, Scikit-learn, TF-IDF, LDA, Google Colab

