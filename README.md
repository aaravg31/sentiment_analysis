# Sentiment Analysis Projects

## Overview

This repository contains two sentiment analysis projects:
1. **Amazon Reviews Sentiment Analysis**: Analyzing the sentiment of Amazon product reviews using VADER and RoBERTa models.
2. **Article Sentiment Analysis**: Analyzing the sentiment of news articles related to specific companies using VADER.

## Contents

### Amazon Reviews Sentiment Analysis
1. **Data Preprocessing**: Loading and preprocessing a subset of Amazon product reviews.
2. **Tokenization and POS Tagging**: Using NLTK for tokenization and part-of-speech tagging.
3. **VADER Sentiment Analysis**: Performing sentiment analysis using VADER.
4. **RoBERTa Sentiment Analysis**: Performing sentiment analysis using a pre-trained RoBERTa model.
5. **Visualization**: Plotting the distribution of sentiment scores relative to review stars and comparing VADER and RoBERTa results.

### Article Sentiment Analysis
1. **Fetching Articles**: Using the News API to fetch news articles related to specific companies.
2. **Text Extraction**: Extracting text content from the articles.
3. **Duplicate Filtering**: Filtering duplicate articles based on their text content.
4. **VADER Sentiment Analysis**: Performing sentiment analysis using VADER.
5. **Data Storage**: Storing the results in a CSV file.
6. **Visualization**: Plotting sentiment trends over time and the distribution of sentiment scores.

## Files

### Amazon Reviews Sentiment Analysis
- `Amazon_reviews.ipynb`: Jupyter Notebook containing the code for analyzing Amazon reviews.
- `Reviews.csv`: CSV file containing Amazon product reviews.

### Article Sentiment Analysis
- `Article_sentiment.ipynb`: Jupyter Notebook containing the code for analyzing news articles.
- `stored_sentiments.csv`: CSV file storing sentiment analysis results of news articles.

## Usage

1. Navigate to the project directory:
   ```bash
   cd sentiment_analysis_projects
2. Install required packages
3. Set up the News API key:
Create a config.py file in the root directory with the following content:
   ```python
   NEWSAPI_KEY = 'your_newsapi_key_here'


## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python packages (NumPy, Pandas, Matplotlib, Seaborn, NLTK, tqdm, transformers, requests, beautifulsoup4, newsapi-python)

## References

For more details on the Amazon Reviews Sentiment Analysis, you can refer to this [YouTube video](https://www.youtube.com/watch?v=QpzMWQvxXWk&list=PLOTXmQlwik5QOcrBNqVAC3fbeNODjzZca&index=9).

## Author

Aarav Gosalia
