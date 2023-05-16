# Neural-Galerkin-for-1-D-Heat-Equation
Implement of a neural Galerkin method to solve a 1-dimensional heat equation.

## Network construction
We are here using a 3*20 fully-connected neural network to train an initial value
Mathmatically, we project the initial value function onto the space spanned by the neural network.

## Key operations
Guassian Integral approximation serves a reduction in opretaion time to approximate the integrals to generate the coefficient matrixs.

## Time evolution
We implemented several explict methods to move forward, including Forward Euler, RK2 and RK4

