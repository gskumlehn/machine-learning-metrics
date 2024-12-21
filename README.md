# Machine Learning Metrics Challenge

This repository contains a set of scripts developed to demonstrate the calculation of machine learning metrics, such as Sensitivity, Specificity, Accuracy, Precision, and F-Score, from the confusion matrix, using the MNIST dataset.

## Objective

The goal of this repository is to apply and demonstrate the understanding of evaluation metrics for classification models, using the MNIST dataset. The model is trained to classify images of handwritten digits, and after training, the evaluation metrics are calculated from the confusion matrix.

## Repository Structure

1. **Main Script (metrics.ipynb)**: This script implements the creation and training of a simple neural network model using Keras. After training, the confusion matrix is generated, and from it, the evaluation metrics are extracted for each class.

2. **Process Description**:
    - **Data Preprocessing**: Loading and normalizing the MNIST dataset.
    - **Model Building**: A neural network with dense layers is built and trained using Keras.
    - **Metric Calculation**: The confusion matrix is generated to evaluate the model's performance. Then, Sensitivity, Specificity, Accuracy, Precision, and F-Score metrics are calculated for each class, using pure Python.

## How to Use

1. Open the `metrics.ipynb` file in Google Colab or your local Jupyter environment.
2. Run the cells to train the model and calculate the evaluation metrics.
3. The results will be presented with the metrics calculated for each class in the MNIST dataset.
