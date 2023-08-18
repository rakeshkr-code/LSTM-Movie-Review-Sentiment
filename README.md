# Sentiment Analysis using LSTM

## Overview
This repository contains the code for a sentiment analysis model implemented using Long Short-Term Memory (LSTM) networks with PyTorch. The model is trained and tested on a dataset of movie reviews to classify sentiments as positive or negative.

## Dependencies
- numpy
- pandas
- torch
- scikit-learn
- matplotlib
- seaborn

## Model Architecture
The LSTM model takes tokenized text reviews and passes them through an embedding layer followed by an LSTM layer. A fully connected layer is used to produce the final output, and a sigmoid activation function is applied to generate a probability score.

## How to Run
- Clone this repository.
- Navigate to the project directory.
- Install the required dependencies.
- Run the Jupyter Notebook final-model-notebook.ipynb.

## Results
The model's performance, including accuracy, precision, recall, and F1 score, is evaluated. Visualizations such as confusion matrices may also be included in the notebook.