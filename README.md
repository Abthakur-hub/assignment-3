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
## Dataset

**Dataset Name:** Position Salaries Dataset

**Source:** https://www.kaggle.com/datasets/akram24/position-salaries

The dataset contains salary information for different employee position levels. It is used to demonstrate Polynomial Regression for predicting salary based on position level.

**Input Feature (X):**
- Level

**Target Variable (y):**
- Salary

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

<img width="726" height="494" alt="Screenshot 2026-07-22 at 9 58 34 PM" src="https://github.com/user-attachments/assets/e0b18fd4-0a71-4a34-837c-c5a56c22e4ee" />


---

### 2. Polynomial Regression Curve

This figure shows the fitted **Polynomial Regression** model along with the original data points, illustrating the nonlinear relationship between position level and salary.

<img width="719" height="489" alt="Screenshot 2026-07-22 at 9 58 46 PM" src="https://github.com/user-attachments/assets/3ade22d7-c4df-4ab1-8061-683fdd6b9732" />


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

