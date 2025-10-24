# E-Commerce-Sentiment-Analysis
E-Commerce-Sentiment-Analysis/
│
├── data/
│   └── ecommerce_reviews.csv
├── notebooks/
│   └── sentiment_analysis.ipynb
├── requirements.txt
└── README.md

| review                                  | sentiment |
| --------------------------------------- | --------- |
| I love this product, very useful!       | 1         |
| The product is terrible, waste of money | 0         |
| Excellent quality and fast delivery     | 1         |
| Not satisfied, it broke in a week       | 0         |
---------
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn


# E-Commerce Sentiment Analysis

## Overview
This project analyzes customer reviews of e-commerce products and classifies them as **positive** or **negative** using **Natural Language Processing (NLP)** and **Machine Learning (ML)**.

## Features
- Text cleaning (removes punctuation, lowercase, stemming, stopwords removal)
- Feature extraction using **CountVectorizer** or **TF-IDF**
- Classification using **Logistic Regression** and **Naive Bayes**
- Evaluation with **accuracy**, **confusion matrix**, and **classification report**

## Dataset
- `ecommerce_reviews.csv` contains:
  - `review`: customer review text
  - `sentiment`: 0 = Negative, 1 = Positive

## How to Run
1. Install dependencies:
pip install -r requirements.txt
2. Run `sentiment_analysis.ipynb` in Jupyter Notebook or VSCode.

## Key Concepts
- NLP: preprocessing text data
- ML: training classifiers for sentiment prediction
- Feature extraction: converting text to numerical vectors
