# Regression with Keras neural newtworks

# This is the final project in Introduction to Deep Learning & Neural Networks with Keras course by IBM

## A. Build a baseline model (<a href="https://github.com/JamesJeberson/Regression-with-Keras-neural-newtworks-/blob/main/A%20-%20Regression%20with%20Keras%20-%20Final%20Project.ipynb" target="_blank">Solution</a>) 

Use the Keras library to build a neural network with the following:
- One hidden layer of 10 nodes, and a ReLU activation function
- Use the adam optimizer and the mean squared error  as the loss function.
1. Randomly split the data into a training and test sets by holding 30% of the data for testing. 
2. Train the model on the training data using 50 epochs.
3. Evaluate the model on the test data and compute the mean squared error between the predicted concrete strength and the actual concrete strength. You can use the mean_squared_error function from Scikit-learn.
4. Repeat steps 1 - 3, 50 times, i.e., create a list of 50 mean squared errors.
5. Report the mean and the standard deviation of the mean squared errors.

## B. Normalize the data (<a href="https://github.com/JamesJeberson/Regression-with-Keras-neural-newtworks-/blob/main/B%20-%20Regression%20with%20Keras%20-%20Final%20Project.ipynb" target="_blank">Solution</a>) 

Repeat Part A but use a normalized version of the data. Recall that one way to normalize the data is by subtracting the mean from the individual predictors and dividing by the standard deviation.

## C. Increate the number of epochs (<a href="https://github.com/JamesJeberson/Regression-with-Keras-neural-newtworks-/blob/main/C%20-%20Regression%20with%20Keras%20-%20Final%20Project.ipynb" target="_blank">Solution</a>)

Repeat Part B but use 100 epochs this time for training.

## D. Increase the number of hidden layers (<a href="https://github.com/JamesJeberson/Regression-with-Keras-neural-newtworks-/blob/main/D%20-%20Regression%20with%20Keras%20-%20Final%20Project.ipynb" target="_blank">Solution</a>)

Repeat part B but use a neural network with the following instead:
- Three hidden layers, each of 10 nodes and ReLU activation function.
