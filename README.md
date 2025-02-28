# Human Action Recognition

## Overview

This project focuses on **Human Action Recognition (HAR)** using machine learning and deep learning techniques. The goal is to classify different human actions based on video or image sequence data.

## Features

- **Data Preprocessing**: Handles image/video dataset processing, including resizing, normalization, and augmentation.
- **Model Training**: Employs deep learning architectures such as **Convolutional LSTM** and **LRCN**, with LRCN proving to be faster to train and achieving better accuracy, which are designed to handle spatiotemporal features in action recognition.
- **Evaluation**: Assesses model performance using metrics like accuracy, precision, recall, and F1-score to ensure reliable classification.
- **Video Prediction**: Processes pre-recorded videos to recognize human actions, making it useful for applications such as video analysis, surveillance, and activity recognition.
- **Recognized Actions**: The model is currently trained to classify the following four actions:
  - Pushups
  - Juggling Balls
  - Playing Piano
  - Punching

## Dataset

This project utilizes the **UCF50 Action Recognition Dataset**, a well-known dataset containing videos of human activities across various categories. 

## Results

The model achieves high accuracy in recognizing the specified human actions. Among the tested architectures, **LRCN demonstrated faster training times and better accuracy compared to Convolutional LSTM**. 

## Author

Snehal Gullapudi

