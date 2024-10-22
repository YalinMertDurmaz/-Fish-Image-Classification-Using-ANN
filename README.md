# Fish Image Classification Using Artificial Neural Network (ANN)

## Overview

This project focuses on classifying different species of fish using an Artificial Neural Network (ANN) model. The dataset used for this project is the [Large-Scale Fish Dataset](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset). The goal of this project is to develop a model that accurately identifies various types of fish based on their images and to provide detailed performance metrics through a classification report and visualizations.

## Table of Contents

* [Overview](#overview)
* [Dataset](#dataset)
* [Model Architecture](#model-architecture)
* [Installation](#installation)
* [Usage](#usage)
* [Training and Validation](#training-and-validation)
* [Evaluation](#evaluation)
* [Results](#results)
* [Conclusion](#conclusion)

## Dataset

The dataset contains images of various fish species, including:

* Black Sea Sprat
* Gilt-Head Bream
* Hourse Mackerel
* Red Mullet
* Shrimp
* Striped Red Mullet
* Trout

The images are divided into training, validation, and test sets to ensure the model can generalize well to new data.

## Model Architecture

The model used in this project is a fully connected ANN. The architecture includes:

* Flatten Layer for input images
* Multiple Dense Layers with ReLU activation
* Dropout layers for regularization
* Batch normalization to stabilize the training process
* Softmax output layer to classify the fish species

## Installation

To run this project locally, clone the repository and ensure the following libraries are installed:

```bash
git clone https://github.com/YOUR_USERNAME/Fish-Image-Classification-ANN.git
cd Fish-Image-Classification-ANN
pip install tensorflow pandas matplotlib seaborn scikit-learn

