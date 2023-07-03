## MNIST Neural Network from Scratch
This repository contains a Python implementation of a neural network for MNIST digit classification. The neural network is implemented from scratch, without using any deep learning frameworks or libraries.

## Dataset
The MNIST dataset consists of a large set of handwritten digits from 0 to 9. It is a commonly used benchmark dataset for image classification tasks.

## Dependencies
The implementation requires the following dependencies:

Python (version 3.6 or higher)
NumPy (for numerical computations)
Matplotlib (for visualization)

## Network Architecture
The neural network architecture consists of an input layer, one or more hidden layers, and an output layer. The number of nodes in each layer and the activation functions can be configured in the config.py file.

The implementation uses the following layers and activation functions:

Input layer: The input layer receives the pixel values of the MNIST images as input.
Hidden layers: Fully connected layers with configurable number of nodes and ReLU activation function.
Output layer: Fully connected layer with softmax activation function.


## Results
The trained neural network achieves an accuracy of around 95% on the MNIST test set after training for a specified number of epochs.
