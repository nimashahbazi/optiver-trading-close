# Optiver Trading at the Close Analysis with LSTM and ConvNet

This repository contains two machine learning models developed for analyzing Optiver trading at the close on Kaggle [Optiver Trading at the Close Competition Overview](https://www.kaggle.com/competitions/optiver-trading-at-the-close/overview): a Long Short-Term Memory (LSTM) model and a Convolutional Neural Network (ConvNet) model. Both models are designed to predict stock return using raw features without any feature engineering and a small set of imbalance features only.

## LSTM Model

The LSTM model is built using raw features along with target lag. This model emphasizes the temporal sequence of the data, capturing patterns over time without extensive feature engineering.

- **Performance**: The model achieved a score of 5.3508 on the public leaderboard.
- **Features**: Utilizes raw features and target lag.
- **Notebook**: The model's implementation can be found on Kaggle under the username `nimashahbazi`. [Link to Notebook](#)

## ConvNet Model

The ConvNet model, in contrast, incorporates imbalance features only with raw feature

- **Performance**: This model scored 5.3439 on the public leaderboard.
- **Features**: Includes imbalance features.
- **Improvement Suggestion**: By adding more features like global stock mapping, basic feature deviation, or domain-engineered features, the performance could easily reach 5.33X.
- **Notebook**: The ConvNet model's implementation is also available on Kaggle under the username `nimashahbazi`. [Link to Notebook](#)

## Getting Started

These models are publicly available for review and improvement. To access the notebooks and explore the models:

1. Visit the Kaggle platform.
2. Search for the username `nimashahbazi`.
3. Navigate to the respective notebooks for the LSTM and ConvNet models.


