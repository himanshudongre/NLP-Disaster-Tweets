# NLP Disaster Tweets Kaggle Competition

## Problem Description

Twitter is a crucial communication platform during emergencies, where people often report disasters in real-time. However, distinguishing between tweets that genuinely report disasters and those that use disaster-related language metaphorically is challenging for machines. The goal of this competition is to build a machine learning model that predicts whether a tweet is about a real disaster or not.

### Dataset Details

The dataset consists of approximately 10,000 tweets, each labeled as either disaster-related (1) or not (0). Alongside the text, the dataset provides additional metadata, including:
- **Keyword**: A specific word from the tweet (optional).
- **Location**: Where the tweet originated (optional).

### Competition Objective

The task is to classify tweets as disaster-related (1) or not (0). Submissions are evaluated using the F1-score, which balances precision and recall to assess model performance.

### Files in the Dataset
1. `train.csv`: Contains labeled tweets for training.
2. `test.csv`: Contains unlabeled tweets for prediction.
3. `sample_submission.csv`: Template for submitting predictions.

The dataset is available at: https://www.kaggle.com/competitions/nlp-getting-started/data
