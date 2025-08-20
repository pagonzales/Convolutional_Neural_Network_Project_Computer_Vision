# Convolutional Neural Network Project: Computer Vision/Image Detection Project
## Problem
A certain company wants to create an algorithm that detects whether or not the image is a Dog or a Cat. Using an Artificial Intelligence Algorithm with Convolutional Neural Network Architecture, we will try to solve this problem.

## Project Objective
- To create an Artificial Intelligence Algorithm that uses Convolutional Neural Network architecture to train a machine that can detect whether an image is a dog or a cat.

## Data used
- For the data used, I just downloaded a bunch of images of cats and dogs to train the model. Since it is too big, I cannot upload it here.

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
  - Then create a convolutional layer
  - Then apply max pooling to the convolutional layer
  - Add a second convolutional layer
  - Next, apply flattening
  - Create a full connection layer
  - Finally, create an output layer
- Compile the ANN
  - Use 'adam' as optimizer 'binary_crossentropy' as loss function and 'accuracy' as metrics
  - Train the model with batch size = 32 and epochs = 100
- Finally, Test the model using the test data
  - Create Confusion Matrix
## Project Insights
- Using the Convolutional Neural Network architecture, I have modelled the data with 90.44% accuracy from using the training set and 79.65% accuracy using the test set.

## Final conclusion
Using the parameters and hyperparameters above, we have a test model accuracy of 76.65%. Of course, this can still be improved by altering the parameters and choosing different activation functions and hidden layers. But this model we have presented here predicts that for 100 images of cats and dogs, it can correctly predict 79 out of 100 of them.
