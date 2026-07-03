# Neural Network from Scratch using NumPy

This project is my implementation of a feedforward neural network built completely from scratch using only NumPy. The goal was to understand what actually happens behind high level deep learning libraries instead of treating them like black boxes.

Rather than using TensorFlow or PyTorch to train a model, every component was implemented manually, starting from dense layers and activation functions to loss calculation and forward propagation. Building each piece individually made it much easier to understand how information flows through a neural network.

## What this project covers

Dense (Fully Connected) Layers

ReLU Activation

Softmax Activation

Categorical Cross Entropy Loss

Forward Propagation

Prediction using Class Probabilities

Visualization of the Spiral Dataset

## Technologies Used

Python

NumPy

Matplotlib

NNFS (for the dataset)

## Project Structure

```
neural-network-from-scratch/
│
├── neuralREAL.ipynb
├── README.md
└── requirements.txt
```

## Running the Notebook

Clone the repository.

```bash
git clone https://github.com/yourusername/neural-network-from-scratch.git
```

Move into the project directory.

```bash
cd neural-network-from-scratch
```

Install the required packages.

```bash
pip install -r requirements.txt
```

Open the notebook.

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

## Why I Built This

I wanted to understand how neural networks actually work internally rather than only knowing how to use existing frameworks. Implementing everything manually helped me understand matrix multiplication, activation functions, probability distributions, and how predictions are generated before moving on to backpropagation and training.

## License

This project is open source and available under the MIT License.
