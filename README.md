# Spam Classifier

A machine learning-based spam classifier that predicts whether a given message is spam or not-spam. This project is built using Python, and the user interface is created with Streamlit for ease of use and deployment.

## Live Demo

🚀 **Check out the live application on Streamlit**: [Spam Classifier](https://spamclassifier-project.streamlit.app/)

## Project Overview

This project is a simple yet effective spam classifier that uses the Naive Bayes algorithm for classification. It can classify individual messages. The Interactive Python Notebook also provides model performance evaluation tools, such as confusion matrix visualization and classification reports.

## Features

- **Single Message Prediction**: Classify a single message as spam or not-spam.
- **Model Performance Evaluation**: Evaluate the model's performance on a test dataset using accuracy, confusion matrix, and classification report.

## Project Structure

```plaintext
spam_classifier/
├── app.py                    # Streamlit app script
├── model.pkl                 # Trained model
├── vectorizer.pkl            # Vectorizer for text preprocessing
├── spam_classifier.ipynb     # Script for training the model
├── spam.csv                  # Dataset used for training
├── requirements.txt          # Dependencies for the project
└── README.md                 # Project documentation
