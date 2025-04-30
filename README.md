# feed-forward-neural-networks
This project demonstrates how to build and train a Feedforward Neural Network (FNN) for natural language modeling using PyTorch. The model learns to predict the next word in a sequence based on the context, which is a foundational task in Natural Language Processing (NLP).

This notebook is part of the IBM AI Engineering Professional Certificate.

# Overview

The goal of this project is to develop a feedforward neural network that can learn from text data and make predictions about word sequences. It covers:

Tokenization and indexing

Word embeddings

N-gram context-target pair creation

Multi-class classification for next-word prediction

# Objectives

Convert raw text into numerical format using tokenization and indexing

Use embedding layers to transform tokens into dense vectors

Generate context-target pairs (n-grams) for training

Design and train a feedforward neural network to predict the next word

Evaluate the model’s performance on word prediction tasks

# Model Workflow

1. Text Preprocessing

      Tokenize the input sentence

      Index tokens

      Generate n-grams (context-target pairs)

2. Embedding Layer

      Learn dense vector representations of words

3. Neural Network Architecture

      Input: context word embeddings

      Hidden layer(s): fully connected

      Output: softmax layer to predict the next word

4. Training Loop

      Forward pass

      Loss computation

      Backpropagation and optimization

# Training

Loss Function: CrossEntropyLoss

Optimizer: SGD or Adam

Metrics: Accuracy of next-word prediction

# Technologies Used

Python

PyTorch

NumPy

Jupyter Notebook

License
This project is part of the IBM Skills Network and is intended for educational purposes only.
