%%writefile README.md
# Stock Sentiment Analysis

This repository contains a Colab notebook that performs sentiment analysis on Telegram stock market discussions using machine learning.

## Features
- **Fetch Telegram messages**: Uses Telethon to scrape stock-related discussions.
- **Sentiment analysis**: Processes and analyzes messages using NLTK's Sentiment Intensity Analyzer.
- **Machine learning**: Trains a Random Forest model to classify messages as positive or negative.

## Installation
Install the required libraries:
```bash
pip install telethon nltk scikit-learn
