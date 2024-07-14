# Brain Tumor Detection Model

## Overview

This project is a custom detection model using a convolutional neural network (CNN) built with TensorFlow and Keras. 
The model is designed to classify MRI images as either indicating the presence of a tumor or not. 
The dataset used for this project consists of a total of 253 MRI images, with 155 positive examples (tumor present) and 98 negative examples (tumor not present) sourced from Kaggle.

## Features

1. **Data Augmentation:** Expanded the dataset using data augmentation techniques, resulting in a total of 2317 MRI images.
2. **Cropping Technique:** Implemented a cropping technique to isolate the brain region from the MRI images.
3. **Custom CNN Architecture:** Developed a custom small CNN architecture suitable for the small dataset.
4. **Accuracy Achieved:** Initially achieved 88% accuracy on the test set.
5. **Addressed Overfitting:** Applied regularization techniques to address overfitting due to the small dataset, ultimately achieving 93% accuracy.

## Dataset

The original dataset used in this project consists of:
- 155 positive examples (tumor present)
- 98 negative examples (tumor not present)

After applying data augmentation, the dataset size increased to 2317 MRI images.

## Steps Followed

1. **Data Augmentation:**
   - Various augmentation techniques such as rotation, flipping, and zooming were applied to increase the dataset size.
   
2. **Cropping Technique:**
   - A technique was used to crop the MRI images to focus only on the brain region, improving the model's performance.

3. **Custom CNN Architecture:**
   - Developed a small custom CNN architecture tailored to the small dataset, achieving notable initial results.

4. **Regularization:**
   - Applied regularization techniques to reduce overfitting, leading to improved accuracy on the test set.

## Results

- **Initial Accuracy:** 88% on the test set.
- **Final Accuracy:** 93% on the test set after applying regularization techniques.

## Model Architecture

The custom CNN architecture includes the following layers:

- Convolutional layers
- Max-pooling layers
- Dropout layers
- Dense (fully connected) layers

## Technologies Used

- **TensorFlow:** An open-source platform for machine learning.
- **Keras:** An open-source software library that provides a Python interface for artificial neural networks.
- **Python:** The programming language used for the implementation.
- **Jupyter Notebook:** Used for development and experimentation.

