# MNIST Digit Recognition

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0-9) using the **MNIST dataset**. The model is built with **TensorFlow** and **Keras** for deep learning tasks.

## Project Overview

The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits. The model uses a CNN to classify these digits with high accuracy.

### Key Features:
- **Data Preprocessing**: Rescaling images for better model performance.
- **CNN Architecture**: A simple CNN model with multiple convolutional and pooling layers.
- **Model Evaluation**: The model is evaluated using accuracy and loss metrics on the test data.
- **Saved Model**: The trained model is saved as `mnist_model.h5`, which can be used for predictions.

## Files in the Repository
- **`mnist_digit_recognition.ipynb`**: Jupyter notebook with the code for training and testing the model.
- **`mnist_model.h5`**: The trained model file (saved after training).
- **`requirements.txt`**: The list of dependencies needed to run the project.
- **`README.md`**: This file, containing information about the project.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/mnist_digit_recognition.git
   cd mnist_digit_recognition
