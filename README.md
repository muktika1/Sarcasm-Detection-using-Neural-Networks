# Sarcasm-Detection-using-Neural-Networks

## Overview

This project implements a sarcasm detection system using deep learning techniques. The model combines Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks to classify news headlines as sarcastic or not sarcastic.

## Features

- **Data Cleaning**: The dataset is cleaned by removing stopwords, punctuation, and irrelevant text.
- **Text Visualization**: Word clouds are used to visualize the most frequent words in sarcastic and non-sarcastic headlines.
- **Tokenization & Padding**: Text data is tokenized and padded to prepare it for model input.
- **Model Building**: The model architecture includes multiple CNN layers and Bidirectional LSTM layers for capturing both local and sequential features.
- **Evaluation**: The model is evaluated using accuracy, confusion matrix, and classification report.
- **User Interaction**: A command-line interface allows users to input headlines and receive sarcasm predictions.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- TensorFlow
- Scikit-learn

## Installation

```bash
pip install pandas numpy matplotlib seaborn nltk tensorflow scikit-learn
