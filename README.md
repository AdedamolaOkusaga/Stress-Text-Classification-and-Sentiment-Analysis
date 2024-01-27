# Stress-Text-Classification-and-Sentiment-Analysis

# Sentiment Analysis on Stress Dataset

This project focuses on performing sentiment analysis on the Stress dataset using machine learning techniques in Python. The objective is to analyze the sentiment of text data and provide valuable insights into the sentiments expressed.

## Dataset Overview

The Stress dataset is sourced from Kaggle and is stored in the 'Stress.csv' file. It consists of text data and corresponding labels indicating positive or negative sentiment. The dataset has been preprocessed, including tokenization, removal of stopwords and punctuation, and lemmatization, to prepare it for analysis.

## Text Preprocessing

The text data in the dataset is subjected to various preprocessing techniques to improve the quality of the data. This includes tokenization to break the text into individual words, removal of stopwords and punctuation to eliminate noise, and lemmatization to reduce words to their base form.

## Word Cloud Visualization

A word cloud is generated to visually represent the most frequent words in the preprocessed text. The word cloud provides a quick overview of the prominent terms present in the dataset, giving insights into the overall sentiment expressed.

## Sentiment Analysis

The sentiment analysis is performed using the VADER sentiment analyzer, which assigns a sentiment label of either positive or negative to each text entry based on its sentiment score. This analysis helps in understanding the prevailing sentiment patterns in the dataset.

## Machine Learning Classification

The preprocessed text data is vectorized using the TF-IDF technique, which converts the text into numerical features. The dataset is then split into training and testing sets. A logistic regression classifier is trained on the training set and used to predict the sentiment labels for the testing set. Various evaluation metrics, such as accuracy, precision, sensitivity, F1-score, and ROC-AUC score, are calculated to assess the performance of the model.

## Visualization of Results

The results of the sentiment analysis and classification are visualized to provide a clearer understanding. The confusion matrix is displayed as a heatmap, allowing for an intuitive representation of the model's performance. Additionally, separate word clouds are generated for the positive and negative sentiment categories, highlighting the most frequent words associated with each sentiment.

This project provides a comprehensive analysis of the Stress dataset, employing text preprocessing, sentiment analysis, and machine learning classification techniques. The insights gained from this analysis can be valuable in understanding sentiment patterns and making informed decisions based on text data.
