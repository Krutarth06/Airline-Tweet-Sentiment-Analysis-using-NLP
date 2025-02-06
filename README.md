# Airline-Tweet-Sentiment-Analysis-using-NLP

This project implements sentiment analysis on airline tweets using Natural Language Processing (NLP) and Random Forest Classifier.

## Project Overview

The model analyzes tweets to classify them into three sentiment categories:
- Positive
- Neutral
- Negative

## Technologies Used

- Python 3.13
- NLTK
- scikit-learn
- pandas
- numpy
- matplotlib
- Regular Expressions (re)

## Model Performance

- Accuracy: 75.92%
- Algorithm: Random Forest Classifier
- Features: 2500 TF-IDF features

## Installation
- pip install nltk
- pip install scikit-learn
- pip install pandas
- pip install numpy


## Data Processing Steps

1. Text preprocessing:
   - Special character removal
   - Single character removal
   - Multiple space removal
   - Lowercase conversion

2. Feature extraction:
   - TF-IDF Vectorization
   - Stop words removal
   - Feature selection (max_features=2500)

3. Model Training:
   - 80-20 train-test split
   - Random Forest with 200 estimators

## Usage

1. Load your dataset in CSV format
2. Run the preprocessing pipeline
3. Train the model
4. Make predictions on new data

## Model Parameters

- TF-IDF Parameters:
  - max_features: 2500
  - min_df: 7
  - max_df: 0.8

- Random Forest Parameters:
  - n_estimators: 200
  - random_state: 0
