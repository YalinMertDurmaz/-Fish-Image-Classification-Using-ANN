# Fish Image Classification Using ANN

This project implements an Artificial Neural Network (ANN) model to classify various fish species using images from the Large-Scale Fish Dataset. The primary objective is to achieve high accuracy in classifying these images, ultimately aiding in the study and conservation of aquatic biodiversity.

## Development Environment

- **Platform:** Kaggle
- **Programming Language:** Python
- **Libraries Used:**
  - TensorFlow
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-Learn

## Project Overview

The notebook is structured with the following sections:

1. **Importing Necessary Libraries:** Load essential libraries for data handling, model creation, and visualization.
2. **Data Preparation:** Extract image paths and labels from the dataset, ensuring to exclude ground truth images.
3. **Visualizing Sample Images and Class Distribution:** Display sample images and the distribution of classes to assess class balance.
4. **Data Splitting and Augmentation:** Split the dataset into training and testing sets, applying image augmentation techniques.
5. **Building the ANN Model:** Construct an ANN model with multiple dense layers, including dropout and batch normalization.
6. **Model Compilation and Training:** Compile the model using the Adagrad optimizer and train it while implementing early stopping and learning rate scheduling.
7. **Training and Validation Results Visualization:** Visualize training and validation loss and accuracy over epochs.
8. **Model Evaluation on Test Set:** Evaluate model performance on the test set and display confusion matrix and classification report.

## Results

- **F1 Score:** 0.9666
- **Accuracy:** 0.9671
- **Loss:** 1.4024
- **Precision:** 0.9672
- **Recall:** 0.9663

### Classification Report:

| Species               | Precision | Recall | F1-Score | Support |
|-----------------------|-----------|--------|----------|---------|
| Black Sea Sprat       | 0.96      | 1.00   | 0.98     | 211     |
| Gilt-Head Bream       | 0.98      | 0.97   | 0.97     | 204     |
| Hourse Mackerel       | 0.98      | 1.00   | 0.99     | 195     |
| Red Mullet            | 0.99      | 0.99   | 0.99     | 191     |
| Red Sea Bream         | 0.99      | 0.98   | 0.98     | 201     |
| Sea Bass              | 0.98      | 0.95   | 0.96     | 179     |
| Shrimp                | 0.99      | 0.98   | 0.98     | 209     |
| Striped Red Mullet    | 0.99      | 1.00   | 0.99     | 207     |
| Trout                 | 0.95      | 0.94   | 0.95     | 203     |
| **Accuracy**          |           |        | **0.98** | 1800    |
| **Macro Avg**         | 0.98      | 0.98   | 0.98     | 1800    |
| **Weighted Avg**      | 0.98      | 0.98   | 0.98     | 1800    |

## Kaggle Notebook Link

You can access the notebook [here](https://www.kaggle.com/code/yalnmertdurmaz/fish-image-classification-using-artificial-neural?scriptVersionId=202722162).

