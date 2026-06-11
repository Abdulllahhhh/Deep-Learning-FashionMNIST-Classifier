# Deep Learning FashionMNIST Classifier

## Project Overview

This project is an image classification system built using Deep Learning with TensorFlow and Keras. The model is trained on the Fashion-MNIST dataset to recognize different types of clothing items.

## Dataset

The Fashion-MNIST dataset contains grayscale images of clothes and accessories.

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels
* 10 clothing categories

## Tools and Technologies

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

## Data Preprocessing

Before training, all image pixel values were normalized from 0–255 to 0–1. This helps the model learn more efficiently.

## Model Architecture

The neural network consists of:

* Flatten Layer
* Dense Layer (128 neurons, ReLU)
* Dense Layer (64 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

Total Parameters: 109,386

## Training Setup

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Epochs: 5
* Validation Split: 20%

## Results

| Metric              | Result |
| ------------------- | ------ |
| Training Accuracy   | 88.98% |
| Validation Accuracy | 86.98% |
| Test Accuracy       | 86.47% |
| Test Loss           | 0.3738 |

## Conclusion

The model achieved a test accuracy of 86.47%, which is a good result for a simple neural network. The training and validation results were close, showing that the model learned effectively without significant overfitting.

## Future Work

* Use CNN models for higher accuracy.
* Train for more epochs.
* Test on real-world clothing images.
* Apply data augmentation techniques.

## Author

Abdullah Alatwi
