# Multi-Layered-Fluid-Neural-Network
Multi-Layered Fluid Neural Network

This code implements a fluid lattice neural network (FLNN) and demonstrates its usage with a simple example. The FLNN is a type of neural network that is inspired by fluid dynamics and uses a lattice structure for its neurons.

The FluidLatticeNeuralNetwork class represents the FLNN. It takes the layer sizes and learning rate as input parameters in its constructor. The FLNN supports multiple hidden layers with customizable sizes. The initializeWeights function initializes the network's weights randomly.

The predict function takes an input vector and returns the output vector computed by propagating the input through the network. It iterates through the layers and computes the activations of each neuron based on the weighted sum of inputs from the previous layer.

The train function trains the FLNN using backpropagation. It takes input-target pairs, the number of training epochs, and performs gradient descent to adjust the network's weights. It calculates the error between the predicted output and the target output, propagates the error backward through the layers, and updates the weights accordingly.

The example in the main function demonstrates the usage of the FLNN. It creates a FLNN with an input layer of 2 neurons, a hidden layer of 4 neurons, and an output layer of 2 neurons. The FLNN is trained to learn the XOR logic gate. The train function is called with input-target pairs and the number of epochs. After training, the FLNN is tested with the predict function to obtain the outputs for the input examples.

In summary, this code implements a FLNN and shows how to train and use it for a simple XOR logic gate problem.
