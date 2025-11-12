# Handwritten Digit Recognition (Kaggle)

This repository contains the implementation of a machine learning model for the Kaggle **Digit Recognizer** competition. The goal of the competition is to predict handwritten digits (0-9) from images.

## Overview
The dataset consists of grayscale images of hand-drawn digits. The model predicts the digit based on the image pixels. The performance is evaluated based on the accuracy of the predictions.

## Kaggle Competition
- **Competition:** [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer)
- **Score:** 0.9739 (Test Set Accuracy)

## Model Architecture
The model is a fully connected neural network with the following layers:
- Input layer: Flattened 28x28 images (784 pixels)
- Dense layers with ReLU activation and HeNormal initializer:
  - 256 units
  - 128 units
  - 64 units
  - 32 units
- Batch Normalization
- Dropout regularization to reduce overfitting
- Output layer: Softmax activation for multi-class classification
