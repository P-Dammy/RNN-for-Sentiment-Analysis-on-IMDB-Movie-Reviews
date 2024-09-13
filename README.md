# RNN for Sentiment Analysis on IMDB Movie Reviews

This project implements a Recurrent Neural Network (RNN) using Long Short-Term Memory (LSTM) layers to perform sentiment analysis on the IMDB dataset. The dataset consists of movie reviews that are classified as positive or negative. The RNN captures long-term dependencies in the text to improve classification performance.

# Introduction

This project builds a Recurrent Neural Network (RNN) with LSTM layers to perform binary sentiment analysis on movie reviews from the IMDB dataset. The task is to classify the sentiment of a review as either positive or negative. We employ an embedding layer for converting word indices into dense vectors and use LSTM layers to capture the sequence of words in the reviews. A function for encoding and predicting the class of a newly written review was included.

# Dataset Description

The dataset used is the IMDB Movie Reviews dataset, containing 50,000 reviews. It is divided into:

**25,000 training samples**

**25,000 test samples**

Each review is a sequence of integers representing the indices of words in a dictionary of the 10,000 most common words.

# Model Architecture

The RNN model consists of an embedding layer, an LSTM layer, and a fully connected output layer.

**Embedding Layer: Turns word indices into dense vectors of fixed size (128).**

**LSTM Layer: A single LSTM layer with 64 units to capture long-term dependencies.**

**Dense Layer: A fully connected layer with a sigmoid activation for binary classification.**

# Results

**Training Accuracy: 0.90**

**Validation Accuracy: 0.87**

**Test Accuracy: ~0.86**
