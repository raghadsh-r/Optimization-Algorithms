# Optimization Algorithms: Gradient Descent from Scratch

This repository contains a C++ implementation of the **Gradient Descent** algorithm, a fundamental optimization technique used in Machine Learning to minimize cost functions.

## 📌 Concept
Gradient Descent is an iterative optimization algorithm used to find the minimum of a function. In Machine Learning, we use it to update the parameters (weights and biases) of our model to minimize the error (Loss Function).

### The Math Behind It
The update rule for a parameter $x$ is:
$$x_{new} = x_{old} - \alpha \cdot f'(x_{old})$$

Where:
- $\alpha$ (Alpha) is the **Learning Rate**.
- $f'(x_{old})$ is the **Derivative** (Gradient) of the function at the current point.

## 🛠️ Implementation Details
In this specific example, I implemented Gradient Descent to find the minimum of the function:
$$f(x) = x^2$$
Whose derivative is:
$$f'(x) = 2x$$

The code demonstrates how the value of $x$ converges towards zero (the global minimum) over several iterations.

## 🚀 How to Run
1. Clone the repository.
2. Compile the `main.cpp` using any C++ compiler (e.g., g++).
3. Provide the initial value $x_0$ and the learning rate $\alpha$ as input.

## 📈 Learning Journey
This project is part of my academic journey in **Artificial Intelligence** at Jordan University of Science and Technology (JUST). It serves as a foundational step toward understanding complex neural network optimization.
