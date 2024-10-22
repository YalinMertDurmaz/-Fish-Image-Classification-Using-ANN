# Fish Image Classification Using ANN

This project implements an Artificial Neural Network (ANN) model to classify various fish species using images from the Large-Scale Fish Dataset. The primary objective is to achieve high accuracy in classifying these images, ultimately aiding in the study and conservation of aquatic biodiversity.

## Development Environment

- **Platform:** Kaggle
- **Programming Language:** Python
- **Libraries Used:** TensorFlow, Pandas, Matplotlib, Seaborn, Scikit-Learn

### Notes:
- It is recommended to develop the project directly on Kaggle due to the large dataset size (approximately 3GB).
- While other platforms like Google Colab can be used, the final notebook must be hosted on Kaggle.

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
