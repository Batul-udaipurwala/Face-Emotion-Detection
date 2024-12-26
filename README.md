# Face-Emotion-Detection

A deep learning-based project for detecting and classifying facial emotions. This project includes two different modules: one for real-time emotion detection using a webcam or video feed and another for emotion detection from photos.


#About the Project

This project leverages Convolutional Neural Networks (CNNs) to classify emotions from facial expressions. The goal is to create a robust and efficient system that can work in real-time and for static images.


#Objective

To accurately identify emotions such as happiness, sadness, anger, surprise, and more from facial expressions.


#Features

Two Modules:

Real-time emotion detection using live video feed.
Emotion detection from static photos.

Pre-trained Model: The included model, emotiondetector.json, achieves 62% accuracy.

Ease of Use: Simply run the corresponding scripts for real-time or image-based emotion detection.

Customizable: Fine-tune the system with additional datasets to improve accuracy.

Requirements File: The requirements.txt file simplifies dependency installation.


#Dataset

The dataset used for training is the FER-2013 dataset, which was obtained from Kaggle. It includes labeled images across seven emotion categories.


#Installation

Download the Haar Cascade Classifier XML file:

Download haarcascade_frontalface_default.xml from OpenCV's GitHub repository.
Place the file in the project directory for face detection.

#Project Workflow

Data Preprocessing:

Normalize images to improve training efficiency.
Apply data augmentation to handle overfitting and improve generalization.

Model Training:

Train a CNN-based architecture using the FER-2013 dataset.
Save the trained model as emotiondetector.json.

Detection:

Use the Haar Cascade Classifier to detect faces.
Predict emotions using the trained CNN model.
