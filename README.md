# Building a Regression Model in Keras Neural Network

#### Course Project - Introduction to Deep Learning & Neural Networks with Keras
**Ahmed Yahya Khaled** \
*July 11, 2020*

### Introduction

Here, We'll build a regression model using the deep learning Keras library, and then We'll experiment with increasing the number of training epochs and changing number of hidden layers and we'll see how changing these parameters impacts the performance of the model.

### Pre-work

1. Import the Dataset
2. Explore the Dataset 
3. Data Preprocessing

### Building Models

## **A.** Build a baseline model

Use the Keras library to build a neural network with the following:

- One hidden layer of 10 nodes, and a ReLU activation function

- Use the adam optimizer and the mean squared error as the loss function.

1. Randomly split the data into a training and test sets by holding 30% of the data for testing. You can use the train_test_splithelper function from Scikit-learn.

2. Train the model on the training data using 50 epochs.

3. Evaluate the model on the test data and compute the mean squared error between the predicted concrete strength and the actual concrete strength. You can use the mean_squared_error function from Scikit-learn.

4. Repeat steps 1 - 3, 50 times, i.e., create a list of 50 mean squared errors.

5. Report the mean and the standard deviation of the mean squared errors.




