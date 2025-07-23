# Pneumonia_Detection_Using_CNN
This project implements a Convolutional Neural Network (CNN) to detect pneumonia from chest X-ray images using PyTorch. The model is trained on a dataset of X-ray images to classify them as either "normal" or "pneumonic.

# Project Overview
The goal of this project is to build a deep learning model for binary classification of chest X-ray images to assist in pneumonia diagnosis. The project includes data preprocessing, model training, evaluation, and a live demo for real-time predictions using Gradio.

# Features
- Data Preprocessing: Image resizing, normalization, and dataset splitting (70% train, 15% validation, 15% test).
- Model Architecture: Custom CNN designed for medical image classification.
- Training: Includes loss function, optimizer, and learning rate scheduling.
- Evaluation: Metrics such as accuracy, confusion matrix.
- Live Demo: A Gradio interface for uploading X-ray images and getting real-time predictions.

# Prerequisites
- Python 3.8+
- PyTorch, torchvision
- Gradio (for live demo)
- Other dependencies: numpy, pandas, matplotlib, seaborn, scikit-learn, Pillow
