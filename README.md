# Bone Fracture Detection Using X-rays

This repository contains the code and resources for detecting bone fractures using X-ray images. The project leverages convolutional neural networks (CNNs) to classify X-ray images as fractured or non-fractured. The dataset used for this project includes images of different joints in the upper extremities and can be found on Kaggle.

## Dataset

The dataset used for this project is available on Kaggle: [Bone Fracture Detection Dataset](https://www.kaggle.com/datasets/vuppalaadithyasairam/bone-fracture-detection-using-xrays).

### Key Features of the Dataset:
- Contains X-ray images of different joints in the upper extremities.
- The dataset already includes augmented images to improve model performance.

## Project Overview

The main steps of this project are:
1. Data preprocessing using `ImageDataGenerator` for rescaling and preparing training, validation, and testing datasets.
2. Building a Convolutional Neural Network (CNN) model with convolutional layers and max pooling layers.
3. Training the model on the dataset.
4. Evaluating the model's performance on training, validation, and test datasets.

## Results

- **Training Accuracy**: 98.27%
- **Validation Accuracy**: 96.59%
- **Test Accuracy**: 95.60%

## Model Architecture

The CNN model was designed using the following components:
- Multiple convolutional layers with ReLU activation.
- Max pooling layers to reduce dimensionality.
- Fully connected dense layers for classification.
- Sigmoid activation function for the output layer.

## Acknowledgements

- [Kaggle](https://www.kaggle.com) for providing the dataset.
- TensorFlow and Keras teams for their incredible deep learning frameworks.
