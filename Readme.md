# Fake News Detection using SVM

## Introduction

This project focuses on detecting fake news articles using a Support Vector Machine (SVM) classifier. The goal is to contribute to the identification and mitigation of misinformation in the media.

## Dataset

We utilize the "fake_or_real_news.csv" dataset, which contains news articles labeled as "FAKE" or "REAL." The dataset includes columns such as "id," "title," "text," and "label."

## Steps

1. **Data Preprocessing**: We prepare the data for training by adding a "fake" column to classify news articles as fake (1) or real (0). The data is then split into training and testing sets.

2. **Feature Extraction**: Text data is converted into numerical features using the TF-IDF vectorizer, making it suitable for machine learning.

3. **Model Training**: We employ a Linear Support Vector Machine (LinearSVC) classifier to train the model, which is effective for binary classification tasks like fake news detection.

4. **Model Evaluation**: The model's performance is evaluated on the test data, and the accuracy of the model is calculated.

## Results

The trained SVM model achieved an accuracy of approximately 94% on the test data, demonstrating its effectiveness in detecting fake news articles.

## Conclusion

This project serves as a valuable tool in the fight against misinformation by providing a reliable means of identifying fake news articles. Future improvements may focus on enhancing accuracy and robustness.

## Prerequisites

Before running the code, make sure you have the following libraries installed:

- numpy
- pandas
- scikit-learn

You can install them using pip:

```bash
pip install numpy pandas scikit-learn
