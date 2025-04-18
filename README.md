
# Sentiment Analysis of Android App Reviews using Machine Learning

## Overview
This project evaluates sentiment analysis models on customer reviews of Android applications. Using a dataset of 20,000 Amazon app reviews, we implemented and compared the performance of two machine learning algorithms: Support Vector Machines (SVM) and K-Nearest Neighbors (KNN). The aim was to identify the most effective model for analyzing sentiment (positive, negative, neutral) to help businesses better understand user feedback.

## Algorithms Used
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)

## Dataset
- 20,000 Amazon reviews, labeled as Positive, Negative, or Neutral
- Split: 50% training and 50% test data

## Tools & Libraries
- Python
- pandas, NumPy
- scikit-learn
- NLTK (tokenization, stopwords, lemmatization)
- matplotlib, seaborn

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Visualizations
- Bar chart comparing algorithm performance
- Confusion matrices
- Pie charts of sentiment distribution per app
- Combined bar plot for sentiment distribution

## Key Findings
- **SVM** outperformed KNN in all metrics, with an F1-score of 77.52% vs. 71.63%
- SVM was applied to reviews from 9 Android apps to identify customer sentiment patterns
- The most positively reviewed app company was **AAD_1** with 106 positive reviews

## How to Run
1. Load the dataset (or replace with your own CSV of reviews)
2. Run the preprocessing pipeline (NLTK, vectorization)
3. Train and evaluate both models (SVM and KNN)
4. Visualize performance and interpret sentiment results

## Author
Havilah Osewajumede Oriazowan
