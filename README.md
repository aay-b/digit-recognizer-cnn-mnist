# digit-recognizer-cnn-mnist
Convolutional Neural Network (CNN) model built for the Kaggle Digit Recognizer competition using the MNIST dataset. Achieved 98.9% accuracy on validation. Includes data preprocessing, model training with Keras, and a clean prediction pipeline for handwritten digit classification.


# Digit Recognizer - CNN (98.9% Accuracy)

This project solves the [Kaggle Digit Recognizer competition](https://www.kaggle.com/competitions/digit-recognizer) using a Convolutional Neural Network (CNN) built with TensorFlow/Keras. The model classifies images of handwritten digits (0–9) from the MNIST dataset.


## 📌 Objective

Classify grayscale 28x28 pixel images of handwritten digits into their correct numeric labels using supervised deep learning.

---

## What I did

- Data preprocessing (normalization, reshaping)
- CNN model architecture with dropout regularization
- Model training and validation using Keras
- Submission file generation for Kaggle
- Achieved **98.9% validation accuracy**

---

## Dataset

- **Train data**: 42,000 labeled digit images
- **Test data**: 28,000 unlabeled digit images
- Each image is 28×28 pixels, flattened to 784 features in CSV format

---

## Model Architecture

- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten → Dense (128) → Dropout (0.5)
- Output: Dense (10, softmax)

---

## Tools Used

- Python
- Pandas, NumPy
- TensorFlow / Keras
- Jupyter Notebook / Kaggle Notebook

---

## Result

Achieved 98.9% Accuracy on the Kaggle leaderboard with this model.

---

## 🔗 Kaggle Notebook
[👉 View the Kaggle notebook here](https://www.kaggle.com/code/aayb10/digit-recognizer-98-9-accuracy-with-cnn)

