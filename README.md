# Sentiment Analysis of Medium App Reviews

## 📌 Overview
This project performs sentiment analysis on 62,633 real user 
reviews of the Medium application collected from the Google 
Play Store. The goal is to automatically classify each review 
as either positive or negative sentiment using Machine Learning 
techniques, helping businesses understand user feedback at scale.

## 🎯 Problem Statement
Manually reading thousands of app reviews is time-consuming 
and inconsistent. This project automates the classification 
process using NLP and ML to extract meaningful insights from 
unstructured text data.

## 🔄 Methodology
1. **Data Collection** — 62,633 reviews scraped from 
   Google Play Store
2. **Data Cleaning** — Removed redundant attributes, 
   handled neutral/mixed sentiments, applied down-sampling 
   to fix class imbalance
3. **Text Preprocessing** — Tokenization, English stopword 
   removal, Porter stemming, TF-IDF transformation
4. **Modelling** — Compared 4 ML models:
   - Naive Bayes
   - Support Vector Machine (SVM)
   - Logistic Regression
   - Random Forest
5. **Evaluation** — Split validation (80:20, 70:30) and 
   k-fold cross-validation
6. **Deployment** — Naive Bayes selected as final model

## 📊 Key Results
- ✅ Best accuracy: **85.61%** using Naive Bayes
- Evaluated using Accuracy, Precision, Recall, and F1-Score
- Naive Bayes outperformed SVM, Logistic Regression, 
  and Random Forest on this dataset

## 🛠️ Tools & Technologies
- RapidMiner (modelling & pipeline)
- Microsoft Excel (data preparation)
- Techniques: NLP, TF-IDF, Porter Stemming, 
  Tokenization, Down-sampling

## 👤 Author
Muhammad Syakirin Bin Shamsunrizan
muhammadsyakirin53@gmail.com
