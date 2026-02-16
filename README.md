# MNIST-Handwritten-Digit-Classification-with-PyTorch

🧠 Handwritten Digit Recognition using PyTorch (MNIST)

This project implements a handwritten digit classification system using PyTorch and the MNIST dataset. A fully connected neural network is trained to recognize digits (0–9) from grayscale images of size 28×28 pixels.

The model is trained using CrossEntropy Loss and the Adam optimizer, achieving reliable accuracy on the MNIST test dataset. The project also includes model saving, evaluation on unseen data, and single-image prediction with visualization.

🚀 Features

Uses the MNIST handwritten digit dataset

Fully connected neural network (MLP) architecture

GPU acceleration support (CUDA if available)

Training and evaluation loops implemented from scratch

Test accuracy calculation

Model persistence using torch.save

Visualization of predictions using Matplotlib

Single image inference support

🛠 Tech Stack

Python

PyTorch

Torchvision

Matplotlib

📂 Model Architecture

Input Layer: 784 neurons (28×28 pixels)

Hidden Layer 1: 128 neurons + ReLU

Hidden Layer 2: 64 neurons + ReLU

Output Layer: 10 neurons (digits 0–9)

📊 Dataset

MNIST Handwritten Digits Dataset

60,000 training images

10,000 test images

Grayscale images (28×28)

📌 Use Cases

Beginner-friendly deep learning project

Understanding PyTorch training pipelines

Image classification fundamentals

Baseline model for computer vision tasks

📈 Future Improvements

Convert MLP to CNN for higher accuracy

Add training loss and accuracy graphs

Implement confusion matrix

Build a GUI or web interface for live digit prediction
