# Phishing URL Detection Using Machine Learning

## Overview

This project develops a machine learning-based system for detecting phishing URLs using URL-based features.

The objective is to classify URLs into two categories:

- Phishing
- Legitimate

The project focuses on data cleaning, feature analysis, prevention of data leakage, model training, and reliable evaluation.

## Dataset

The original dataset contains:

- Total URLs: 235,795
- Duplicate URL rows: 425
- Unique URLs after duplicate removal: 235,370

Duplicate URLs were removed before model evaluation.

The dataset contains URL-based features such as:

- URL length
- Domain length
- Number of subdomains
- Number of digits
- Number of letters
- Digit ratio
- Letter ratio
- Number of special characters
- Special character ratio
- HTTPS usage
- Domain IP indicator
- TLD length
- Obfuscation-related features

## Data Cleaning

Duplicate URLs were identified and removed.

The dataset contained 425 duplicate rows, corresponding to approximately 0.18% of the dataset.

An additional check was performed to determine whether the same URL appeared with different labels.

Result:

```text
URLs appearing with multiple different labels: 0