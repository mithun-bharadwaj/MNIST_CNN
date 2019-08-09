# MNIST_CNN

## Architecture
I've used 2 convolution layers and 2 fully connected layers with 10 softmax units in the output layer. 

Some of the hyperparameters are:
1. Number of epochs
2. Batch size 
3. Number of filters
4. Filter size
5. Stride
6. Learning rate (for the optimization algorithm)

They can be tuned easily in the source code to check their impact on performance

## Accuracy
Number of epochs trained: 5
* Training set accuracy: 98.42% (57,000 images)
* Validation set accuracy: 99.03% (3,000 images or 5% of the training set)
* Test/Dev set accuracy: 99.05% (10,000 images)

## System requirements
1. Jupyter notebook
2. Tensorflow
3. Keras
4. Numpy
5. Matplotlib

## How to run
Download the source code file (CNN_MNIST.ipynb) into a root folder. Download the folder in data (MNIST) and paste the entire folder in the same location as the source code. Then run all the cells in the source code file.

If you paste the MNIST data folder in a different location, an appropriate path should be provided while loading the data in the source code.
