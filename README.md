# Classification-Model-For-Iris-Dataset
# Iris Classification Model in Google Colab

This project implements a classification model using the famous Iris dataset. The model is built using TensorFlow and Keras, and includes functionality for training, evaluation, and making predictions with user input. The entire project is contained in a single Google Colab notebook.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Setup](#setup)
3. [Project Structure](#project-structure)
4. [Usage](#usage)
5. [Model Details](#model-details)
6. [Results](#results)
7. [Future Improvements](#future-improvements)

## Project Overview

This project follows these main steps:
1. Loading the Iris dataset
2. Exploring and performing correlation analysis on the dataset
3. Creating a classification model using TensorFlow and Keras
4. Training and evaluating the model
5. Implementing a prediction system that takes user input

## Setup

This project is implemented in Google Colab, which provides a ready-to-use environment with most required libraries pre-installed. However, you may need to install or upgrade some libraries. You can do this directly in the notebook using:

```python
!pip install -q sklearn
!pip install tensorflow==2.15
```

## Project Structure

The entire project is contained within a single Google Colab notebook. The notebook is structured into sections corresponding to each step of the process:

1. Data Loading and Preprocessing
2. Data Exploration and Correlation Analysis
3. Model Definition
4. Model Training and Evaluation
5. User Input Prediction System

## Usage

To use this project:

1. Open the Google Colab notebook.
2. Run each cell in order from top to bottom.
3. When you reach the prediction system, you can enter your own data to get predictions.

You can also modify the code cells to experiment with different model architectures or hyperparameters.

## Model Details

The classification model is a Deep Neural Network (DNN) with the following architecture:
- Input layer: 4 nodes (corresponding to the 4 features of the Iris dataset)
- Hidden layer 1: 30 nodes with ReLU activation
- Hidden layer 2: 10 nodes with ReLU activation
- Output layer: 3 nodes with Softmax activation (corresponding to the 3 Iris species)

The model is compiled with:
- Optimizer: Adam
- Loss function: Sparse Categorical Crossentropy
- Metric: Accuracy

## Results

- Training loss averaging around 0.0735
- Training Accuracy averaging around 0.9833
- Evaluation loss: 0.0768
- Evalation Accuracy: 0.9333

## Future Improvements

- Experiment with different model architectures
- Implement cross-validation
- Try other classification algorithms for comparison
- Create a web interface for the prediction system
- Export the model for use in other environments

Feel free to copy and modify this notebook for your own projects or experiments.
