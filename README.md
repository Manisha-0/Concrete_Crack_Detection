
# Concrete Crack Detection using CNN

This project aims to detect cracks in concrete surfaces using a Convolutional Neural Network (CNN). It was developed as a final project for the CMPS6720-1 course.

## Project Description

Manual inspection of cracks in concrete structures is time-consuming and prone to error. This project uses a CNN to classify images into "crack" and "no crack" categories, automating the inspection process.

## Dataset

- Source: Kaggle (Concrete Crack Images for Classification)
- Total Images: 40,000
- Classes: Crack / No Crack
- The dataset was divided into training, validation, and testing sets.

## Model

- CNN built using TensorFlow and Keras
- Input image size: 224x224
- Layers: Convolutional, MaxPooling, Flatten, Dense
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Batch size: 32
- Epochs: 10

## Results

- Test Accuracy: 98.95%
- AUC: 1.00
- The model performs well on unseen data with minimal misclassification.

## Files Included

- Python source code: `cmps6720_1_final_project.py`
- Evaluation plots: confusion matrix, ROC curve, accuracy/loss graph
- Sample prediction outputs


## How to Run

1. Install dependencies:
- tensorflow>=2.10
- numpy>=1.21
- matplotlib>=3.4
- pandas>=1.3
- scikit-learn>=1.0
- seaborn>=0.11
- Pillow>=8.0

## Reference

Dataset: https://www.kaggle.com/datasets/arnavr10880/concrete-crack-images-for-classification

