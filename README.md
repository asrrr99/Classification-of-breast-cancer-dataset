# Classification-of-breast-cancer-dataset
## Objective

To build a model that can accurately predict the species of an iris flower.

Target classes:

* Setosa
* Versicolor
* Virginica

---

## Dataset Information

The dataset is loaded using the *Seaborn library* and contains:

* *150 rows*
* *5 columns*

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target

* Species

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Import Libraries

Imported all required libraries for data analysis, visualization, and machine learning.

### 2. Data Collection

Loaded the Iris dataset from Seaborn.

### 3. Data Cleaning & Preprocessing

Performed:

* Missing value checking
* Duplicate checking and removal
* Data type verification
* Outlier detection and handling using IQR method
* Feature scaling using StandardScaler

### 4. Data Visualization

Used:

* Boxplots
* Heatmaps
* Scatterplots

### Key Insights

* Petal Length and Petal Width show a very strong positive correlation
* Setosa is clearly separable from the other species
* Sepal Width shows some outliers which were handled during preprocessing

### 5. Model Building

Used:

* Train-Test Split (80:20)
* Logistic Regression Classifier

### 6. Model Evaluation

Evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 7. Prediction on New Data

Tested the model using new unseen flower measurements.

---

## Results

The model achieved excellent classification performance with highly accurate predictions.

### Key Observation

The confusion matrix showed perfect or near-perfect classification with predictions correctly placed on the diagonal.

This indicates the model performs very well for Iris species classification.

---

## Conclusion

This project successfully demonstrates how Machine Learning can be used to classify iris flower species based on flower measurements.

From data loading to final prediction, the complete workflow was implemented clearly and effectively.

The Logistic Regression model performed very well and proved to be a strong choice for this classification task.

---

## Author

Project developed as part of Data Science learning and practice using Python and Machine Learning concepts.
