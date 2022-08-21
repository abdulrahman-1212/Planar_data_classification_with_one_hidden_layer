# Planar_data_classification_with_one_hidden_layer
This is an implementation of one-hidden-layer neural network. It is Assignment 3 in deep learning specialzation course 1.

<h2>The problem:<h2>
  <ul>
    <li>Implement a 2-class classification neural network with a single hidden layer</li>
    <li>Use units with a non-linear activation function, such as tanh</li>
    <li>Compute the cross entropy loss</li>
    <li>Implement forward and backward propagation</li>
  <ul>
    
    <h2>Activation function</h2>
    <p>I used tanh as an activation function for the hidden layer and sigmoid function for the output layer</p>
    
    ### 4.4 - Compute the Cost

Now that you've computed $A^{[2]}$ (in the Python variable "`A2`"), which contains $a^{[2](i)}$ for all examples, you can compute the cost function as follows:

$$J = - \frac{1}{m} \sum\limits_{i = 1}^{m} \large{(} \small y^{(i)}\log\left(a^{[2] (i)}\right) + (1-y^{(i)})\log\left(1- a^{[2] (i)}\right) \large{)} \small\tag{13}$$

<a name='ex-5'></a>
