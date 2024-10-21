                                                      Real-Time Stress and Emotion Recognition System
Project Overview

This project is focused on developing a Convolutional Neural Network (CNN) to accurately detect human emotions from facial expressions in real-time. It leverages TensorFlow and OpenCV to classify emotions into seven categories: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise. Additionally, it assesses stress levels based on the detected emotions. This README outlines the project setup, model architecture, and instructions for running the application.

Features

Real-time emotion detection using webcam feed.
Stress level indication based on the emotion detected.
Training of a CNN model on a labeled dataset of facial expressions.
Evaluation of model performance with sample images.

Installation
Prerequisites

Python 3.x

TensorFlow 2.x

OpenCV

Keras

Model Architecture

The CNN model consists of multiple Conv2D and MaxPooling2D layers, Dropout layers for regularization, and Dense layers for classification. The model is compiled with the Adam optimizer and categorical cross-entropy loss function.

Dataset

The model was trained and validated on a dataset not included in this repository due to size constraints. Please ensure you have a similar structured dataset in Dataset/train and Dataset/test directories for training and evaluation purposes.
