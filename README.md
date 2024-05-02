## Project Overview
This project applies several machine learning models to perform sentiment analysis on tweets. It explores different demographic groups and uses various features to understand how well these models perform across different datasets.

## Technologies
- Python
- Pandas, NumPy
- Matplotlib
- NLTK
- Scikit-Learn

## Data Preprocessing
The dataset class handles the loading and preprocessing of tweet datasets. This includes:
- Reading data from pickled files.
- Handling different demographic groups.
- Text processing and length calculation.

## Feature Selection
Mutual information is used for selecting relevant features from the dataset, focusing on parts of speech and tweet length.

## Machine Learning Models
The project evaluates the following models:
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes (GNB)
- Logistic Regression (LR)

Each model is tested with TF-IDF and embedding features.

## Evaluation
The models are evaluated using classification reports to understand their performance in terms of precision, recall, and F1-score. Additionally, the logistic regression model's performance is analyzed based on prediction confidence ranges.

## POS Tagging
Part-of-speech tagging is performed on the dataset to analyze the distribution of different POS tags in the tweets.

## Mutual Information Classification
This section of the project focuses on the application of mutual information for feature selection in sentiment analysis. Mutual information is a statistical measure that assesses the dependency between variables. In this context, it helps in determining which features in the tweet data are most informative about the sentiment.

