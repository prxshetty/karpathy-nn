# Micrograd Implementation

This project contains all the resources that are inspired by Andrej Karpathy's "Neural Networks: Zero to Hero" YouTube series. It's a lightweight, educational implementation of backpropagation and neural networks from scratch.
Current python file implements a small autograd engine and neural network library, 
## Features

- Custom `Value` class for automatic differentiation
- Basic mathematical operations (+, -, *, /, pow, exp, tanh)
- Neuron class for building simple neural networks
- Visualization of computational graphs using Graphviz
- Comparison with PyTorch implementation

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- PyTorch (for comparison)
- Graphviz (for visualization)

## Components

### Value Class

The `Value` class is the core of this implementation, providing automatic differentiation capabilities. It supports basic mathematical operations and allows for the construction of computational graphs.

### Neuron Class

The `Neuron` class represents a single neuron in a neural network. It can be used to build more complex network architectures.

## Visualization

The project includes functionality to visualize the computational graph using Graphviz. This helps in understanding the structure of the computations and the flow of gradients during backpropagation.

## PyTorch Comparison

A section of the code compares the custom implementation with PyTorch, demonstrating the similarities and differences between the two approaches.

## Acknowledgements

This implementation is based on Andrej Karpathy's "Neural Networks: Zero to Hero" YouTube series. It's intended for educational purposes to understand the fundamentals of backpropagation and neural networks.

## License

[MIT License](LICENSE)
