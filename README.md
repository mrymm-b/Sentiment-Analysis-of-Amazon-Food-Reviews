# 🍽️ Sentiment Analysis of Amazon Food Reviews

![Python](https://img.shields.io/badge/Python-3.11-blue)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-orange)
![Transformers](https://img.shields.io/badge/Transformers-HuggingFace-yellow)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-green)

## 📌 Project Overview

This project focuses on sentiment analysis of Amazon food product reviews using Natural Language Processing (NLP) techniques and transformer-based models.

The goal is to classify customer reviews into **Positive** and **Negative** sentiments, compare the performance of multiple pre-trained models, and identify the most effective approach for sentiment classification.

---

## 📂 Dataset

The project uses the Amazon Fine Food Reviews dataset from Kaggle.

**Dataset Source:**
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

The dataset contains customer reviews, ratings, product information, and helpfulness scores collected from Amazon users.

---

## 🎯 Objectives

* Analyze customer review sentiment.
* Preprocess and clean textual data.
* Address class imbalance within the dataset.
* Extract meaningful textual features.
* Compare multiple sentiment classification models.
* Identify the best-performing model.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Sentiment labeling based on review scores.
* Text cleaning and normalization.
* Converting text to lowercase.
* Removing punctuation and numbers.
* Removing stop words.
* Creating a cleaned text dataset for modeling.

---

## ⚖️ Handling Class Imbalance

The dataset showed a significant imbalance between positive and negative reviews.

To improve model performance and reduce bias, **oversampling** was applied to the minority class before training and evaluation.

---

## 📊 Exploratory Data Analysis (EDA)

Several analyses were performed to better understand the dataset:

* Review score distribution.
* Sentiment distribution.
* Class imbalance analysis.
* TF-IDF feature analysis.
* Bag of Words analysis.
* Word Cloud visualization.

---

## 🤖 Models Evaluated

### Model 1

**Twitter RoBERTa**

Pre-trained transformer model used for sentiment classification.

### Model 2

**DistilBERT Base Uncased Fine-Tuned SST-2**

Lightweight transformer model optimized for sentiment analysis.

### Model 3

**SieBERT**

State-of-the-art sentiment classification model designed for English-language sentiment analysis.

---

## 📈 Model Comparison

The three models were evaluated and compared using standard classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score

### Best Performing Model

🏆 **SieBERT** achieved the strongest overall performance and delivered the most reliable sentiment predictions across both sentiment classes.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Hugging Face Transformers
* Jupyter Notebook

---

## 💡 Business Value

The developed sentiment analysis system can help businesses:

* Understand customer satisfaction.
* Detect recurring customer concerns.
* Monitor product perception.
* Support data-driven decision making.
* Improve products and customer experience.

---

## 📖 Conclusion

This project demonstrates how modern NLP techniques and transformer-based models can be used to analyze customer opinions at scale. By comparing multiple pre-trained models, the study identified SieBERT as the most effective solution for sentiment classification on Amazon food reviews.
