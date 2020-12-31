# Back Propagation Algorithm 

This is an implementation of the Multi Layer Perceptron (MLP) or Artificial Neural Network (ANN) in MATLAB.

The code is for a 3 layer (2 hidden layers) neural network with ReLU activations in the first two layers and a logistic
sigmoid in the output layer.


### How to use?

    net = neuralnet(n_input, n_hidden, n_hidden);
    n_epochs = 1000; % increase this for better fit
    lr = 0.3; % learning rate
    lambda = 0.1;
     
    % Train the Network
    net = train_neuralnet(net, train_data, train_labels, n_epochs, lr, lambda);
     
    % Test the Network
    outputs = predict_neuralnet(net, test_data);


### Updates
- (31/Dec/2020): Regularization is added!