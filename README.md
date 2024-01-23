# Cats vs. Dogs Image Classification with SVM

This project implements an image classification model using Support Vector Machine (SVM) to classify images of cats and dogs from the Kaggle dataset.

## Dataset

The dataset used for this project is the [Cats vs. Dogs dataset on Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data). Download the dataset and organize it into the required directory structure.


## Requirements

Make sure you have the following dependencies installed:

- numpy
- opencv-python
- scikit-learn
- joblib
- matplotlib

Install dependencies using:

```bash
pip install numpy opencv-python scikit-learn joblib matplotlib

Usage
Update the data_dir variable in the Jupyter Notebook with the path to your dataset.
Run the Jupyter Notebook cells to load, preprocess, train the SVM model, and make predictions.
View the accuracy and visualize predictions.
Files
svm_image_classification.ipynb: Jupyter Notebook containing the SVM image classification code.
svm_model.pkl: Saved SVM model after training.
