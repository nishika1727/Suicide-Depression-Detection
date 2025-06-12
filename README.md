# 🧠 Suicide and Depression Detection Using Deep Learning

A deep learning-powered web application that detects whether a given text (tweet, quote, or post) expresses **suicidal** or **depressive** thoughts. Built with an **LSTM model** using **GloVe embeddings**, and deployed through **Streamlit** for an interactive user experience.

---

## 🔍 Problem Statement

Social media often reflects a person’s mental state. Detecting suicidal or depressive content in posts can help in initiating timely support or intervention. This project leverages NLP and deep learning to automate that detection process.

---

## 📊 Dataset

- **Source**: [Kaggle - Suicide Watch Dataset](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch)
- The dataset contains social media posts labeled as:
  - `suicidal/depressed`
  - `not suicidal/depressed`

---

## 🧠 Model Overview

- **Architecture**: LSTM (Long Short-Term Memory)
- **Embeddings**: Pre-trained GloVe word vectors
- **Objective**: Binary classification of text (suicidal/depressive vs. neutral)
- **Frameworks used**: TensorFlow, Keras, Scikit-learn

---

## 🖥️ Streamlit Web App

The Streamlit interface allows users to input a line/post/tweet and receive a prediction.

### 💡 Features:
- Simple text input
- Real-time prediction
- Easy to run locally with minimal setup

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/suicide-depression-detector.git
   cd suicide-depression-detector

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the app:
   ```bash
   streamlit run app.py

## 🔻 Model & Dataset
Due to file size restrictions, the trained model (model.h5) and dataset are not included in this repository.

Please download them manually:

📥 Model file and Dataset: [Google Drive Link](https://drive.google.com/drive/folders/1iQHSNkkB3qYF7ys7xBozjlaqigtuI0k6?usp=drive_link)
