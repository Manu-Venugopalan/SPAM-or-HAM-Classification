# SPAM-or-HAM-Classification

## 📬 Ham or Spam - SMS Classification using Machine Learning
![Made with Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
![Scikit-learn](https://img.shields.io/badge/Powered%20by-scikit--learn-blue)
![Natural Language Processing](https://img.shields.io/badge/NLP-Text%20Classification-yellowgreen)
![TF-IDF](https://img.shields.io/badge/Vectorizer-TF--IDF-orange)
![Dataset](https://img.shields.io/badge/Dataset-SMS%20Spam%20Collection-lightgrey)
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-yellow)

This project focuses on building a **Spam Detection Model** that classifies SMS messages as either **Ham (legitimate)** or **Spam** using natural language processing (NLP) techniques and machine learning models. The goal is to automate the detection of unsolicited messages and reduce digital clutter for users.

### 🔍 Overview
- Preprocessing of SMS messages: lowercasing, punctuation removal, stop word filtering, etc.
- Feature extraction using **TF-IDF Vectorizer**
- Implementation of classification algorithms including:
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Logistic Regression
- Evaluation of model performance using accuracy, precision, recall, and F1-score

### 📊 Dataset
The dataset used is the classic [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset), containing 5,574 messages labeled as 'ham' or 'spam'. Else you can use the dataset that I have added to this repository

### 🧠 Key Learnings
- Understanding of NLP preprocessing pipelines
- Comparison of different ML models for text classification
- Importance of evaluation metrics in imbalanced classification tasks

### 🚀 How to Use
1. Clone the repository
2. Install dependencies from `requirements.txt`
3. Run the `Ham_or_Spam.ipynb` notebook

### ✅ Results
The Naive Bayes model performed best for this particular dataset, achieving high accuracy and precision in spam detection.
