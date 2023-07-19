# Sentiment Analysis on Amazon Clothing Products Reviews

This project aims to build several machine learning models to perform sentiment analysis on customer reviews for
clothing products sold on Amazon. The dataset used for this project is scraped by scrapy from Amazon's website and contains
customer reviews and ratings for clothing products.

## Dataset

The dataset used for this project is scraped from Amazon's website and contains 100,000 customer reviews and ratings for
clothing products. The dataset is pre-labeled with the sentiment of each review as positive, negative or neutral.

- 1,2 stars: Negative
- 3 stars: Neutral
- 4,5 stars: Positive

## Approach

The project will use several machine learning algorithms to perform sentiment analysis on the Amazon clothing products
reviews dataset. The following algorithms will be used:

- Support Vector Machine (SVM)
- Logistic Regression
- Naive Bayes
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)
- CNN-LSTM

## Requirements

The following Python libraries are required to run this project:

- pandas
- numpy
- tensorflow
- keras
- scrapy
- sklearn
- nltk
- matplotlib

## Results

The machine learning models achieved the following performance on the held-out test set:

- Support Vector Machine (SVM): 91.68% accuracy
- Logistic Regression: 91.29% accuracy
- Naive Bayes: 88.30% accuracy
- Convolutional Neural Network (CNN): 92.45% accuracy
- Long Short-Term Memory (LSTM): 92.86% accuracy
- CNN-LSTM: 93.19% accuracy

The results show that the CNN-LSTM model achieved the highest accuracy, indicating that it is the best-performing model
for sentiment analysis on Amazon clothing products reviews in the dataset.
