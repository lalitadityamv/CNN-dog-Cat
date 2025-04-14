# Dog vs Cat Classifier 🐶🐱

This project implements a Convolutional Neural Network (CNN) in Python using TensorFlow/Keras to classify images of dogs and cats.

## 📌 Project Overview

The goal is to build a binary image classifier that can distinguish between images of cats and dogs with high accuracy. The model is trained on labeled image data and evaluated using various performance metrics.

## 🧠 Model Architecture

The CNN architecture used includes:

- Input Layer: 128x128 RGB images
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten
- Dense → ReLU
- Dropout
- Output Layer (Dense with sigmoid activation)

## 🗂 Dataset

- Source: [Kaggle Dogs vs. Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)
- Size: 25,000 images (12,500 dogs and 12,500 cats)
- Preprocessing:
  - Resized to 128x128
  - Normalized pixel values (scaled to [0, 1])
  - Split: 80% training, 10% validation, 10% testing

## 🛠 Requirements

- Python 3.8+
- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-learn

Install dependencies:

```bash
pip install -r requirements.txt
