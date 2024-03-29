# Deep learning ANN model from scratch
Designing a model from scratch help you understand the algorithm and also give you much insights to help you solve practical/real world problems. Though modern day deep learning packages like Tensorflow are quick and efficient, learning from scratch helps you learn the nitty gritty of the model architecture. This GitHUB page is an attempt to understand Artificial Neural Network models by developing it from scratch. 

## Artificial Neural Network design from scratch using numpy (ANN)
Description:
To start with, we will design a neural network that can be parameterized to form shallow or deep neural network. Following are some of the typical parameters that can be tuned.
- Number of layers, units and their activation functions with options of sigmoid, tanh, relu and leaky relu. We can define softmax function for multi class classifier.
- Optimizers like Gradient Descent, Gradient Descent with momentum, RMSprop and Adam
- Batch/Mini batch/Stochastic Gradient
- Learning rate Decay for better optimization
- L2 regularization and Drop out regularization methods

We will use/create a petal dataset to train, predict and form decision boundary. This will help us to understand how much Neuralnet is capable of understanding the nonlinear region where traditional machine learning algorithm struggles.

## Artificial Neural Network design from scratch using tensorflow (ANN)
Now let's build similar network using tensorflow and process the petal dataset with similar parameters, that will help you understand the advantage of Tensorflow. Tensorflow frame is fast, efficient and easier to code. One of key highlights of tensorflow is it finds its own way to do backward propagation and update parameters. There are other benefits that are useful like use of GPU or parallel processing however that is not in scope of our discussion here.
**NOTE**: The code written in tensorflow is just to compare the model design approach using numpy and tensorflow.

## Reference : Andrew Ng's Deeplearning lectures at Standford University and Deeplearning.ai
