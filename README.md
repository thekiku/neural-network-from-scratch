# Neural Network from Scratch using NumPy

A complete implementation of a feedforward neural network built entirely from scratch using NumPy.

The purpose of this project is to understand how modern neural networks work internally by implementing every major component manually instead of relying on high level deep learning frameworks such as TensorFlow or PyTorch. Every layer, activation function, loss function, optimizer, and training step has been implemented from first principles using only NumPy.

The implementation follows the concepts presented throughout *Neural Networks from Scratch in Python* by Harrison Kinsley and Daniel Kukieła, serving as a complete reference implementation while reinforcing the underlying mathematics and programming involved in deep learning.

---

# Features

Fully Connected (Dense) Layers

Forward Propagation

Backpropagation

ReLU Activation

Sigmoid Activation

Linear Activation

Softmax Activation

Categorical Cross-Entropy Loss

Binary Cross-Entropy Loss

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Combined Softmax and Cross-Entropy Optimization

L1 Regularization

L2 Regularization

Dropout

Stochastic Gradient Descent (SGD)

SGD with Momentum

AdaGrad Optimizer

RMSProp Optimizer

Adam Optimizer

Learning Rate Decay

Binary Classification

Multi-Class Classification

Regression

Accuracy Calculation

Mini-Batch Training

Model Saving

Model Loading

Prediction on Unseen Data

Training and Validation Loops

Data Visualization

---

# Dataset

The project primarily uses the spiral dataset introduced throughout the book to demonstrate multi-class classification and neural network training.

### Spiral Dataset Visualization

> Replace the placeholder below with a screenshot of the generated spiral dataset.

<p align="center">
  <img src="images/spiral_dataset.png" width="600">
</p>

---

# Technologies Used

Python

NumPy

Matplotlib

NNFS

Jupyter Notebook

---

# Project Structure

```
neural-network-from-scratch/
│
├── neural_network_from_scratch.ipynb
├── README.md
├── requirements.txt
└── images/
    └── spiral_dataset.png
```

---

# Getting Started

Clone the repository.

```bash
git clone https://github.com/yourusername/neural-network-from-scratch.git
```

Move into the project directory.

```bash
cd neural-network-from-scratch
```

Install the required dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

---

# What This Project Demonstrates

This project walks through the complete lifecycle of building a neural network without relying on any deep learning framework.

Every major component is implemented manually, including layer initialization, forward propagation, gradient computation through backpropagation, parameter updates using multiple optimization algorithms, regularization techniques, dropout, regression models, binary classification, multi-class classification, model serialization, and prediction.

Rather than treating neural networks as black boxes, this implementation exposes each mathematical operation involved in training and inference, providing a deeper understanding of how modern deep learning systems function internally.

---

# Learning Reference

This implementation closely follows the concepts presented in:

**Neural Networks from Scratch in Python**

**Authors:** Harrison Kinsley and Daniel Kukieła

The objective was not simply to reproduce the examples, but to implement and understand every major building block involved in constructing and training neural networks from first principles using NumPy.

---

# Current Status

This repository contains a complete NumPy implementation covering the material presented throughout the book. It serves both as a personal reference and as a demonstration of the fundamental algorithms that power modern deep learning libraries.

---

# Requirements

Python 3.10+

NumPy

Matplotlib

NNFS

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

# License

This project is released under the MIT License.
