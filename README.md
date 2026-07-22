# assignment-3

Polynomial Regression for Salary Prediction using Scikit-learn

---

## Student Information

| Details | Information |
|---------|-------------|
| **Name** | Abhishek Thakur |
| **Registration Number** | 23MIM10078 |
| **Application Number** | IN26011189 |
| **Batch** | 1A |

---

## Project Overview

This assignment implements a **Polynomial Regression** model to predict employee salaries based on their position level. The Position Salaries dataset is used to understand the nonlinear relationship between position level and salary. The model is developed using **Polynomial Features (Degree = 3)** along with **Linear Regression**, which together form the Polynomial Regression model.

---

## Objectives

- Load and understand the dataset.
- Perform data preprocessing.
- Transform the input feature using Polynomial Features (Degree = 3).
- Train a Polynomial Regression model.
- Predict salaries for the test dataset.
- Evaluate the model using regression metrics.
- Visualize the original data and the Polynomial Regression curve.

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset

**Dataset Name:** Position Salaries Dataset

**Features**

- Position
- Level
- Salary

**Input Feature (X)**

- Level

**Target Variable (y)**

- Salary

---

## Model

Polynomial Regression using:

- PolynomialFeatures (Degree = 3)
- LinearRegression

---

## Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Results

The Polynomial Regression model successfully captures the nonlinear relationship between position level and salary. The evaluation metrics indicate good predictive performance, and the fitted regression curve closely follows the trend of the original dataset.

---

## Conclusion

This project successfully demonstrates the implementation of Polynomial Regression for predicting employee salaries based on position level. By transforming the input feature using Polynomial Features (Degree = 3) and training a Linear Regression model on the transformed data, the model effectively captures the nonlinear relationship present in the dataset. The evaluation metrics, including MAE, MSE, and an R² Score of **0.8763**, indicate good predictive performance. Overall, Polynomial Regression proved to be an effective approach for modeling salary prediction on the given dataset.


---

## Screenshots

### 1. Scatter Plot of the Original Data

This figure shows the relationship between the employee **Position Level** and **Salary** in the original dataset.

![Scatter Plot of the Original Data](images/scatter_plot.png)

---

### 2. Polynomial Regression Curve

This figure shows the fitted **Polynomial Regression** model along with the original data points, illustrating the nonlinear relationship between position level and salary.

![Polynomial Regression Curve](images/polynomial_regression_curve.png)

---

## Repository Structure

```
Assignment-3/
│
├── Assignment-3.ipynb
├── README.md
└── .gitignore
```

---

