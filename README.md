# Task 1: Iris Flower Classification

## Objective

The objective of this project is to train a machine learning classification
model to identify iris flower species based on their physical measurements.

The project classifies flowers into three species:

- Setosa
- Versicolor
- Virginica

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## Dataset

The Iris dataset is directly available from `sklearn.datasets`, so no
external download is required.

The dataset contains 150 samples with four features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Project Workflow

1. Load the Iris dataset
2. Create a Pandas DataFrame
3. Perform Exploratory Data Analysis (EDA)
4. Check dataset shape and data types
5. Check for missing values
6. Generate descriptive statistics
7. Visualize feature distributions using pairplots
8. Create box plots for each feature
9. Analyze the most discriminative features
10. Split the dataset into training and testing sets
11. Scale the features
12. Train Logistic Regression
13. Train K-Nearest Neighbours (KNN)
14. Evaluate both models
15. Compare model performance
16. Select the best-performing model

## Exploratory Data Analysis

EDA was performed to understand the structure and distribution of the
dataset.

The analysis included:

- Dataset shape
- Data types
- Null value checking
- Descriptive statistics
- Species distribution
- Feature visualization

## Feature Selection

The visualizations showed that **petal length** and **petal width** are the
most discriminative features for distinguishing the three Iris species.

## Machine Learning Models

Two classification algorithms were trained:

### 1. Logistic Regression

Logistic Regression was used as the first classification model.

### 2. K-Nearest Neighbours (KNN)

KNN was used as the second classification model.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

## Results

The **K-Nearest Neighbours (KNN)** model achieved an accuracy of:

**96%**

KNN was therefore selected as the **best-performing model** for this
project.

## Conclusion

The project demonstrates that machine learning can effectively classify
Iris flowers based on their physical measurements. Among the two tested
models, KNN achieved the best performance with **96% accuracy**.

## Project Files

- `Iris_Flower_Classification.ipynb` - Complete Jupyter/Google Colab notebook
- `README.md` - Project documentation
