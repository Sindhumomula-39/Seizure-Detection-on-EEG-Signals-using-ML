# Seizure-Detection-on-EEG-Signals-using-ML
## Project Overview

This project focuses on the automatic classification of EEG (Electroencephalogram) signals using a 1D Convolutional Neural Network (CNN). The system analyzes raw EEG signals and classifies them into five different classes: F, N, O, S, and Z.

The EEG dataset consists of raw signal recordings stored as `.txt` files. The signals are preprocessed, normalized, and reshaped before being provided to the CNN model for classification.
## Objectives

- Classify raw EEG signals into five categories.
- Develop a 1D CNN model for EEG classification.
- Evaluate model performance using multiple metrics.
- Analyze model generalization using K-Fold cross-validation.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Results

The developed CNN model achieved approximately **86% test accuracy** on the EEG dataset.

## Dataset

The project uses the **EEG Dataset** from Kaggle:

`quands/eeg-dataset`

## Evaluation

The model performance is analyzed using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score
- K-Fold Cross-Validation
- ROC Curve and AUC

## Future Scope

Future improvements can include experimenting with different CNN architectures, advanced EEG preprocessing techniques, hyperparameter tuning, and larger EEG datasets to improve model generalization.
