# Image-Classification-Using-Deep-Learning-in-TensorFlow
Grayscale CIFAR-10 Image Classification using TensorFlow

Description

This project focuses on classifying CIFAR-10 images converted to grayscale using a deep learning model built with TensorFlow.
The workflow includes preprocessing the data, training a neural network, evaluating performance, and analyzing misclassifications using a confusion matrix.

Project Highlights

Converted CIFAR-10 images to grayscale for simplified feature learning.
Reshaped and verified input data to match the model’s requirements.
Built and compiled a deep learning model using TensorFlow.
Trained the model and evaluated it using loss and accuracy metrics.
Made predictions on grayscale images and applied softmax to interpret output probabilities.
Visualized predictions and analyzed errors using a confusion matrix.
Generated a classification report showing precision, recall, and F1-scores for each class.

Steps Involved

Convert CIFAR-10 images into grayscale.
Reshape grayscale images to fit model input.
Convert labels (Y Tensor) into NumPy arrays.
Build and verify the model input shape.
Make predictions and apply softmax for probability outputs.
Define and calculate the loss function.
Compile the model with optimizer, loss, and metrics.
Train the model and evaluate its accuracy and loss.
Visualize correct and incorrect predictions.
Analyze model performance using confusion matrix and classification report.

Tools and Libraries

TensorFlow
Keras
NumPy
Matplotlib
Scikit-learn (for confusion matrix and classification report)
