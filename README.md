### Weights initialization in neural network

Training the neural network requires specifying an initial value of the weights. A well chosen initialization method helps the learning.

How do you choose the initialization for a new neural network? In this assignment of "Initialization" of the course "Improving Deep Neural Networks" we learn three different techniques to initialize the weights. We will see here that how different initializations lead to different results.

A well chosen initialization can:

. Speed up the convergence of gradient descent.
. Increase the odds of gradient descent converging to a lower training (and generalization) error.

The initialization methods we will experiment with are:

. Zeros initialization
. Random initialization
. He initialization
