# Task 3: Car Price Prediction with Machine Learning

## Objective

The objective of this project is to build a machine learning regression
model that predicts the selling price of a used car based on features
such as brand, car age, engine size, mileage, fuel type, transmission,
condition, and model.

---

## Dataset

The dataset contains information about used cars and their selling prices.

### Main Features

- Car ID
- Brand
- Year
- Engine Size
- Fuel Type
- Transmission
- Mileage
- Condition
- Price
- Model

The dataset contains **2,500 car records** and **10 original columns**.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Project Workflow

The project follows these steps:

1. Load the car price dataset
2. Explore the dataset
3. Check data types and missing values
4. Remove duplicate records
5. Clean and standardize categorical values
6. Perform feature engineering
7. Conduct Exploratory Data Analysis (EDA)
8. Encode categorical variables
9. Create training and testing datasets
10. Train regression models
11. Evaluate model performance
12. Compare the models
13. Identify the best-performing model
14. Analyze feature importance

---

## Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent categorical values

Categorical values such as brand, fuel type, transmission, and condition
were standardized to maintain consistency.

---

## Feature Engineering

A new feature called **Car Age** was created from the `Year` column.

The calculation is:

```text
Car Age = Current Year - Manufacturing Year
