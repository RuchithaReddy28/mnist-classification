# Convolutional Deep Neural Network for Digit Classification

## AIM

To Develop a convolutional deep neural network for digit classification and to verify the response for scanned handwritten images.

## Problem Statement and Dataset
Digit classification and to verify the response for scanned handwritten images.

The MNIST dataset is a collection of handwritten digits. The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively. The dataset has a collection of 60,000 handwrittend digits of size 28 X 28. Here we build a convolutional neural network model that is able to classify to it's appropriate numerical value.

## Neural Network Model

![output](https://github.com/RuchithaReddy28/mnist-classification/blob/main/3.0.png?raw=true)

## DESIGN STEPS

### STEP 1:
Import tensorflow and preprocessing libraries.

### STEP 2:
Download and load the dataset

### STEP 3:
Scale the dataset between it's min and max values

### STEP 4:
Using one hot encode, encode the categorical values

### STEP-5:
Split the data into train and test

### STEP-6:
Build the convolutional neural network model

### STEP-7:
Train the model with the training data

### STEP-8:
Plot the performance plot

### STEP-9:
Evaluate the model with the testing data

### STEP-10:
Fit the model and predict the single input

## PROGRAM
```
Developed By: Akkireddy Ruchitha Reddy
Register NUmber: 212221230004
```

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

![output](https://github.com/RuchithaReddy28/mnist-classification/blob/main/3.1.png?raw=true)
![output](https://github.com/RuchithaReddy28/mnist-classification/blob/main/3.2.png?raw=true)

### Classification Report

![output](https://github.com/RuchithaReddy28/mnist-classification/blob/main/3.3.png?raw=true)

### Confusion Matrix

![output](https://github.com/RuchithaReddy28/mnist-classification/blob/main/3.4.png?raw=true)

### New Sample Data Prediction

![output](https://github.com/RuchithaReddy28/mnist-classification/blob/main/3.5.png?raw=true)
![output](https://github.com/RuchithaReddy28/mnist-classification/blob/main/3.6.png?raw=true)
## RESULT
A convolutional deep neural network for digit classification and to verify the response for scanned handwritten images is developed sucessfully.
