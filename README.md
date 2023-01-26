# Twitter Emotion Recognition

In this repository we are going to explore twitter's dataset and using basic machine learning and deep learning models to predict each tweet's emotion.

# Datasets

You can download the dataset from here: [Dataset](https://drive.google.com/file/d/1y_wzYnug2a28LmeKmrt5NORWkVBI_i4z/view?usp=sharing)

## How To Run?
Language: Python 3+  
Recommended way of running: use the `jupyter notebook` command

## 1st Section
For the 1st section we are going to explore the different tools that we can use in order to classify objects. In this section we are going to learn about:
- Data Preparation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Simple Model Building (Naive Bayes)
- Simple Deep Learning Models (Word2Vec)
- Clustering (K-means)
- High-Dimension Visualization (t-SNE)

## 2nd Section
For the 2nd section we are going to do the twitter emotion recognition, where we will be doing some feature engineering and using different kinds of models in order to effectively predict the emotion class for each tweets.

Some preprocessing we had done on the dataset:
- Convert all text to lowercase
- Remove stop words from text
- Remove all mentions
- Remove hashtags from text
- Remove URLs from text
- Turn emojis into words

Features that we are going to focus on:
- Number of top words from each emotion
- Preprocessed text
- Hashtags

Models used:
- Logistic regression
- Multi-class decision tree
- Multi-class random forest
- Naive-Bayes 
- KNN
- Support vector machine (SVM)
- CNN + Word embedding
