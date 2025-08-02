# Sentiment Analysis for Finance

This repository contains two sentiment analysis projects focused on financial texts related to major market players Tesla and NVIDIA. Both projects utilize **FinBERT**, a pre-trained language model fine-tuned specifically for financial sentiment analysis, to extract meaningful insights from social media and news data.

---

## Projects Overview

### 1. Tesla Tweet Sentiment Analysis  
This project analyzes tweets related to Tesla using FinBERT. Tesla’s market influence and the high-profile presence of its CEO on social media make Twitter sentiment a valuable indicator. The pipeline includes data collection, text preprocessing, sentiment classification (positive, negative, neutral), and visualization of sentiment trends over time from a financial perspective.

### 2. NVIDIA News Sentiment Analysis  
This project applies FinBERT to the latest news headlines about NVIDIA to gauge overall market sentiment. Headlines are classified into positive, negative, or neutral categories to help understand how news events potentially impact NVIDIA’s stock sentiment and market reactions.

---

## Key Features

- Data collection from Twitter (Tesla) and news sources (NVIDIA)  
- Text preprocessing tailored for financial language  
- Sentiment classification using FinBERT, designed for financial contexts  
- Visualization of sentiment trends and distributions  
- Insights into how public sentiment may influence market behavior  

---

## Folder Structure

/Sentiment_Analysis_for_Finance <br>
│ <br>
├── Tesla_Tweet_Sentiment_Analysis.ipynb <br>
└── Nvidia_News_Sentiment_Analysis.ipynb <br>

## Requirements

- Python 3.11  
- Libraries: `transformers`, `torch` or `tensorflow`, `pandas`, `numpy`, `matplotlib`, `tweepy` (for Twitter data collection)  

---

## Usage

1. Collect or load data into the `data/` directory  
2. Run preprocessing scripts or notebooks  
3. Perform sentiment classification with FinBERT  
4. Visualize and interpret sentiment trends  

---

## Notes

- FinBERT is specifically optimized for financial texts and may provide better results than generic sentiment models for this domain.  
- Sentiment analysis results should be combined with other financial indicators for comprehensive market analysis.
