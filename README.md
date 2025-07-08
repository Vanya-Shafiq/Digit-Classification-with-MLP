# MNIST Digit Classification with MLP 

This project implements a **Multilayer Perceptron (MLP)** from scratch to classify handwritten digits using the **MNIST dataset**. The goal is to better understand the internals of neural networks by manually implementing key components like forward propagation, backpropagation, and optimization using only NumPy.

---

## Problem Statement

Train a Multilayer Perceptron (MLP) to classify grayscale images of handwritten digits (0–9) using the MNIST dataset. 

---

##  Objectives

- Load and preprocess the MNIST dataset.
- Flatten each 28x28 image into a 784-length vector.
- Build a neural network with:
  - **2 to 4 hidden layers**
  - **ReLU activation** in hidden layers
  - **Softmax output** layer for 10-class classification
- Use **cross-entropy loss** and **Adam optimizer**.
- Train the model and evaluate performance.
- Visualize:
  - Accuracy vs. Epochs
  - Confusion Matrix
  - Sample Predictions

---

## Dataset

- **Name**: MNIST (Modified National Institute of Standards and Technology)
- **Type**: 28x28 grayscale images of handwritten digits
- **Classes**: 10 (digits 0 to 9)

