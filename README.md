# Sentiment-AI-Review-Classifier

A simple NLP project to classify movie reviews as **positive** or **negative** using machine learning and text preprocessing.

---

## 📌 Project Overview

This project uses real-world natural language processing (NLP) techniques to:
- Clean and preprocess movie reviews
- Convert text into numbers using **TF-IDF**
- Train a sentiment classifier using **Logistic Regression**
- Predict whether a new review is **positive** or **negative**

---

## 🧰 Tools Used

- Python 🐍
- Pandas
- Scikit-learn
- NLTK (for stopwords, lemmatization)
- Matplotlib (for optional graphs)

---

## 🧼 Step-by-Step Workflow

1. **Load the dataset**
2. **Clean the text** (remove HTML, symbols, lowercase, lemmatize)
3. **Transform text into numbers** with TF-IDF
4. **Train the model** with Logistic Regression
5. **Evaluate the model** using accuracy and confusion matrix
6. **Predict sentiment** of custom reviews

---

## ✨ Example Predictions

```python
predict_sentiment("This was the best movie I've ever seen. Amazing!")
# Output: positive

predict_sentiment("It was awful, I hated every minute.")
# Output: negative
