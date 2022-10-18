  All the actions are shown step by step from one to the next
  
# Week 3
   [Week3](https://github.com/ImAli0/ImAli/blob/main/week3/Intro.ipynb):
### code 3-1
-Init Code for XORLearning Example

-Now that the ground truth has been altered for the training example to range from 0.0 to 1.0 because, as previously stated, we have selected the logistic sigmoid function as our activation function for the output neuron, unlike the perceptron, which had an output of -1.0 our neuron's output does not go to -1.0.

### code 3-2
 -Variables Needed to Track State of Neurons
 
 -Declare variables to hold the state of our three neurons
 
 -These are all the state variables that we need for each neuron for both the forward pass and the backward pass: weights (n_w), output (n_y),3 and error term (n_error). We arbitrarily initialize the input weights to random numbers between -1.0 and 1.0, and we set the bias weights to 0.0.
 
### code 3-3
-Helper Functions for Backpropagation
 
# Week 5
   [Week5](https://github.com/ImAli0/ImAli/blob/main/week5/week5.ipynb):
       
• Variables: tensors initialized in a session:
– trainable, defined as tf.Variable()
• Constants: fixed value tensors
– not trainable, defined as tf.constant()
• Placeholders: tensors whose values are unknown during the
graph construction but passed as input during a session:
tf.placeholder()

Tensorboard Visualization!!!

# Week 6
   [Week6_1](https://github.com/ImAli0/ImAli/blob/main/week6/AI__course__week6_1.ipynb):
   
-installing the 1.15.5 version of the TensorFlow

-Invoking the dependencies: importing the libraries

-Defining the parameters

-Creating the dataset of linear regression

-Plotting the graph: The blue dots are noisy observations corresponding to the noisy dataset,
and the green line corresponds to the noise-free dataset.

-Defining the model, defininh the optimizer, implementing the cost function and initializing the variables.

-Starting the TensorFlow session
   
### Visualization of Linear Regression parameters using TensorFlow:
-Defining the TensorFlow session again

-Importing the MNIST dataset and store it in the variable

-Determining how many images are for training, testing and validation

-Determining the network parameters of the Neural Network

-Defining the hyperparameters

-Building the network as a TensorFlow graph

-Creating a NN model: Defining the operations that will manipulate tensors

-Executing the computational graph

   [Week 6_2](https://github.com/ImAli0/ImAli/blob/main/week6/week6_session2.ipynb):
    
• Linear Regression using TensorFlow
• Visualization of Linear Regression parameters using
TensorFlow
• Digit Classification | Neural network to classify MNIST
dataset using TensorFlow

-Downloading the csv file

-Uploading the fashion-mnist_train.csv file

-Installing the 1.15.5 version of the TensorFlow

-Importing all required dependencies

-Defining the parameters for the neural network

-Creating the computational graph

-Implementing Neural network model using Tensorflow api

-Defining the metrics in order to compute the loss for the dataset, then defining
the AdagradOptimizer which requires learning_rate as a parameter and
computed_loss as an input
