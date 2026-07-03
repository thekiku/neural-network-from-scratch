# Neural Network from Scratch using NumPy

A complete implementation of a feedforward neural network built entirely from scratch using NumPy.

The purpose of this project is to understand how modern neural networks work internally by implementing every major component manually instead of relying on high level deep learning frameworks such as TensorFlow or PyTorch. Every layer, activation function, loss function, optimizer, and training step has been implemented from first principles using only NumPy.

The implementation follows the concepts presented throughout *Neural Networks from Scratch in Python* by Harrison Kinsley and Daniel Kukieła, serving as a complete reference implementation while reinforcing the underlying mathematics and programming involved in deep learning.

# Features

* Fully Connected (Dense) Layers
* Forward Propagation
* Backpropagation
* ReLU Activation
* Sigmoid Activation
* Linear Activation
* Softmax Activation
* Categorical Cross-Entropy Loss
* Binary Cross-Entropy Loss
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Combined Softmax and Cross-Entropy Optimization
* L1 Regularization
* L2 Regularization
* Dropout
* Stochastic Gradient Descent (SGD)
* SGD with Momentum
* AdaGrad Optimizer
* RMSProp Optimizer
* Adam Optimizer
* Learning Rate Decay
* Binary Classification
* Multi-Class Classification
* Regression
* Accuracy Calculation
* Mini-Batch Training
* Model Saving
* Model Loading
* Prediction on Unseen Data
* Training and Validation Loops
* Data Visualization

# Dataset

The project primarily uses the spiral dataset introduced throughout the book to demonstrate multi-class classification and neural network training.

### Spiral Dataset Visualization

<img width="568" height="413" alt="image" src="https://github.com/user-attachments/assets/99c5a473-64ea-454d-8cc2-e92021d2b6e7" />


# Tech Stack

* Python
* NumPy
* Matplotlib
* Jupyter Notebook
* NNFS (dataset generation and utility functions)

# Project Structure

```
neural-network-from-scratch/
│
├── .gitignore
├── README.md
├── neural.ipynb
└── requirements.txt
```

---

# Getting Started

Clone the repository.

```bash
git clone https://github.com/thekiku/neural-network-from-scratch
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

---

# Current Status

This repository contains a complete NumPy implementation covering the material presented throughout the book. It serves both as a personal reference and as a demonstration of the fundamental algorithms that power modern deep learning libraries.

---

# Requirements

* Python 3.10+
* NumPy
* Matplotlib
* NNFS

Install all dependencies with:

```bash
pip install -r requirements.txt
```
Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

# License

This project is released under the MIT License.
