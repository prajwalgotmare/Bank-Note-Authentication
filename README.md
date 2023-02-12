
# Bank Note Authentication

This project aims to classify bank notes as either genuine or fake based on four attributes - Variance, Skewness, Kurtosis, and Entropy. The dataset used for this project is obtained from the UCI Machine Learning Repository and is called "Bank Note Authentication UCI data".

![Bank Note Image](https://www.neuraldesigner.com/images/banknote-authentication.webp)

## Problem Statement

Counterfeit bank notes are a major problem faced by the bank industry. With the advancement of technology, it is becoming increasingly difficult to differentiate between a genuine bank note and a fake one. The goal of this project is to build a machine learning model that can accurately classify bank notes as either genuine or fake.

## Data Overview

The dataset contains 1,372 observations and 5 columns. The first four columns represent the four attributes used to classify the bank notes, and the fifth column represents the class label (genuine or fake).

## Methodology

We will be using several machine learning algorithms to build our models. These algorithms include:

Random Forest

We will be using a 70-30 train-test split for evaluating the performance of the models. The model with the highest accuracy will be selected as the final model.

## Requirements

To run this project, you need to have the following packages installed:

- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Conclusion

In this project, we have attempted to build a machine learning model that can accurately classify bank notes as either genuine or fake. The results of this project will be useful for banks to detect counterfeit notes and ensure the security of their financial transactions.
