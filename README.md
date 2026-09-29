# 🔐 Phishing URL Detection using Machine Learning

> A machine learning system for detecting whether a URL is **legitimate or potentially phishing** using URL-based features and an XGBoost classification model.

---

## 🚀 Overview

Phishing attacks are one of the most common forms of cybercrime, where attackers use malicious URLs to trick users into revealing sensitive information such as passwords, banking credentials, and personal data.

This project uses **machine learning and URL-based feature engineering** to automatically classify URLs as:

- 🟢 **Legitimate**
- 🔴 **Phishing**

The project uses **XGBoost**, a powerful gradient-boosting algorithm, to learn patterns from URL characteristics and make predictions on previously unseen URLs.

---

## ✨ Key Features

- 🔎 URL-based feature extraction
- 🧹 Data preprocessing and cleaning
- 📊 Exploratory Data Analysis
- 🤖 XGBoost classification model
- 💾 Trained model saved using Pickle
- 🧪 Jupyter notebook for experimentation
- 🌐 Application interface for URL prediction
- 📦 Reproducible Python environment using `requirements.txt`

---

## 🧠 Machine Learning Workflow

```text
Raw URL Dataset
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
URL Feature Extraction
       ↓
Feature Preprocessing
       ↓
Train / Test Split
       ↓
XGBoost Classifier
       ↓
Model Evaluation
       ↓
Saved Trained Model
       ↓
URL Prediction
