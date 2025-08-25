# NLP-Sentiment-Analysis-Restaurant-Reviews

## 📋 Project Overview

This project implements a sentiment analysis model to classify restaurant reviews as either positive or negative.
It provides a practical example of a natural language processing (NLP) workflow, covering text preprocessing,
feature engineering using a bag-of-words model, and training a machine learning classifier. 
The goal is to accurately predict customer sentiment based on a given review.

## 📈 Methodology

1.  **Data Loading**: The project begins by loading a dataset of restaurant reviews from a tab-separated values (TSV) file.
2.  **Text Preprocessing**: Reviews are cleaned by removing stop words and punctuation and are then lemmatized to reduce words to their root form.
3.  **Feature Extraction**: The preprocessed text data is converted into a numerical format using a **CountVectorizer**, which creates a bag-of-words model.
4.  **Model Training**: A **Naive Bayes classifier** from `scikit-learn` is trained on the vectorized data.
5.  **Model Evaluation**: The model's performance is assessed using a confusion matrix and accuracy scores to measure its effectiveness.

## 📁 Repository Contents

* `Sentiment analysis restaurant reviews.ipynb`: The main Jupyter Notebook that documents the entire workflow, from data cleaning and preprocessing to model training and evaluation. It also includes the code for a simple GUI using `tkinter`.
* `Restaurant_Reviews.tsv`: The dataset of 1,000 restaurant reviews, each labeled with a sentiment score (1 for positive, 0 for negative).

## 📦 Requirements

This project requires a Python environment with the following libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `warnings`
* `joblib`
* `nltk`
* `sklearn`
* `tkinter`
