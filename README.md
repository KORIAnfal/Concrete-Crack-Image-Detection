# Concrete Crack Image Detection

This repository contains a model and script for detecting cracks in concrete images using TensorFlow and Keras. The model was trained using a dataset of concrete images with and without cracks, providing an effective tool for automated crack detection.

## Project Overview

This project utilizes two different neural network architectures:

1. **Pre-trained MobileNetV2**: The base model, MobileNetV2, is employed for its efficiency and accuracy in feature extraction. It is fine-tuned to suit the concrete crack detection task.
2. **Custom Convolutional Neural Network (CNN)**: A custom-designed CNN model is also implemented to compare performance with the pre-trained model.

## Dataset

The dataset used for training and testing the models was sourced from [Kaggle](https://www.kaggle.com/datasets/arnavr10880/concrete-crack-images-for-classification). It includes 40,000 images, split into two classes: Negative and Positive .

## Model Performance

- **MobileNetV2-based Model**:
  - Achieved a validation accuracy of 99.81% after 5 epochs.

- **Custom CNN Model**:
  - Achieved a validation accuracy of 51.00% after 5 epochs.


