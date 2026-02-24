# Simple Neural Network (PyTorch) — Weights, Biases, and Activations

## Project Overview

This repository contains a lightweight, educational neural network built in **PyTorch** to demonstrate how **weights**, **biases**, and **activation functions** combine to produce a model’s output. The notebook walks step-by-step through the forward pass and visualizes intermediate values to build intuition for how neural networks work under the hood.

You can review the notebook here: [Simple-NN.ipynb](https://github.com/qfattah/Simple-Neural_Network/blob/main/Simple-NN.ipynb).

The project integrates:

- Defining a neural network from scratch using `torch.nn.Module`
- Manual weight/bias initialization (for interpretability)
- Forward propagation using **ReLU** activations
- Visualizing activation functions and intermediate transformations
- Plotting final model output across a continuous input range

---

## Business Context

Neural networks are often treated as “black boxes.” This project focuses on interpretability—showing how a simple architecture transforms inputs into outputs using basic building blocks (linear transformations + activations). This is a strong foundation for understanding deeper models used in forecasting, classification, and performance modeling.

---

## Technical Approach

### 1. Import Dependencies

The notebook uses PyTorch for tensor math and model structure, and Matplotlib/Seaborn for visualization.

---

### 2. Define a Simple Neural Network

A custom `nn.Module` is created with explicitly defined scalar parameters (weights and biases). This keeps the model transparent and easy to reason about.

---

### 3. Forward Pass on Sample Inputs

A small set of example inputs is passed through the network to confirm that outputs change as expected and that the forward function is working correctly.

---

### 4. Visualize Activations

The notebook builds intuition by plotting:

- The **top activation function** output across a range of inputs  
- The **bottom activation function** output across the same input range  
- Both activations together for direct comparison

---

### 5. Combine Activations and Produce Final Output

Intermediate activation outputs are combined using the final layer weight(s), and the notebook visualizes:

- Output after applying the last weight  
- Final output curve of the neural network across the input domain

---

## Model Evaluation

This is an interpretability-first notebook rather than a training-focused project. Evaluation is performed through:

- Sanity checks using known input doses
- Visual inspection of activation behavior and output response curves

---

## Key Skills Demonstrated

- PyTorch fundamentals (`torch`, `nn.Module`, tensors)
- Manual parameterization (weights/biases) for interpretability
- Forward propagation mechanics
- Activation functions (ReLU) and their effect on model output
- Visualization of intermediate computations and final predictions

---

## Tools & Libraries

- Python
- PyTorch
- NumPy
- Matplotlib
- Seaborn

---

## Credits

Notebook inspired by *“StatQuest illustrated guide to neural networks”* (credited in the notebook).

---

## Author

Qusai Fattah  
Applied Machine Learning | Analytics | Model Interpretability
