# Predicting_bike_rental_ridership
This project is about building a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, a much better understanding of gradient descent, backpropagation, and other concepts is gained. This project is the first requirement to graduate Udacity's Deep learning Nano-degree.

The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is  𝑓(𝑥)=𝑥 .

The mission is to implement the forward and backward passes from scratch and choose all the network parameters that allows the trained model to pass certain rubric. 

My code passed all the unit tests as well as the rubric, which implies producing good results when running the network on full data. Requirements are:
•	Training loss should be less than 0.09
•	Validation loss should be less than 0.18

My network parameters were:
iterations = 10000
learning_rate = 0.5
hidden_nodes = 7
output_nodes = 1

My output:
Training loss: 0.062 ... Validation loss: 0.158
