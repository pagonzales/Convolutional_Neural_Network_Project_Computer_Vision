# Convolutional Neural Network Project: Computer Vision/Image Detection Project
## Problem
A certain company wants to create an algorithm that detects whether or not the image is a Dog or a Cat. Using a Deep Learning Algorithm with Convolutional Neural Network Architecture, we will try to solve this problem.

## Project Objective
- To create a Deep Learning Algorithm that uses Convolutional Neural Network architecture to train a machine that can detect whether an image is a dog or a cat.

## Data used
- <a href = "asdfasdf">Dataset</a>

## Metrics
- What is the probability that the final image is a dog or a cat?
- What is the accuracy of the model?

## Action plan
- Preprocess the data
  - Import the necessary libraries
  - Preprocess the training set by transforming it to avoid overfitting the data using image augmentation
  - Preprocess the test set but use only the feature scaling to avoid data leakage
- Build the Convolutional Neural Network (CNN) Algorithm
  - Start with initialising the CNN using the tensorflow and keras.
  - Then, create a convolutional layer
  - Then, pool the convolutional layer
  - 
- Compile the ANN
  - Use 'adam' as optimizer 'binary_crossentropy' as loss function and 'accuracy' as metrics
  - Train the model with batch size = 32 and epochs = 100
- Finally, Test the model using the test data
  - Create Confusion Matrix
