# CODSOFT-TASK-3 SMS Spam Classification

This project aims to classify SMS messages as spam or legitimate (ham) using various machine learning techniques. The classification models are built using TF-IDF for text feature extraction and three different classifiers: Naive Bayes, Logistic Regression, and Support Vector Machines (SVM).

Project Overview

The dataset used for this project contains SMS messages labeled as spam or ham. The goal is to build and evaluate models that can accurately identify spam messages.

Key Features

- *Data Preprocessing*: Cleaning the dataset and preparing it for model training.
- *Exploratory Data Analysis (EDA)*: Understanding the data distribution, message lengths, and common words in spam and ham messages.
- *Feature Extraction*: Converting text data to numerical features using TF-IDF.
- *Model Training and Evaluation*: Building and evaluating Naive Bayes, Logistic Regression, and SVM classifiers.
- *Visualization*: Visualizing the distribution of messages, message lengths, and important features for classification.

Dataset

The dataset used in this project is a CSV file containing SMS messages labeled as spam or ham. The dataset is preprocessed to retain relevant columns and map labels to binary values.

Exploratory Data Analysis (EDA)

- *Missing Values*: Checking for any missing values in the dataset.
- *Label Distribution*: Visualizing the distribution of spam and ham messages.
- *Message Length*: Analyzing and visualizing the length of messages for both classes.
- *Word Clouds*: Generating word clouds to visualize common words in spam and ham messages.
- *Common Words*: Identifying the most common words in spam and ham messages.
- *Top Features*: Visualizing the top features for the Naive Bayes classifier based on TF-IDF scores.

 Models and Evaluation

- *Naive Bayes*: A probabilistic classifier that uses the Bayes theorem.
- *Logistic Regression*: A linear model for binary classification.
- *Support Vector Machines (SVM)*: A classifier that finds the optimal hyperplane for separating classes.

The models are evaluated using accuracy scores and classification reports, providing insights into precision, recall, and F1-score for each classifier.

Results

The performance of the classifiers is summarized as follows:

- *Naive Bayes*: Achieved an accuracy of 96.23%.
- *Logistic Regression*: Achieved an accuracy of 96.59%.
- *SVM*: Achieved an accuracy of 98.30%.

 Visualization

- *Distribution Plots*: Show the distribution of spam vs. ham messages and message lengths.
- *Word Clouds*: Visualize common words in spam and ham messages.
- *Top Features*: Bar plot showing the top 10 important features for the Naive Bayes classifier based on log probabilities.

This project demonstrates the application of machine learning techniques for classifying SMS messages as spam or ham. The combination of TF-IDF and various classifiers provides a robust approach to spam detection, achieving high accuracy across different models.
