# Text Classification using Machine Learning (NLP)

## Abstract

This project presents an end-to-end Natural Language Processing (NLP) workflow for sentiment analysis using the Twitter US Airline Sentiment dataset. Customer tweets are classified into positive, neutral, and negative sentiment categories using TF-IDF feature extraction and a Logistic Regression classifier. The project demonstrates the complete machine learning pipeline, including preprocessing, feature engineering, model training, evaluation, and prediction.

---

# Introduction

Sentiment analysis is a popular Natural Language Processing task that aims to determine the emotional tone of textual data. Organizations use sentiment analysis to monitor customer satisfaction, analyze product reviews, and improve services based on public opinion.

This project focuses on airline-related tweets to automatically classify customer sentiment.

---

# Dataset

The dataset contains customer tweets directed at major U.S. airlines.

Main attributes include:

- Tweet Text
- Airline
- Sentiment
- Confidence Score
- Negative Reason
- Timestamp

---

# Methodology

The project follows these stages:

1. Data Loading
2. Exploratory Data Analysis
3. Text Cleaning
4. TF-IDF Vectorization
5. Logistic Regression Training
6. Model Evaluation
7. Sentiment Prediction

---

# Model

Feature Extraction:

- TF-IDF Vectorizer

Classifier:

- Logistic Regression

---

# Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

---

# Results

The classifier successfully predicts airline tweet sentiment and demonstrates the effectiveness of traditional machine learning techniques for text classification.

---

# Future Improvements

- Compare multiple classifiers.
- Apply hyperparameter tuning.
- Use Word2Vec and GloVe embeddings.
- Fine-tune transformer models such as BERT.
- Deploy the model using Streamlit or FastAPI.

---

# Conclusion

This project demonstrates an end-to-end NLP workflow, from raw text preprocessing to sentiment prediction. It provides a solid foundation for more advanced Natural Language Processing applications.