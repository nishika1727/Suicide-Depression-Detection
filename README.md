# 🧠 Suicide and Depression Detection Using Deep Learning

This project is a deep learning-powered web app that detects whether a given text (tweet, quote, or post) indicates suicidal or depressive content. Built using LSTM with GloVe word embeddings and deployed via Streamlit.

## 🔍 Problem Statement
Social media platforms contain posts that may indicate a person in distress. Identifying such posts using AI can be a step toward providing timely help and intervention.

## 📊 Dataset
- **Source**: [Kaggle - Suicide Detection](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch)
- Contains labeled data indicating whether text is **suicidal/depressed** or **not**.

## 🧠 Model
- Deep learning model: **LSTM**
- Embedding: **Pre-trained GloVe vectors**
- Trained to classify text as **suicidal/depressive** or **neutral**

## 🖥️ Streamlit App
- Input: Any line/post/tweet
- Output: Label indicating presence of suicidal/depressive tone
- Interface built using **Streamlit**
