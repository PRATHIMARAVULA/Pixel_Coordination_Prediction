## Pixel Coordinate Prediction using CNN
## Problem Statement

This project predicts the (x, y) coordinates of a single bright pixel (value 255) in a 50×50 grayscale image where all other pixels are 0.

## Dataset Rationale

A synthetic dataset is generated programmatically to ensure:

Controlled environment

Uniform distribution of pixel locations

Sufficient training data

Reproducibility

Each image contains exactly one bright pixel placed randomly.

Model Used

## Convolutional Neural Network (CNN)

Regression approach

## Loss Function: Mean Squared Error (MSE)

## Results

The model successfully learned spatial localization.
Predicted coordinates closely align with ground truth values.

## Installation

Install dependencies:

pip install -r requirements.txt

## Then run the notebook using:

jupyter notebook

