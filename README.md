# MNIST-NeuralNetwork-TensorFlow

Implementation of Neural Networks using Tensor Flow. 

The dataset used is MNIST's handwriting data which uses approximately 60,000 28*28 pixel images of hand written numbers. 

Used 3 hidden layers with 500 nodes each
Used 10 epochs for forward and back propagation
Used AdamOptimizer to minimize cost function
Used softmax_cross_entropy_with_logits to calculate cost function

Achieved an accuracy of 94.69% on the test dataset

Extracting /tmp/data/train-images-idx3-ubyte.gz
Extracting /tmp/data/train-labels-idx1-ubyte.gz
Extracting /tmp/data/t10k-images-idx3-ubyte.gz
Extracting /tmp/data/t10k-labels-idx1-ubyte.gz
Epoch 0 completed out of 10 loss: 1894283.11475
Epoch 1 completed out of 10 loss: 407599.110336
Epoch 2 completed out of 10 loss: 218386.406212
Epoch 3 completed out of 10 loss: 129236.364692
Epoch 4 completed out of 10 loss: 80897.0573309
Epoch 5 completed out of 10 loss: 51128.0831414
Epoch 6 completed out of 10 loss: 30541.7300525
Epoch 7 completed out of 10 loss: 21930.4604849
Epoch 8 completed out of 10 loss: 22995.1314586
Epoch 9 completed out of 10 loss: 19337.32017
Accuracy: 0.9469
