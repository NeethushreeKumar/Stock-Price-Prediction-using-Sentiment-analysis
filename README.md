# Multi-Algorithm Stock Price Prediction Using Sentiment and Emotion Analysis

## Project Overview
This project combines financial and social media data to predict stock prices using a multi-algorithm approach. By integrating sentiment and emotion analysis with machine learning, the model captures the influence of emotions on stock prices for major companies like Google, Amazon, and Apple. This comprehensive framework incorporates Long Short-Term Memory (LSTM), Convolutional Neural Networks (CNN), and Gradient Boosting Machine (GBM) to enhance accuracy in stock price prediction, especially around impactful events such as elections and global crises.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results and Findings](#results-and-findings)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Sentiment and Emotion Analysis**: Integrates emojis and text-based sentiment from Twitter to predict stock prices.
- **Multi-Algorithm Model**: Utilizes LSTM, CNN, Linear Regression, and GBM in an ensemble model for enhanced prediction accuracy.
- **Explainable AI**: Incorporates SHAP to explain the influence of sentiment on model predictions.
- **Event Impact Analysis**: Assesses how events like presidential elections impact investor sentiment and stock prices.

## Technologies Used
- **Python**: Core language for analysis and model building.
- **Scikit-Learn**: Machine learning models and evaluation metrics.
- **TensorFlow/Keras**: Deep learning models (LSTM and CNN).
- **SHAP**: Explainable AI techniques for interpreting model outputs.
- **Twitter API**: For gathering sentiment and emotional cues from tweets.

## Project Structure
```plaintext
├── data/                         # Datasets used for model training and evaluation
├── notebooks/                    # Jupyter notebooks for data exploration and model building
├── models/                       # Saved models and hyperparameters
├── results/                      # Evaluation metrics and results
└── README.md                     # Project overview and instructions


