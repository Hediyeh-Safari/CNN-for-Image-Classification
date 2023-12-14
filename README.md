# CNN-for-Image-Classification

Train a convolutional network (CNN) using a machine learning library on the CIFAR10 dataset. Download and load the dataset using library APIs, splitting it into training and testing sets. For this problem, randomly sample 20% of the training set as a new training set and use the original test set for validation. Implement the following in a single .ipynb with all output already displayed:

1-MLP (Multi-Layer Perceptron):

Construct an MLP with layers:
Fully connected layer (512 units, sigmoid activation)
Fully connected layer (512 units, sigmoid activation)
Output layer (classification task)

2-CNN1 (Convolutional Neural Network 1):

Design a CNN with layers:
2D Convolutional layer (64 filters, 3x3 size, ReLU activation)
2D Convolutional layer (64 filters, 3x3 size, ReLU activation)
Fully connected layer (512 units, sigmoid activation)
Fully connected layer (512 units, sigmoid activation)
Output layer (classification task)

3- CNN2 (Convolutional Neural Network 2):

Create a CNN with layers:
2D Convolutional layer (64 filters, 3x3 size, ReLU activation)
2x2 Max pooling layer
2D Convolutional layer (64 filters, 3x3 size, ReLU activation)
2x2 Max pooling layer
Fully connected layer (512 units, sigmoid activation)
Dropout layer (0.2 dropout rate)
Fully connected layer (512 units, sigmoid activation)
Dropout layer (0.2 dropout rate)
Output layer (classification task)
Use a batch size of 32, Adam optimizer, and an appropriate loss function for both networks. Train each network for 5 epochs.

References used for this question:
https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
