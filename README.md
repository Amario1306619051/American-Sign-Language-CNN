# Convolutional Neural Networks for Image Classification

<div style="text-align:center">
    <img src="./cnn.png" width="180" />
</div>

## Overview
This repository contains code and resources for implementing Convolutional Neural Networks (CNNs) to classify images of American Sign Language (ASL) letters. The goal is to build and train a CNN model that can accurately recognize ASL letters from images.

## Objectives
- Prepare image data specifically for CNNs.
- Create a more sophisticated CNN model, utilizing a variety of CNN layers.
- Train the CNN model and evaluate its performance.

## Dataset
The [American Sign Language alphabet](http://www.asl.gs/) consists of 26 letters. However, letters 'j' and 'z' are excluded from the dataset as they involve movement. The dataset contains grayscale images of hands forming ASL letters.

### Loading and Preparing Data
The dataset is loaded from CSV files, and the images are normalized and reshaped to fit a CNN architecture.

## CNN Architecture
The CNN model consists of various layers:
- Convolutional Layers (Conv2D) to detect features in the images.
- Batch Normalization to scale hidden layer values.
- Max Pooling Layers (MaxPool2D) to reduce image dimensions.
- Dropout Layers to prevent overfitting.
- Flatten Layer to convert 2D features into a 1D vector.
- Dense Layers for classification.

### Model Summary
The model architecture and summary are provided in the repository. It's designed to improve performance compared to the previous simple model.

## Training and Results
The model is compiled and trained using the training data. Training accuracy is high, and the validation accuracy improves compared to the previous model. However, there's still room for improvement in terms of generalization.

## Next Steps
While this repository covers CNN implementation, it's important to address issues like overfitting and optimize the model further. Future steps could involve exploring more advanced CNN architectures and techniques.

Feel free to explore the code and resources provided to understand the process of building and training CNNs for image classification using the American Sign Language dataset.

**Note**: Before moving to the next notebook or section, clear GPU memory using the provided code snippet.

