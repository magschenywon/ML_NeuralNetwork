## Design a neural network that has two input nodes and one output node.

The to-be-learned function is y = x1 * x2. You can assume that 0 <= x1, x2 <= 1. 
-  Describe your network structure. How many layers, how many nodes in each layer and how nodes are connected.
```
The first hidden layer has 12 nodes and uses the relu activation function (rectified linear unit activation function).
The second hidden layer has 8 nodes and still uses the relu activation function.
The final output layer has one node, which is the class variable, and uses the sigmoid activation function.
```
-  What is your activation function? 
```
The first two layers activation function is rectified linear unit activation function. 
The last output layer activation function is Sigmoid function.
```
-  Describe your loss function 
```
Using cross entropy as the loss function, because this loss function is for a binary classification problem. 
```
-  How do you update your weights and biases? 
 ```
 model.add(Dense(12, input_dim=8, init='uniform', activation='relu'))
drop
 ```
