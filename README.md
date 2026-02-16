🧠 MNIST Handwritten Digit Recognition using PyTorch

This project implements a handwritten digit recognition system using PyTorch and the MNIST dataset. A fully connected neural network (MLP) is trained to classify grayscale images of handwritten digits (0–9).

The project demonstrates the complete deep learning workflow including data loading, model creation, training, evaluation, visualization, and single-image prediction.

📌 Features

MNIST handwritten digit dataset

Fully connected neural network (MLP)

GPU acceleration (CUDA support if available)

Training and evaluation loops

Test accuracy calculation

Model saving using torch.save()

Single image prediction

Visualization using Matplotlib

🛠 Tech Stack

Python

PyTorch

Torchvision

Matplotlib

🧠 Model Architecture
Layer	Description
Input Layer	784 neurons (28×28 pixels)
Hidden Layer 1	128 neurons + ReLU
Hidden Layer 2	64 neurons + ReLU
Output Layer	10 neurons (digits 0–9)
📊 Dataset

MNIST Handwritten Digits Dataset

60,000 training images

10,000 test images

Image size: 28×28 (grayscale)

🚀 How to Run
1️⃣ Install Dependencies
pip install torch torchvision matplotlib
2️⃣ Run the Training Script
python train.py

The MNIST dataset will automatically download on the first run.

📈 Training Output

Prints loss for each epoch

Evaluates accuracy on the test dataset

Saves the trained model as:

mnist_model.pth
🖼 Sample Prediction

The program:

Displays a test image

Shows the actual label

Predicts the digit using the trained model

📌 Use Cases

Beginner-friendly deep learning project

Learning PyTorch training pipelines

Image classification fundamentals

Baseline model for computer vision tasks

🔮 Future Improvements

Replace MLP with CNN for higher accuracy

Add training loss and accuracy graphs

Implement confusion matrix

Build GUI or web app for live digit drawing

Hyperparameter tuning

👤 Author

Thakor Harshad Mahendraji
M.Sc. Environmental Science | Aspiring Data Scientist

⭐ Acknowledgements

MNIST Dataset

PyTorch Documentation
