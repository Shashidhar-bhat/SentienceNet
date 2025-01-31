# SentienceNet: AI for Social Well-Being

## Overview

SentienceNet leverages Artificial Intelligence to detect suicidal ideation in social media content, helping identify distress signals in online platforms like Reddit and Twitter. This project uses Natural Language Processing (NLP) techniques, machine learning (ML), and deep learning (DL) models to classify posts that may indicate suicidal thoughts and provide timely interventions.

## Project Motivation

With the rise of online communities, more individuals are sharing their struggles with mental health, often in anonymous or public forums. While this can be a valuable space for expression, it also presents a risk for those experiencing severe mental distress, including suicidal ideation. By using advanced AI models, this project aims to identify such posts and contribute to mental health safety.

## Features

- **Reddit and Twitter Data**: Data collection from specific subreddits and Twitter based on targeted keywords.
- **Suicidal Ideation Detection**: Classification of posts into suicidal ideation and non-suicidal based on NLP models.
- **High Accuracy**: Achieved 96% accuracy using a Random Forest Classifier and 97% with a BiLSTM model.
- **Data Visualizations**: Word clouds for frequent terms in both Reddit and Twitter data.

## Datasets

Two datasets were collected for this project:

1. **Reddit**: Data from subreddits such as 'suicidewatch', 'depression', and 'anxiety', containing 2,958 suicidal ideation samples and 5,381 non-suicidal posts.
2. **Twitter**: Tweets containing keywords like 'end my life', 'die', etc., with a total of 3,000 tweets related to suicidal ideation.

## Getting Started

### Prerequisites

- Python 3.6+
- Install dependencies using `pip`:

```bash
pip install -r requirements.txt
