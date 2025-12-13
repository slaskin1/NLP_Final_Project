# Welcome to our Natural Language Processing final project!

# Urgent Care Reviews NLP Project

This project analyzes patient reviews of urgent-care clinics using natural language processing (NLP) techniques.
The workflow includes data collection via the Google Places API, text preprocessing, sentiment analysis, topic modeling, and supervised learning to better understand patient experiences and feedback patterns.

## Data Source
- Public Google Maps reviews collected using the Google Places API

## Preprocessing
- Text normalization and lowercasing
- Expansion of medical abbreviations (e.g., "dr" → "doctor")
- Removal of doctor names
- Tokenization and lemmatization

## Methods
- Sentiment analysis (polarity, subjectivity, NLTK compound)
- Topic modeling using LDA
- Supervised learning using review ratings as labels
  
## File Directory

| **File Name**  | **Description** |
| ------------- | ------------- |
| urgent_care_reviews_CA.csv  | Original scraped data  |
| urgent_care_reviews_CA_fully_preprocessed.csv  | Contains review-level text at each preprocessing stage, from raw reviews to fully cleaned and normalized text, supporting downstream NLP tasks.  | 
| TopicModelling.ipynb | Topic modeling colab |
| DataCollectionPreprocessingSA.ipynb | Preprocessing pipeline |
| Supervised_Learning.ipynb | Colab with supervised learning code |



