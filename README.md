# Image Classification using SVM (Cats vs Dogs)

## Description

This project implements a Support Vector Machine (SVM) model for binary image classification to distinguish between cats and dogs. The approach relies on classical machine learning with feature extraction techniques to achieve reliable classification performance.

## Objective

To build an effective image classification system using SVM combined with handcrafted feature extraction methods such as HOG descriptors or color histograms.

## Dataset

Source: Kaggle – Dogs vs. Cats Dataset
[https://www.kaggle.com/competitions/dogs-vs-cats](https://www.kaggle.com/competitions/dogs-vs-cats)

The dataset contains a large collection of labeled cat and dog images for training and evaluation.

## Workflow

* Image loading and preprocessing
* Feature extraction using HOG descriptors or color histograms
* Training SVM models with linear and RBF kernels
* Model evaluation using accuracy score and confusion matrix

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install required dependencies:

   ```bash
   pip install numpy pandas scikit-learn opencv-python matplotlib
   ```
3. Download the dataset from Kaggle and extract it into the project directory.
4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
5. Run the notebook cells sequentially to preprocess data, train the model, and evaluate results.

## Results

The model achieved strong class separation between cats and dogs, with high accuracy on the test dataset.

## Tech Stack

* Python (NumPy, Pandas, Scikit-learn)
* OpenCV
* Matplotlib
* Jupyter Notebook

## Future Enhancements

* Integrate CNN-based feature extraction
* Apply hyperparameter tuning using Grid Search or Random Search
* Experiment with different kernels and feature combinations
