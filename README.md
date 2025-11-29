# NLP Sentiment Analysis using TF-IDF and RoBERTa

This project presents a hybrid Natural Language Processing (NLP) approach for sentiment classification of airline-related tweets by combining traditional TF-IDF features with contextual RoBERTa embeddings.

## Overview
The model classifies tweets into three sentiment classes: **positive**, **neutral**, and **negative** using a hybrid feature representation that integrates lexical frequency and deep contextual semantics.

## Dataset
- Twitter US Airline Sentiment Dataset (Kaggle)
- 14,427 labeled tweets
- Strong class imbalance addressed using class-weighted learning

## Methodology
- Text preprocessing and normalization
- TF-IDF feature extraction (unigrams + bigrams)
- Contextual sentence embeddings using **RoBERTa**
- Hybrid feature fusion (TF-IDF + embeddings)
- Supervised models: Logistic Regression, Linear SVM, XGBoost, Decision Tree

## Results
- Best performance achieved with **Logistic Regression** on hybrid features
- Accuracy: 80%
- Strong macro-F1 score demonstrating robustness to class imbalance

## Tools & Libraries
Python, scikit-learn, Sentence Transformers, RoBERTa, Pandas, NumPy, Matplotlib, Seaborn, NLTK, spaCy

## Author
Abide Mandaza
