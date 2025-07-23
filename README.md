# 🧠 MNIST Number Prediction using CNN

Welcome to the **MNIST Number Prediction** project! This repository contains a Jupyter Notebook that trains a Convolutional Neural Network (CNN) to recognize handwritten digits using the classic MNIST dataset. This is a beginner-friendly deep learning project that demonstrates the power of CNNs for image classification.

![MNIST Digits](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## 📌 Project Overview

- **Dataset**: [MNIST](http://yann.lecun.com/exdb/mnist/) (70,000 grayscale images of handwritten digits from 0–9)
- **Model Type**: Convolutional Neural Network (CNN)
- **Framework**: TensorFlow / Keras
- **Goal**: Predict the correct digit from a 28x28 grayscale image

## 🛠️ Tech Stack

- Python 🐍
- TensorFlow & Keras
- NumPy
- Matplotlib (for visualization)

## 🚀 Features

- Preprocessing and normalization of image data
- Construction of a CNN architecture with Conv2D, MaxPooling, Dropout, and Dense layers
- Training on 60,000 images and evaluating on 10,000 test images
- Visualization of training metrics (accuracy & loss)
- Predicting and visualizing model outputs on test images

## 📊 Model Architecture Summary

## 📈 Results

- **Training Accuracy**: ~99%
- **Test Accuracy**: ~98%
- The model shows strong generalization with minimal overfitting.

## 🖼️ Sample Predictions

Some example test images and their predicted labels are shown in the notebook using `matplotlib`.

## 🧪 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/hiteshjha24/MNIST_dataset_based_model.git
   cd MNIST_number_prediction

