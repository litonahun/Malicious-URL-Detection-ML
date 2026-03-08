# Malicious URL Detection using Machine Learning

This project focuses on identifying and classifying malicious URLs (Phishing, Malware, Defacement) using various Machine Learning models. It was developed as a graduation project at Ankara University to move beyond traditional blacklisting methods.

## 🚀 Project Overview

- **Goal**: Real-time detection of malicious behavior through URL analysis.
- **Dataset**: Over 1 million URLs from Kaggle (Lexical and Host-based features).
- **Performance**: Achieved **91% accuracy** using Support Vector Machines (SVM).

## 📁 Repository Structure

- **Kaggle Malicious URL Dataset**: Code for 4-class classification (Benign, Malware, Phishing, Defacement).
- **Kaggle Phishing Site URLs Dataset**: Code for binary classification ("Good" vs "Bad").
- **ANKARA UNIVERSITY.pdf**: Full technical report and research methodology.

## 📊 Methodology

1. **Feature Extraction**: Extracted Lexical (URL length, special characters), Host-based (WHOIS data, IP info), and Content-based features.
2. **Model Training**: Evaluated SVM, Random Forest, Decision Trees, Logistic Regression, and Naive Bayes.
3. **Evaluation**: Compared models based on Accuracy, Precision, and Recall scores.

## 🔗 Datasets

The datasets are too large for GitHub. You can download them here:

- [Kaggle Malicious URL Dataset](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset)
- [Kaggle Phishing Site URLs Dataset](https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls)
