## Gradient Descent:<br>

-> It is a key optimization algorithm used to minimize the loss function in neural network during training.<br>
-> The goal is to adjust the weight and biases in the network to minimize the difference between predicted output and the actual target values (i.e., minimize the loss)<br>

### How Gradient Descent works?
1) Forward Bias:<br>
    - Input data is passed through the neural network.
    - The network produces an output based on its current weight and biases.

2) Compute loss:<br>
    - The difference between the predicted output and the actual value is computred using a loss function (e.g., MSE or Cross-Entropy loss)
    - This indicates how far predictions are from true values.

3) Back Propagation:<br>
    - The error loss is propagated backward through the network to calculate the gradients.
    - The gradients is the partial derivative of loss with respect to each weight in the network. This tells us how much each weight in the network contributed to the error.
  
4) Update Weights:<br>
    - The weights are adjusted in the direction that reduces the error. This is done by subtracting a small portion of the gradients from current weight.

5) Repeat:<br>
    - The above steps are repeated for several iterations until the loss converges to a minimum or stops decreasing significantly.
  
<br>

## Types of Gradient Descent:
1) Batch Gradient Descent:<br>
    a) Compute the gradient of the loss function using the entrie dataset.<br>
    b) It provides a stable but computationally expensive update.<br>

2) Stochastic Gradient Descent:<br>
    a) Computes the gradient and updates the weights using only a single data point.<br>
    b) It is much faster but introduces more variance in the updates, which may result in noisy or fluctuation updates.<br>






