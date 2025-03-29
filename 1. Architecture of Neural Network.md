# Architecture of Neural Networks
-> It refers to the structure or design of the network, which defines how the neurons (or nodes) are organised, connected, and how data flows through the network.

## 1) Input Layer:
Resposible for receiving the initialdata features that are fed into the neural network.

## 2) Hidden Layers: 
Intermediate layers between the input & output layers. They perform complex computation and transformation on the input data. A neural network can have numerous hidden layer consisting of numerous neurons or nodes.

## 3) Neurons (Nodes): 
They receive input signals and perform computations to produce and output. Neurons in the hidden and output layers utilize activation functions to introduce non-linearities into the network, allowing it to learn complex patterns.

## 4) Weights & Biases: 
Weights & Biases are adjustable parameters with the connections between neurons. Each connection has a weight, which determines the strength or importance of input signal. Biases, on the other hadn, provide an additional tunable parameter that allows neurons to adjust their activation threshold.

## 5) Activation function: 
Activation function are threshold valuses that introduce non-linearites into the neural network, enabling it to comprehend complex relationships between inputs & outputs. Common activation functions include sigmoid, tanh, Relu a (Rectified Linear Unit) & Softmax.

## 6) Output Layer: 
It generates the final predictions or output of neural network.

## 7) Loss function: 
The loss function measures the discrepancy between the predicted output of the neural network and true value.

## 8) Back Propagation: 
It is a learning algorithm used to train a neural network. It involves propagating the error backward through the network and adjusting the weights & biases iteratively to mimimize the loss function.

## 9) Optimization Algorithm: 
Optimization algorithms, such as gradient descent, are employed to update weigths and biases during training. These algorithms determine the direction and magnitude of weigths adjustments based on the gradient of loss function concerning the network parameters.

<br>
<br>

## Different types of Activation Funtion:
### -> **sigmoid:** Useful for binary classificerin task, but can suffer from vanishing gradients
### -> **ReLU:** Default choice in many architectures due to its simplicity and efficiency. It is a piece wise linear function that outputs the input directlys if it is positive, otherwise it outputs zero.
### -> **Tanh:** Similar to sigmoid but output values between -1 & 1.
### -> **Softmax:** Often used in the output layer for multi-class classification problem.

<br>
<br>

## Two types types of Loss function:
### 1) Mear Squared Error: for regression task
### 2) Cross-entropy loss: For classification task
