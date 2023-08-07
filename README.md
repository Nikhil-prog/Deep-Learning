# Deep-Learning


## ⭐️ Introduction
Deep learning is a subfield of machine learning that focuses on training artificial neural networks to perform tasks by automatically learning and improving from experience. It is inspired by the structure and function of the human brain, where neurons are interconnected to process information. <br><br> *I have provided here the implementation of Neural Network from scratch. I hope you like it :)*

## 👨‍💻 What is a Neural Network?
A neural network is a computational model inspired by the structure and functioning of biological neural networks, such as the human brain. It's a mathematical framework used in machine learning to solve various tasks, including pattern recognition, classification, regression, and more. Neural networks are particularly prominent in the field of deep learning. At its core, a neural network is composed of interconnected units called neurons, organized into layers. Each neuron receives inputs, processes them using a weighted sum, and then applies an activation function to produce an output. The connections between neurons are associated with weights, which determine the strength of the signal being passed along the network. <br><br> Here's a simplified breakdown of the components of a neural network:
- **Input Layer:** This layer receives the raw data or features that are used as inputs to the network. Each input is connected to every neuron in the next layer.
- **Hidden Layers:** These layers come between the input and output layers and perform intermediate computations. They extract increasingly abstract features from the inputs as information flows through the network. Deep neural networks have multiple hidden layers, which is why they're referred to as "deep."
- **Output Layer:** This layer produces the final output of the network's computation. The number of neurons in the output layer depends on the type of task the network is designed for (e.g., binary classification, multi-class classification, regression, etc.).
- **Weights and Biases:** The connections between neurons are represented by weights, which determine the strength of the signal transmitted from one neuron to another. Each neuron also has a bias term, which helps control the neuron's activation.
- **Activation Functions:** Activation functions introduce non-linearity to the network, enabling it to learn complex relationships in the data. Common activation functions include ReLU (Rectified Linear Activation), sigmoid, and tanh
- **Feedforward and Backpropagation:** In the feedforward process, data flows from the input layer through the hidden layers to the output layer, generating a prediction. During training, backpropagation is used to adjust the weights based on the difference between the predicted output and the actual target. This process iterates until the network's performance improves.

## 👇 Prerequisite Libraries
You must have basic knowledge of the followings libraries and have installed on your system
- [Python](https://www.python.org/doc/)
- [Numpy](https://numpy.org/doc/stable/)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [Pickle](https://docs.python.org/3/library/pickle.html)

