# CIFAR-10 VGG16 Architecture

## 🧠 Project Overview

This project implements and trains the **VGG16 convolutional neural network** architecture on the **CIFAR-10** image classification dataset. The goal is to achieve high accuracy on this benchmark dataset by adapting the VGG16 model—originally designed for larger images—to the 32x32 images in CIFAR-10.

## 📦 Dataset

**CIFAR-10** is a labeled subset of the Tiny Images dataset containing 60,000 32x32 color images in 10 classes, with 6,000 images per class:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Split:
- **50,000** training images
- **10,000** testing images

## 🏗️ Architecture

The model used is a modified version of **VGG16** tailored to handle 32x32 inputs. Key modifications may include:
- Adjusted input shape
- Reduced number of fully connected layer parameters
- Optionally adding batch normalization and dropout

## 🔧 Implementation Details

- **Framework**: TensorFlow / Keras (or PyTorch, depending on your implementation)
- **Optimizer**: Adam / SGD
- **Loss Function**: Categorical Crossentropy
- **Metrics**: Accuracy

## 🚀 Training

- Number of Epochs: _e.g., 50_
- Batch Size: _e.g., 64_
- Data Augmentation: Random flip, rotation, zoom, etc.

## 📈 Results

- Achieved Accuracy: _e.g., 91.5% on test set_
- Training Time: _e.g., 45 minutes on NVIDIA RTX 3060_
- Loss and Accuracy plots included

## 📊 Visualizations

- Confusion matrix
- Sample predictions
- Training/validation loss and accuracy plots


## 📌 How to Run

1. Clone the repository:
   ```
   bash
   git clone https://github.com/not-saad-zahid/Cifar10-VGG16-ANN-Architecture.git
   cd cifar10-vgg16
   ```
