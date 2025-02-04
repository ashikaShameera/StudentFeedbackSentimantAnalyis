# Sentiment Analysis Comparison Project

A comprehensive comparison of different ML/DL approaches for student feedback sentiment analysis.

## 📌 Project Overview
- Analyzed 10,000 student feedback records
- Compared 7 different approaches:
  - Traditional ML models (Logistic Regression, Random Forest, SVM, Naive Bayes, XGBoost)
  - Deep Learning models (BERT, Custom Neural Network)
  - TextBlob (Rule-based approach)
  - PowerBI built-in sentiment analysis
- Developed interactive PowerBI dashboard
- Neural Network model showed best performance

## 📂 Dataset
- 10,000 student feedback records
- Labeled sentiment (Positive/Negative/Neutral)
- Preprocessed text data:
  - Cleaning
  - Tokenization
  - Stemming/Lemmatization

## 🧠 ML/DL Approaches
```python
models = {
    'Logistic Regression': LogisticRegression(max_iter=1000),
    'Random Forest': RandomForestClassifier(),
    'SVM': SVC(),
    'Naive Bayes': MultinomialNB(),
    'XGBoost': XGBClassifier(),
    'BERT': 'bert-base-uncased',
    'Neural Network': Custom TensorFlow/Keras model
}

```

## 📊 Power BI Dashboard
Developed an interactive business intelligence dashboard for sentiment analysis visualization:

![PowerBI Dashboard](images/dashboard-screenshot.png)
