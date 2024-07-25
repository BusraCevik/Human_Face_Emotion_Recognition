# Emotion Recognition Using CNN

This repository contains the code and resources for my final year project titled "Yapay Zeka ile İnsan Yüzünde Duygu Tanıma" (Emotion Recognition Using AI on Human Faces). The project aims to develop a model that can recognize 7 different emotions from facial expressions using Convolutional Neural Networks (CNN).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training and Evaluation](#training-and-evaluation)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

Emotion recognition from facial expressions is a crucial aspect of human-computer interaction, with applications in security, healthcare, and personalized experiences. This project leverages deep learning techniques, specifically CNNs, to accurately identify emotions such as happiness, sadness, surprise, fear, anger, disgust, and neutrality from facial images.

## Features

- Emotion recognition for 7 different emotions
- High accuracy achieved using deep learning
- Data preprocessing and augmentation techniques
- Detailed model training and evaluation scripts

## Dataset

The dataset used in this project is the FER2013 dataset, which consists of 35,887 grayscale images, each 48x48 pixels, representing 7 different emotions:

- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

The dataset is split into training and test sets, with 28,709 images for training and 7,178 images for testing.

## Model Architecture

The model is based on Convolutional Neural Networks (CNN), which are well-suited for image recognition tasks. The architecture includes multiple convolutional layers, pooling layers, and fully connected layers to learn and classify the emotions from facial expressions.

## Training and Evaluation

- Data preprocessing includes normalization and augmentation to enhance the training process.
- The model is trained using Google Colab, taking advantage of its GPU capabilities to handle the large dataset.
- Training and validation metrics are monitored to ensure the model's performance.
- Evaluation metrics include accuracy, precision, recall, and confusion matrix.

## Results

The model achieved an overall accuracy of 80% in emotion recognition. The performance for specific emotions like happiness, sadness, and anger showed particularly high accuracy.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/emotion-recognition-cnn.git
   cd emotion-recognition-cnn
