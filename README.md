# Image Classification with VGG16

## Overview

This project applies image enhancement techniques to improve the classification of chest X-ray images using a deep learning model (VGG16).

## Dataset

- **Source**: [Chest X-ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Content**: The dataset includes X-ray images labeled as either 'Normal' or 'Pneumonia' from patients.

## Project Structure


1. **[image_without.ipynb](https://github.com/majdfo/majdfo-image-processing-project/blob/main/image_without.ipynb)**: 
2. **[image_with_enhance.ipynb](https://github.com/majdfo/majdfo-image-processing-project/blob/main/image_with_enhance.ipynb)**: 

## Objective

- **Train VGG16** on original and enhanced chest X-ray images.
- **Compare Results** to assess the effect of image enhancement on accuracy.

## Steps

1. **Preprocessing**: Resize images and apply enhancement techniques.
2. **Model Training**: Use VGG16 for image classification.
3. **Evaluation**: Compare accuracy, precision, recall, and F1-score between the two approaches.

## Results and Insights

- Initial results showed improvements in classification accuracy with enhanced images using techniques like CLAHE and Sobel filtering.
