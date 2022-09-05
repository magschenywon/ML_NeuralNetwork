## What is drop-out and how it helps to reduce over-fit? 
(Explain how weight changes during training and inference times)

The intuition to have the ‘drop-out’ to reduce the overfit problem, is to spread out the weights of each hidden unit. </br>
For example, first is to set the hidden unit as value ‘0’ and with the probability of 0.5. 
This weight could make each hidden unit has the random opportunity to turn on or off, and the value of ‘0’ setup would apply the drop-out task, and then make the hidden layer could not co-adapt with other units at each time while running the model randomly. 
Since drop-out is a regularization technique, is placed during both training and inference time. During the training time, dropout would randomly set an individual node value to zero. During the inference time, dropout would not kill any node value (set into zero), but all the weights at the layer would be multiplied by pkeep.
