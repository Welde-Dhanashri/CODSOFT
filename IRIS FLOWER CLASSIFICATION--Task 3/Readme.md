# Iris Flower Classification

## Overview
- This project works on classifying iris flowers into three different species using machine learning techniques.
- The dataset consists of four features: sepal length, sepal width, petal length, and petal width.

## Dataset
- The dataset used for the classification task is the famous **Iris dataset**, containing 150 samples with about 50 samples per species.
- The features in the dataset include:
  - **Sepal Length (cm)**
  - **Sepal Width (cm)**
  - **Petal Length (cm)**
  - **Petal Width (cm)**
  - **Species (Target Variable)**
- The dataset shape is **(150, 5)**, indicating 150 rows and 5 columns (4 features + target variable).


<p align="center">
  <img src="https://github.com/Welde-Dhanashri/CODSOFT/blob/main/IRIS%20FLOWER%20CLASSIFICATION--Task%203/iris1.jpg?raw=true" width="30%" alt="iris1">
  <img src="https://github.com/Welde-Dhanashri/CODSOFT/blob/main/IRIS%20FLOWER%20CLASSIFICATION--Task%203/iris2.jpg?raw=true" width="30%" alt="Correlation Heatmap">
  <img src="https://github.com/Welde-Dhanashri/CODSOFT/blob/main/IRIS%20FLOWER%20CLASSIFICATION--Task%203/Pairplot%20image.png?raw=true" width="30%" alt="Confusion Matrix">
</p>


## Project Workflow
### 1. Data Loading & Exploration
- Load the dataset using Pandas
- Check for missing values and basic statistics
- Visualize the data using Seaborn and Matplotlib

### 2. Data Preprocessing
- Transform the species feature labels into numerical values
- Perform correlation analysis
- Detect and handle outliers
- Split the dataset into training and test sets

### 3. Model Training
- Train a **K-Nearest Neighbors (KNN)** classification model
- Optimize hyperparameters
- Evaluate model performance using accuracy, precision, recall, and confusion matrix

### 4. Model Evaluation
- Measure performance metrics
- Visualize results using confusion matrix and classification reports

## Results
- The trained **KNN model** proved to be a powerful iris flower classifier.
- Model evaluation showed strong performance across experiment validations and measurements.
- Visualizations helped in understanding feature importance in predicting classification outcomes.



