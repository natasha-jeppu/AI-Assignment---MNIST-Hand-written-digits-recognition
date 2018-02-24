# AI-Assignment---MNIST-Hand-written-digits-recognition
A comparison of different ANN networks for classifying hand written digits based on test loss and test accuracy. The parameters modified are: optimizer, activation function, number of hidden layers, number of nodes in each layer and batch size.

Observations:
1. The Adam optimizer gives highest accuracy amongst Adagrad, SGD with momentum and Adadelta.
2. Increasing number of nodes increases the accuracy but at the same time slows down the process.
3. Reducing batch size gives better accuracy than using a batch size = input size.
4. Relu is the preferred activation function in the hidden layers.
