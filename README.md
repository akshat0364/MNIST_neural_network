# MNIST Digit Recognition with TensorFlow

This repository contains a simple implementation of a neural network for recognizing handwritten digits using the MNIST dataset. The code is written in Python and utilizes TensorFlow and Matplotlib for building and visualizing the model.

## Overview

The neural network implemented in this code is a basic feedforward model with one dense layer. It is trained on the MNIST dataset, which consists of 28x28 pixel grayscale images of handwritten digits (0 through 9).

## Dependencies

Before running the code, ensure you have the following dependencies installed:

- TensorFlow
- Matplotlib
- NumPy
You can install them using the following commands:

```bash
pip install tensorflow matplotlib numpy
```

## Model Training

The model is trained using the MNIST dataset for handwritten digit recognition. The training script (mnist_digit_recognition.py) includes the following key steps:
Loading the MNIST dataset using TensorFlow.
Preprocessing the data by normalizing pixel values to the range [0, 1].
Building a simple neural network with one dense layer.
Compiling the model with the Adam optimizer and sparse categorical crossentropy loss.
Training the model on the training data for 5 epochs.

## Results
After training, the model's performance is evaluated on the test set. The predictions for some sample test images are visualized using Matplotlib.
Feel free to explore and modify the code to experiment with different neural network architectures and training parameters.
code by: akshat0364

Happy coding!


