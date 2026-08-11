# Chihuahua or Muffin with CNN

## Project Overview

This project explores image classification using a Convolutional Neural Network (CNN). The goal was to train a computer vision model to distinguish between images of Chihuahuas and muffins, two classes that can sometimes have surprisingly similar visual features.

## Problem Statement

Image classification requires a model to identify meaningful visual patterns such as shapes, textures, edges, and colors. This project demonstrates how a CNN can learn those features directly from image data and use them to classify new images.

## Approach

The project uses a CNN-based image classification workflow that includes:

- Loading and preparing image data
- Preprocessing images for model input
- Building a CNN architecture
- Training the model
- Evaluating model performance
- Reviewing predictions and results

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab
- Convolutional Neural Networks (CNN)

## Dataset

This project uses the **Chihuahua vs. Muffin image dataset** provided with the workshop repository used in the lab.

The dataset is not stored separately in this portfolio repository.

**Dataset source:**  
https://github.com/patitimoner/workshop-chihuahua-vs-muffin

The dataset can be accessed by cloning the repository:

git clone https://github.com/patitimoner/workshop-chihuahua-vs-muffin.git

The notebook loads the training and validation images using `torchvision.datasets.ImageFolder()` from the `data/train` and `data/validation` directories.

## Results

The completed notebook contains the training and evaluation results produced during the lab, including model outputs and visualizations.

Rather than only looking at whether the code ran, I reviewed how well the CNN learned to distinguish between the two visually similar classes.

## Key Findings

This project helped me understand how CNNs learn image features differently from traditional machine learning approaches.

It also showed me how preprocessing, model architecture, training, and evaluation all contribute to the final performance of an image classification system.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Run the setup and import cells.
3. Load the required image dataset.
4. Run the preprocessing cells.
5. Build and train the CNN.
6. Run the evaluation and prediction cells.
7. Review the outputs and visualizations.
