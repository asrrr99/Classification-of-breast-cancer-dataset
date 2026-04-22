# Breast-Cancer-Data-Analysis
## Project Overview

This project focuses on predicting breast cancer diagnosis using multiple Machine Learning classification algorithms. The dataset used is the Breast Cancer Wisconsin Dataset available from sklearn.datasets.

The main objective is to compare the performance of different classification models and identify the most accurate model for predicting whether a tumor is malignant or benign.

Technologies Used
* Python
* Pandas
* NumPy
Scikit-learn
Jupyter Notebook
Dataset Information

The project uses the built-in dataset:

from sklearn.datasets import load_breast_cancer

* Dataset Features
* 569 total samples
*  numerical input features
* Target variable:
* 0 → Malignant
* 1 → Benign

Examples of features include:

* Mean Radius
*Mean Texture
* Mean Perimeter
* Mean Area
* Mean Smoothness
* Worst Radius
* Worst Texture
* Worst Perimeter
* Project Workflow
## 1. Import Libraries

Essential libraries for data handling, preprocessing, model building, and evaluation are imported.

## 2. Load Dataset

The breast cancer dataset is loaded and converted into a Pandas DataFrame.

## 3. Data Preprocessing
* Duplicate values removed
* Null value checking
* Feature-target separation
## 4. Train-Test Split

Dataset is divided into:

* 80% Training Data
* % Testing Data
## 5. Feature Scaling

StandardScaler() is used for scaling features, especially for models like:

* Logistic Regression
* SVM
* KNN
## 6. Model Training

The following models are trained:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* 
## 7. Model Evaluation

Each model is evaluated using:

* accuracy_score()
* Machine Learning Models Used
* Logistic Regression

A statistical model used for binary classification problems.

* Decision Tree Classifier

A tree-based model that splits data based on feature importance.

* Random Forest Classifier

An ensemble learning method using multiple decision trees.

* Support Vector Machine (SVM)

A powerful classifier used for both linear and non-linear classification.

* K-Nearest Neighbors (KNN)

A distance-based classification algorithm.

* Expected Outcome

The project helps determine which machine learning model provides the best prediction accuracy for breast cancer diagnosis.

In most cases, Random Forest and Logistic Regression provide strong performance for this dataset.

## Conclusion

This project demonstrates how machine learning can support early breast cancer detection by improving diagnostic accuracy.

By comparing multiple classification algorithms, we can identify the most reliable model for medical prediction tasks. This improves decision-making and helps in building efficient healthcare solutions using data science.

Future Improvements

Possible enhancements include:

Hyperparameter tuning
Cross-validation
Confusion matrix analysis
Precision, Recall, and F1-score evaluation
ROC-AUC score comparison
Model deployment using Flask or Streamlit
Author

Project developed for Machine Learning practice and academic learning using Python and Scikit-learn.
