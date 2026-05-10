# Abalone Age Classification

## Overview

This project uses the Abalone dataset to classify abalones into age groups based on physical measurements.

The project focuses on using neural networks for classification and testing how different model settings affect performance.

## Problem

Abalone age is usually estimated by counting shell rings, which is slow and manual. This project explores whether physical measurements can be used to predict age groups instead.

## Methods

The analysis included:
- Loading and preparing the dataset
- Creating age groups from the rings variable
- One-hot encoding categorical variables
- Exploratory data analysis
- Training neural network models
- Comparing different hidden layer sizes, learning rates, and optimisers

The final model used a neural network built with TensorFlow/Keras.

## Main Findings

The model performed better on the age groups with more examples and struggled more with the underrepresented classes. This showed the impact of class imbalance on classification performance.

The project also showed that tuning the network structure and optimiser affected model performance.

## Files

- `abalone_nn.ipynb` — notebook containing the neural network experiments
- `abalone_classification_report.pdf` — final written report

## Skills Shown

- Neural networks
- Classification
- TensorFlow/Keras
- Hyperparameter testing
- Confusion matrix and ROC-AUC evaluation
