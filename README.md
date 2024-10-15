# Diabetes Prediction using Support Vector Machine (SVM)

This project is a Machine Learning model that predicts whether a pregnant woman has diabetes or not, using a Support Vector Machine (SVM) for classification. The dataset is sourced from Kaggle.

## Dataset

The dataset contains various features relevant to predicting diabetes among pregnant women. You can download it from Kaggle and place it in the `data/` directory of this repository.

## Project Overview

The steps involved in building the predictive model include:

- Data preprocessing and feature scaling using `StandardScaler`.
- Splitting the dataset into training and testing sets.
- Training the SVM model on the training data.
- Evaluating the model's performance using accuracy scores.

## Dependencies

The following Python libraries are required:

- `numpy`
- `pandas`
- `scikit-learn` (for `StandardScaler`, `train_test_split`, `SVM`, and `accuracy_score`)

To install the dependencies, run:

```bash
pip install numpy pandas scikit-learn
