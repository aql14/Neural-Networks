# Neural Network Regression with TensorFlow and PyTorch: Celsius to Fahrenheit Conversion

This repository presents a comparative implementation of simple feedforward neural networks to solve a basic regression task: converting temperatures from Celsius to Fahrenheit. The goal is to provide a clear and concise demonstration of supervised learning using both **TensorFlow (Keras)** and **PyTorch**.

## Overview

The task involves training a neural network on synthetically generated data based on the well-known linear relationship:

\[
\text{Fahrenheit} = \text{Celsius} \times \frac{9}{5} + 32
\]

While the underlying function is simple and deterministic, this example provides a controlled environment for understanding fundamental concepts in neural network regression, including data normalization, loss functions, optimization, and model evaluation.

## Contents

- Synthetic data generation and preprocessing
- Model implementation and training using:
  - [x] TensorFlow (Keras API)
  - [x] PyTorch
- Evaluation on held-out test data. Will also use two-layer cross-validation for a smaller data set.
- Visualization of predictions and training performance
- Well-organized code

