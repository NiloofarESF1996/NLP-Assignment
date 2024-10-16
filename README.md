# ANLP: Advanced Natural Language Processing Project

## Overview

This repository contains the code and analysis for a project focused on **Advanced Natural Language Processing (ANLP)**. The goal of this project is to apply advanced NLP techniques to solve a specific problem, leveraging various tools and libraries in Python.

One of the main objectives of this project is to develop sentiment classifiers that can accurately classify movie reviews by sentiment (positive or negative), using machine learning models such as **Naive Bayes** and custom-built methods. This project also explores the steps involved in **data extraction**, **feature engineering**, and **model evaluation**.

### Objectives:
- Implement key natural language processing (NLP) models and techniques.
- Preprocess and analyze textual data.
- Develop machine learning models to classify movie reviews by sentiment.
- Provide actionable insights for decision-making in the movie industry based on the sentiment of reviews.
- Evaluate the performance of classification models using advanced metrics.

## Project Structure

- **Data Preprocessing**: The notebook includes steps to clean and preprocess the raw data, including:
  - Tokenization
  - Stopword removal
  - Word list creation
  - Data extraction via SQL queries and Python
- **Feature Engineering**: Features are extracted from the text data using techniques like Bag-of-Words (BoW), transforming the raw text into numerical representations for model training.
- **Modeling**: Sentiment classifiers were developed using:
  - Naive Bayes
  - A custom word list approach
- **Model Evaluation**: Models were evaluated based on accuracy and confusion matrices. Results include:
  - Naive Bayes: **88% accuracy**
  - Custom Word List: **85% accuracy**

## Data

The data used in this project consists of movie reviews, each labeled as either positive or negative. The data was extracted using SQL queries and processed using Python and **NLTK**.

### Preprocessing Steps:
- Tokenization of text data
- Stopword Removal to focus on relevant words
- Feature extraction using Bag-of-Words to create a numerical representation of text for model training.

## Models

The following models were implemented and evaluated in the project:
- **Naive Bayes Classifier**: Achieved an accuracy of **88%** in classifying movie reviews by sentiment.
- **Custom Word List Classifier**: A simpler, custom-built approach that achieved **85% accuracy** in sentiment classification.

### Key Features:
- **Data Extraction**: Textual data was extracted and preprocessed using SQL queries, Python, and the NLTK library.
- **Sentiment Classification**: Developed machine learning models to classify movie reviews as positive or negative.
- **Feature Engineering**: Created feature sets for model training by transforming text data into numerical representations using techniques like Bag-of-Words.
- **Model Evaluation**: Models were evaluated using confusion matrices and accuracy scores.

## Results

The key results and findings from the analysis are summarized in the notebook. Models were evaluated based on accuracy and confusion matrices, with the Naive Bayes classifier achieving the best performance.

### Key Achievements:
- Developed sentiment classifiers using Naive Bayes and a custom word list approach.
- Achieved high accuracy rates in sentiment classification (88% for Naive Bayes, 85% for the custom word list model).
- Created a pipeline for preprocessing and feature extraction from raw text.
- Generated insights that can be used for decision-making in the movie industry.

## How to Run

### Prerequisites:
- Python 3.x
- Libraries: `pandas`, `numpy`, `scikit-learn`, `nltk`, `matplotlib`

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/anlp-project.git
