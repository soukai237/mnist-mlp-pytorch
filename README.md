# MNIST Digit Classification with PyTorch

## Project Overview

This project implements a Multilayer Perceptron (MLP) using PyTorch to classify handwritten digits from the MNIST dataset.

The objective is to understand the fundamental concepts of deep learning, including data preprocessing, neural network architecture, model training, and evaluation.

## Objectives

- Understand the structure of the MNIST dataset.
- Build a neural network using `torch.nn`.
- Implement a training loop with PyTorch.
- Use Cross-Entropy Loss and the Adam optimizer.
- Evaluate the model on unseen test data.
- Visualize predictions and misclassified examples.

## Model Architecture

The MLP consists of the following layers:

- Input layer: 784 features (28 × 28 pixels).
- Hidden layer 1: 256 neurons with ReLU activation.
- Hidden layer 2: 128 neurons with ReLU activation.
- Output layer: 10 neurons representing digits from 0 to 9.

##  Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

##  Project Structure

```text
mnist-mlp-pytorch/
├── notebooks/
│   └── mnist_mlp.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

##  Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/soukai237/mnist-mlp-pytorch.git
cd mnist-mlp-pytorch
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/mnist_mlp.ipynb` and execute the cells in order.

##  Results

Model accuracy and training results will be added after the experiments are completed.

##  Dataset

The project uses the MNIST handwritten digit dataset, consisting of 28 × 28 grayscale images representing digits from 0 to 9.

## Author

Ahmadou Soukairadjou

Student Engineer in Artificial Intelligence and Data