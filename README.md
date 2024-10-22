# Fish Image Classification Using ANN

This project implements an Artificial Neural Network (ANN) model to classify different species of fish using images from the Large-Scale Fish Dataset. The goal is to achieve high accuracy in classifying images of various fish species.

## Dataset
- **Source**: [Large-Scale Fish Dataset](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset/data)
- **Total Rows**: 9000 images
- **Classes**: 9 species of fish

## Model Structure
- Input Layer: Flatten
- Hidden Layers:
  - Dense (1024 units, ReLU, L2 regularization)
  - Batch Normalization
  - Dropout (0.2)
  - Dense (512 units, ReLU, L2 regularization)
  - Batch Normalization
  - Dense (256 units, ReLU, L2 regularization)
  - Dropout (0.2)
  - Dense (128 units, ReLU, L2 regularization)
  - Dense (64 units, ReLU, L2 regularization)
  - Dropout (0.2)
- Output Layer: Dense (9 units, Softmax)

## Required Libraries
- TensorFlow
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Results
- **F1 Score**: 0.9666
- **Accuracy**: 0.9671
- **Loss**: 1.4024
- **Precision**: 0.9672
- **Recall**: 0.9663

### Classification Report
- Black Sea Sprat: Precision: 0.96, Recall: 1.00, F1-score: 0.98
- Gilt-Head Bream: Precision: 0.98, Recall: 0.97, F1-score: 0.97
- Hourse Mackerel: Precision: 0.98, Recall: 1.00, F1-score: 0.99
- Red Mullet: Precision: 0.99, Recall: 0.99, F1-score: 0.99
- Red Sea Bream: Precision: 0.99, Recall: 0.98, F1-score: 0.98
- Sea Bass: Precision: 0.98, Recall: 0.95, F1-score: 0.96
- Shrimp: Precision: 0.99, Recall: 0.98, F1-score: 0.98
- Striped Red Mullet: Precision: 0.99, Recall: 1.00, F1-score: 0.99
- Trout: Precision: 0.95, Recall: 0.94, F1-score: 0.95

## Link to Kaggle Notebook
- [Kaggle Notebook](https://www.kaggle.com/code/yalnmertdurmaz/fish-image-classification-using-artificial-neural?scriptVersionId=202722162)
