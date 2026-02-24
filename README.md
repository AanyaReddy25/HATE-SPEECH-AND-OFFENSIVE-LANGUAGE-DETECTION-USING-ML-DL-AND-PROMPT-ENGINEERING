## HATE SPEECH AND OFFENSIVE LANGUAGE DETECTION
## Introduction

This project focuses on classifying tweets into three categories: Hate Speech, Offensive Language, and Neither. With the growth of social media, automatic detection of harmful content is important. The project uses machine learning, deep learning, and prompt engineering techniques to perform and compare text classification.

## Objective

* To classify tweets into three classes

* To build machine learning models using TF-IDF features

* To build deep learning models (LSTM, BiLSTM, CNN)

* To compare model performance using accuracy

* To apply prompt engineering methods like zero-shot, one-shot, few-shot, and chain-of-thought

## Data Preprocessing

The dataset is loaded from a CSV file and only the tweet and class columns are used. Missing values are removed. For machine learning models, TF-IDF vectorization is applied. For deep learning models, text is tokenized, converted into sequences, and padded. The data is then split into training and testing sets.

## Model Building

Three machine learning models (Logistic Regression, Naive Bayes, Random Forest) and three deep learning models (LSTM, BiLSTM, CNN) are trained for classification. All models are evaluated on test data. A results table is created to compare their accuracies.

## Prompt Engineering

A large language model is used with four prompting strategies: zero-shot, one-shot, few-shot, and chain-of-thought. Sample tweets are tested to observe how different prompts affect the classification responses.

## Conclusion

The project shows that deep learning models perform well for tweet classification, while traditional models provide useful baselines. Prompt engineering also proves effective for classification without training. This work demonstrates multiple approaches to solving text classification problems.
