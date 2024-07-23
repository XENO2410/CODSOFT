# Encryptix: Machine Learning Internship Projects

## Overview

This repository contains the projects completed during the Machine Learning internship. The internship required the completion of at least three tasks, each focusing on different machine learning applications. The projects included are:

1. **Movie Genre Classification**
2. **Credit Card Fraud Detection**
3. **Spam SMS Detection**

## Projects

### 1. Movie Genre Classification

#### Objective
Build a machine learning model that can predict the genre of a movie based on its plot summary or other textual information. Techniques such as TF-IDF or word embeddings are utilized with classifiers like Naive Bayes.

#### Workflow
- **Data Collection and Preparation**: Collect and import movie plot summaries and corresponding genres.
- **Text Processing**: Preprocess textual data using tokenization, stop word removal, and stemming or lemmatization. Convert text to numerical features using TF-IDF or word embeddings.
- **Model Building**: Train a Naive Bayes classifier using the processed features.
- **Model Evaluation**: Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.
- **Prediction**: Predict genres for new, unseen movie plot summaries.

### 2. Credit Card Fraud Detection

#### Objective
Build a model to detect fraudulent credit card transactions using a dataset containing transaction information. Experiment with algorithms like Logistic Regression, Decision Trees, and Random Forests to classify transactions as fraudulent or legitimate.

#### Workflow
- **Data Import and Exploration**: Import and explore the credit card transactions dataset.
- **Data Preprocessing**: Clean the dataset by handling missing values and outliers. Split data into training and testing sets.
- **Model Building**: Train models using Logistic Regression, Decision Trees, and Random Forests.
- **Model Evaluation**: Evaluate models using metrics such as accuracy, precision, recall, and F1-score. Perform comparative analysis to identify the best-performing model.
- **Prediction**: Use the best-performing model to predict fraudulent transactions on new data.

### 3. Spam SMS Detection

#### Objective
Create an AI model that can classify SMS messages as spam or legitimate. Use techniques like TF-IDF or word embeddings with classifiers like Logistic Regression to identify spam messages.

#### Workflow
- **Data Collection and Preparation**: Collect and import SMS messages labeled as spam or legitimate.
- **Text Processing**: Preprocess textual data using tokenization, stop word removal, and stemming or lemmatization. Convert text to numerical features using TF-IDF or word embeddings.
- **Model Building**: Train a Logistic Regression model using the processed features.
- **Model Evaluation**: Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.
- **Prediction**: Predict whether new SMS messages are spam or legitimate.

### Conclusion
This repository demonstrates the application of machine learning techniques across different domains, including movie genre classification, credit card fraud detection, and spam SMS detection. By following the outlined workflows, one can build, evaluate, and enhance various classification models in Python.
