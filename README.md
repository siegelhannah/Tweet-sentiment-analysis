# Sentiment Analysis of Tweets about the Final Season of Game of Thrones

## Description

This project analyzes approximately 20,000 tweets about the final season of **Game of Thrones**. The goal is to break down each tweet into individual words, assign sentiment scores to the words, and evaluate the overall sentiment of each tweet. This analysis provides insights into public sentiment toward the final season.

## Installation Instructions

To run this project, follow these steps:

1. Clone the repository:
   git clone https://github.com/siegelhannah/Tweet-sentiment-analysis.git
2. Navigate to the project directory:
   cd Tweet-sentiment-analysis
4. Install required Python packages
   pip install pandas numpy matplotlib scikit-learn jupyter

## Usage

1. Open the Jupyter Notebook:
   jupyter notebook TweetNLPAnalysis.ipynb
2. Follow the notebook to:
   - Load and preprocess the Twitter dataset.
   - Tokenize tweets into individual words.
   - Use the VADER sentiment lexicon to assign sentiment scores.
   - Calculate and visualize overall sentiment toward Game of Thrones.
  
## Files Overview

This repository contains the following files:

- sentiment_analysis.ipynb: Jupyter Notebook with the full implementation of the sentiment analysis.
- gotTwitter.csv: Dataset containing ~20,000 tweets about the final season of Game of Thrones.
- vader_lexicon.txt: Sentiment lexicon used to assign sentiment scores to words.
