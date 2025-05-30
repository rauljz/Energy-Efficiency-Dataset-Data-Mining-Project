# Energy-Efficiency-Dataset-Data-Mining-Project

This project focuses on **predicting the energy efficiency of buildings** using classical regression algorithms from the `scikit-learn` library, based on the [Energy Efficiency Dataset](https://archive.ics.uci.edu/ml/datasets/energy+efficiency) from the UCI Machine Learning Repository.

---

## 📘 Project Description

The objective of this project is to:

- Apply standard **data preprocessing techniques** suitable for regression problems.
- Explore and implement a variety of **classical regression algorithms** using `scikit-learn`, such as:
  - Linear Regression
  - Ridge and Lasso Regression
  - Decision Trees
  - k-Nearest Neighbors
  - Support Vector Regression
- Analyze the **effect of hyperparameters** on model performance using techniques such as:
  - Grid Search
  - Cross-Validation
- Compare the performance of different models based on metrics like:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score
- Select the **most suitable model** for predicting the energy efficiency indicators of buildings:
  - Heating Load
  - Cooling Load

---

## 📊 Dataset Overview

The dataset consists of 768 samples and 8 input features describing the characteristics of buildings, such as:

- Relative Compactness
- Surface Area
- Wall Area
- Roof Area
- Overall Height
- Orientation
- Glazing Area
- Glazing Area Distribution

The outputs are two continuous variables:

- **Heating Load (Y1)**
- **Cooling Load (Y2)**

---

## 🛠️ Technologies Used

- Python 3.x
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn (for visualization)

---
