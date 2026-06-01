# Fashion MNIST Classification using CNN (TensorFlow & PyTorch)

## Project Overview

This project implements Convolutional Neural Networks (CNNs) for image classification on the Fashion MNIST dataset using both TensorFlow/Keras and PyTorch.

The goal is to classify clothing items into one of 10 categories, including T-shirts, Dresses, Sneakers, Bags, and Ankle Boots.

## Dataset

Fashion MNIST is a dataset of 70,000 grayscale images (28×28 pixels) divided into:

- 60,000 Training Images
- 10,000 Testing Images
- 10 Clothing Categories

Classes:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

## Technologies Used

- Python
- TensorFlow / Keras
- PyTorch
- NumPy
- Matplotlib

## Project Features

### TensorFlow/Keras Implementation
- Data preprocessing and normalization
- CNN architecture with convolution and pooling layers
- Model training and validation
- Accuracy evaluation
- Prediction visualization

### PyTorch Implementation
- Custom CNN model
- Dropout regularization
- Adam optimizer
- Model saving and loading
- Test accuracy evaluation
- Prediction visualization

## CNN Architecture

- Conv2D (32 filters, 3×3)
- MaxPooling2D
- Conv2D (64 filters, 3×3)
- MaxPooling2D
- Flatten Layer
- Dense Layer (128 neurons)
- Output Layer (10 classes)

## Results

The model successfully classifies Fashion MNIST images with high accuracy using both TensorFlow and PyTorch implementations.

## Skills Demonstrated

- Deep Learning
- Convolutional Neural Networks (CNNs)
- Image Classification
- TensorFlow
- PyTorch
- Data Preprocessing
- Model Evaluation
- Computer Vision Fundamentals

## How to Run

```bash
pip install tensorflow torch torchvision matplotlib numpy
