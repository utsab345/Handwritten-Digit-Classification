# MNIST Digit Classifier

This project demonstrates the creation of a simple digit classification model using the MNIST dataset. The model uses TensorFlow and Keras for implementation, providing insights into preprocessing, training, and evaluating the dataset.

## Dataset

The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) consists of handwritten digit images (0-9). It includes:
- **Training Set:** 60,000 samples
- **Test Set:** 10,000 samples

Each image is grayscale and has a size of 28x28 pixels.

## Features

- **Data Normalization:** Input pixel values are scaled to the range [0, 1].
- **Visualization:** Uses Matplotlib to display sample images.
- **Deep Learning Model:** Fully connected neural network using Keras and TensorFlow.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>

## Code Overview
1. Data Loading
   ```bash
   keras.datasets.mnist.load_data() to fetch the MNIST dataset.
2. Data Preprocessing:
   ```bash
   Normalizes pixel values for faster convergence.
3. Model Architecture:
   ```bash
   Utilizes Dense and Flatten layers for classification.
4. Visualization
   ```bash
   Displays digit samples using Matplotlib.

## Usage
1. Run the script:
   ```bash
   python main.py
2. The model will:
- Load and preprocess the dataset.
- Train a neural network.
- Display a sample image.
- Evaluate performance on the test set.

## Future Work
- Add CNN layers for better accuracy.
- Experiment with data augmentation techniques.
- Implement deployment using FastAPI.
