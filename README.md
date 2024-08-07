# Iris-Detection Project

## Overview
This project focuses on detecting and estimating the position of the iris using deep learning techniques. The project is divided into two main parts: Data Collection and Iris Estimation.

## Data Collection
The Data Collection phase involves gathering images and preparing them for training. Key steps include:
1. **Image Collection**: Capturing images using a webcam and saving them.
2. **Annotation**: Using Labelme to annotate the images with key points for the left and right eyes.
3. **Dataset Creation**: Organizing the annotated images into training, testing, and validation sets.
4. **Image Augmentation**: Applying various augmentations to increase the diversity of the dataset.

## Iris Estimation
The Iris Estimation phase involves building and training a deep learning model to predict the iris position. Key steps include:
1. **Data Loading**: Loading and preprocessing images and their corresponding labels.
2. **Model Building**: Creating a neural network using TensorFlow and Keras, with ResNet152V2 as the backbone.
3. **Training**: Training the model on the prepared dataset.
4. **Evaluation**: Testing the model and visualizing the results.

## Installation
To run the project, ensure you have the following dependencies installed:
- TensorFlow
- OpenCV
- Matplotlib
- Albumentations
- Labelme

## Usage
1. **Data Collection**: Run the `DataCollection.ipynb` notebook to collect and prepare the dataset.
2. **Iris Estimation**: Run the `IrisEstimation.ipynb` notebook to train and evaluate the model.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

