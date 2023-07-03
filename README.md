## MNIST Neural Network from Scratch
This repository contains a Python implementation of a neural network for MNIST digit classification. The neural network is implemented from scratch, without using any deep learning frameworks or libraries. (no Tensorflow/Pytorch, just numpy & math)

## Dataset
The MNIST dataset consists of a large set of handwritten digits from 0 to 9. It is a commonly used benchmark dataset for image classification tasks.

## Dependencies
The implementation requires the following dependencies:

- Python (version 3.6 or higher)
- NumPy (for numerical computations)
- Pandas (for data manipulation and analysis)
- Matplotlib (for visualization)

## Network Architecture
The neural network architecture consists of an input layer, one hidden layer, and an output layer.

The implementation uses the following layers and activation functions:

- Input layer: The input layer receives the pixel values of the MNIST images as input which have 784 nodes/neurons.
- Hidden layers: Fully connected layers with configurable number of nodes and ReLU activation function which have 10 nodes/neurons.
- Output layer: Fully connected layer with softmax activation function which have 10 nodes/neurons.

## Results
The trained neural network achieves an accuracy of around 83% on the MNIST test set.
