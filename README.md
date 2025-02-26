# Feed Forward Neural Network

This repository contains a simple Feed Forward Neural Network implemented in Python within a Jupyter Notebook. It takes 2 inputs, processes them through 2 hidden neurons, and produces 1 output using the `tanh` activation function. The weights are randomly chosen each run from the range [-0.5, 0.5], with biases fixed at 0.5 for the hidden layer and 0.7 for the output layer. Built from scratch using only Python's `math` and `random` modules, it demonstrates basic forward propagation.

## Features
- 2 input neurons, 2 hidden neurons, 1 output neuron
- `tanh` activation function implemented manually
- Random weights initialized between -0.5 and 0.5
- Fixed biases: 0.5 (hidden), 0.7 (output)
- No external libraries beyond `math` and `random`

## Usage
1. Open the `feedforward_nn.ipynb` file in Jupyter Notebook.
2. Run all cells to see the network in action with example inputs (0.1, 0.2).
3. Outputs include the randomly generated weights, biases, inputs, and the network's result.

## Requirements
- Python 3.x
- Jupyter Notebook

## Purpose
Created as an educational example for understanding neural network forward propagation, suitable for assignments or learning purposes.
