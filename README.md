# Digit-Classification
A simple deep learning project that uses a Neural Network to recognize handwritten digits from the MNIST dataset. It includes a predictive system to test the model with your own images

# MNIST Handwritten Digit Classification

Deep Learning project that identifies handwritten digits (0-9) using a Neural Network.

## 📌 Project Overview
The goal of this project is to recognize handwritten numbers using the **MNIST dataset**. The project covers data collection, preprocessing, building a neural network, and creating a predictive system for custom images.

## 🛠 Libraries Used
* **TensorFlow & Keras**: For building and training the neural network.
* **NumPy**: For handling image data as arrays.
* **OpenCV (cv2)**: For computer vision and processing custom images.
* **Matplotlib & Seaborn**: For visualizing image data and performance metrics.
* **PIL (Pillow)**: For image processing tasks.

## 📊 Dataset Details
* **Source**: Keras Datasets.
* **Train Data**: 60,000 images.
* **Test Data**: 10,000 images.
* **Image Dimensions**: 28x28 pixels in Grayscale (1 channel).

## 🧠 Model Architecture
The model is a **Sequential Neural Network** with the following layers:
1. **Flatten Layer**: Converts the 28x28 matrix into a 1D array.
2. **Hidden Layer 1**: 50 neurons with **ReLU** activation.
3. **Hidden Layer 2**: 50 neurons with **ReLU** activation.
4. **Output Layer**: 10 neurons (one for each digit) with **Sigmoid** activation.

## 🚀 Training & Results
* **Optimizer**: Adam.
* **Loss Function**: Sparse Categorical Crossentropy.
* **Epochs**: 10.
* **Training Accuracy**: ~99%.
* **Test Data Accuracy**: 97.1%.

## 🔮 Predictive System
The code includes a predictive system that takes a custom image path, processes it (grayscale conversion and resizing to 28x28), and predicts the handwritten digit.

