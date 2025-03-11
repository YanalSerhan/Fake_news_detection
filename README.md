# Fake_news_detection

This project implements a Fake News Detection system using Logistic Regression, a simple yet effective machine learning model for binary text classification. The goal is to distinguish between fake and real news articles based on their textual content.

## Dataset
The model is trained on Kaggle's "Fake and Real News" dataset, which contains:

* Fake.csv – Fake news articles.
* True.csv – Real news articles.

## Preprocessing Steps
1. Text Cleaning: Lowercasing, removing special characters and punctuation.
2. Vectorization: Converting text into numerical format using TF-IDF (Term Frequency-Inverse Document Frequency).
3. Splitting Data: 80% for training, 20% for testing.

## Model Training
* Algorithm: Logistic Regression
* Feature Extraction: TF-IDF vectorization
* Evaluation Metrics: Accuracy, Precision, Recall, and F1-score

## Results
The model achieved 98% accuracy on the test dataset, demonstrating its effectiveness in identifying fake news.
