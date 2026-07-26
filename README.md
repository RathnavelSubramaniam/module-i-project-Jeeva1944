# Stock Market Sentiment Analysis using Sentence Transformers and Random Forest

##  Project Overview

This project performs **Stock Market Sentiment Analysis** by classifying financial news headlines into sentiment categories using **Sentence Transformers** for text embeddings and a **Random Forest Classifier** for prediction.

The goal is to determine whether a financial news headline expresses **positive, negative, or neutral sentiment**, which can help investors and analysts understand market reactions.

---

##  Objectives

- Preprocess financial news text.
- Generate contextual sentence embeddings using Sentence Transformers.
- Train a Random Forest classifier on the generated embeddings.
- Evaluate model performance using classification metrics.
- Predict sentiment for unseen financial news articles.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Sentence Transformers
- Transformers
- Matplotlib
- Seaborn

---

##  Dataset

The dataset contains financial news headlines along with their corresponding sentiment labels.

Typical columns include:

- News Headline
- Sentiment Label

The dataset is cleaned before model training by removing missing values and preparing the text.

---

##  Workflow

1. Load Dataset
2. Data Exploration
3. Data Cleaning
4. Text Preprocessing
5. Generate Sentence Embeddings
6. Split Training and Testing Data
7. Train Random Forest Classifier
8. Evaluate Model Performance
9. Predict Sentiment for Unseen News Headlines

---

##  Model Used

### Sentence Transformer

Sentence Transformers convert each news headline into a dense numerical vector that captures its semantic meaning.

Advantages:

- Context-aware embeddings
- Better semantic understanding
- High-quality sentence representations

### Random Forest Classifier

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy.

Advantages:

- High accuracy
- Reduces overfitting
- Handles high-dimensional embeddings effectively

---

##  Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

