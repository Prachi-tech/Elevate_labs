# 📰 Fake News Detection using NLP and Machine Learning

This project detects whether a news article is **fake** or **real** using **Natural Language Processing (NLP)** and **Logistic Regression**. A simple and efficient **Streamlit web app** is included for live predictions.

---

## 🚀 Project Overview

With the increasing spread of misinformation, especially online, it's crucial to have systems that can identify **fake news** automatically. This project uses a dataset from **Kaggle**, applies text processing techniques using **NLTK**, vectorizes the data using **TF-IDF**, and trains a **Logistic Regression** model to classify the news.

---

## 🧠 Key Features

- Preprocessing of news articles using NLTK  
- Text vectorization using TF-IDF  
- Model training using Logistic Regression  
- Model evaluation (Accuracy, F1 Score, Precision, Recall)  
- Streamlit app for real-time news classification  
- Save and reuse the trained model with `joblib`

---

## 🛠️ Tools and Libraries

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **NLTK**
- **Streamlit**
- **Joblib**
- **Matplotlib** *(optional, for visualization)*

---

## 📁 Dataset

- **Fake.csv** — Contains fake news articles  
- **True.csv** — Contains real news articles  
> Downloaded from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 📌 How It Works

1. Load and combine datasets
2. Clean and preprocess the text
3. Convert text to numerical data using TF-IDF
4. Train/test split
5. Train a Logistic Regression model
6. Evaluate model performance
7. Save the model and vectorizer
8. Build a Streamlit app for live predictions

---

## 📈 Model Performance

- **Accuracy**: 98.46%  
- **F1 Score**: 98.39%  
- Detailed metrics via `classification_report`

---


