# CIFAR-10 Image Classification

This project implements an image classification model using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset. The model is designed to classify images into ten distinct categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Table of Contents

- [Model Architecture](#model-architecture)
- [Results](#results)
- [Future Work](#future-work)
- [Installation](#installation)

## Model Architecture
The CNN model consists of the following layers:

- 3 Convolutional layers with ReLU activation
- 2 MaxPooling layers
- 1 Flatten layer
- 2 Dense layers (one with ReLU activation and one with softmax activation for classification)

## Results
The model achieves a test accuracy of approximately 70.31%. Visualizations of predictions will be displayed after training.(Check the visualizations in ipynb file)

## Future Work
Experiment with more complex architectures (e.g., ResNet, VGG).
Implement data augmentation techniques to improve model robustness.
Fine-tune hyperparameters for better performance.

## Installation

To run this project, you need to have Python installed on your machine. You can install the required libraries using pip:

```bash
pip install tensorflow matplotlib
