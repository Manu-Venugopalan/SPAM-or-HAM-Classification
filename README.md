# SPAM-or-HAM-Classification

## 📬 Ham or Spam - SMS Classification using Machine Learning

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
