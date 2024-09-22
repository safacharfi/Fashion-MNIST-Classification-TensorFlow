# Fashion-MNIST Classification with TensorFlow

This project implements a neural network using TensorFlow and Keras to classify images from the Fashion MNIST dataset. The model is trained to recognize various types of clothing, including T-shirts, trousers, dresses, and more.

## Project Overview

The **Fashion-MNIST** dataset consists of 70,000 grayscale images of 28x28 pixels, each associated with a label from 10 different clothing categories. The goal of this project is to build and train a deep learning model to accurately classify these images into one of the 10 categories.

### Dataset

The dataset includes:
- **Training set**: 60,000 images
- **Test set**: 10,000 images

Each image is 28x28 pixels and labeled with one of the following categories:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Model Architecture

The model is a **Sequential neural network** with the following layers:
1. **Flatten**: Converts each 28x28 image into a 1D array of 784 pixels.
2. **Dense Layer**: Fully connected layer with 128 neurons and ReLU activation function.
3. **Dense Output Layer**: 10 neurons (one for each class) with Softmax activation function to output a probability distribution over the 10 classes.

### Model Compilation

The model is compiled using:
- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy (suitable for integer labels)
- **Metrics**: Accuracy

### Model Training

The model is trained on the Fashion MNIST dataset for 5 epochs using the training data. It then evaluates its performance on the test data.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib



