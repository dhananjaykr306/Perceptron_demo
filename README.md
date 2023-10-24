# Perceptron_demo
perceptron
A perceptron is a fundamental building block in artificial neural networks and is a type of artificial neuron or node. It was developed by Frank Rosenblatt in 1957. The perceptron is a simple mathematical model inspired by the way biological neurons work in the human brain.

A perceptron takes multiple binary inputs (0 or 1), applies weights to these inputs, sums them up, and then applies an activation function to the result. The output of a perceptron is typically binary, representing either 0 or 1, which can be seen as a decision boundary. The perceptron can be used to perform binary classification, which means it can decide whether an input belongs to one of two classes.

Mathematically, the output of a perceptron can be represented as follows:

Output = 1, if (Weighted Sum of Inputs) + Bias > 0
Output = 0, if (Weighted Sum of Inputs) + Bias <= 0

Here's a breakdown of the terms:
1. Inputs: These are the binary values (0 or 1) that the perceptron takes as input.
2. Weights: Each input is assigned a weight, which represents the importance or strength of that input.
3. Bias: The bias is a constant term added to the weighted sum, which allows the perceptron to shift its decision boundary.

The perceptron is limited in its capabilities because it can only represent linear decision boundaries. However, when you combine multiple perceptrons in layers, you can create more complex models, such as feedforward neural networks. These networks can learn to represent and approximate more intricate and non-linear functions, making them suitable for a wide range of machine learning tasks.

It's important to note that while the basic perceptron was essential in the history of artificial neural networks, modern neural networks often use more advanced and complex activation functions and architectures like the sigmoid, ReLU, or convolutional and recurrent layers to handle a wide range of machine learning and deep learning applications.
