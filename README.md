# Sentiment Analysis Using Text and Audio Transcription

## Project Overview
This project performs sentiment analysis on textual and audio data. Using preprocessed news headlines, descriptions, and audio transcripts, it classifies the data into positive and negative sentiments with the help of Logistic Regression and LSTM models.

## Features
- **Data Processing**: Standardizes and cleans multiple text datasets for consistency.
- **Audio Transcription**: Converts audio data to text using silence-based segmentation and speech recognition.
- **Sentiment Analysis**: Predicts sentiment classes using TextBlob for scoring and models for classification.
- **Model Evaluation**: Visualizes model performance with metrics and distribution plots.

## Installation
Clone this repository and install dependencies:
```bash
git clone https://github.com/SparshK312/sentiment-analysis-machine-learning.git
cd sentiment-analysis-machine-learning
pip install -r requirements.txt
