# **Solar Panel Energy Output Prediction Using Simple Linear Regression**

## **Introduction**

This project implements a **simple linear regression model** to predict the energy output of solar panels based on **ambient temperature**. A **synthetic dataset** with a linear relationship and random noise is used. The model is implemented using two approaches:

1. **Manual implementation using gradient descent**
2. **Using scikit-learn for performance comparison**

---

## **Dataset**

The synthetic dataset is generated randomly. Temperature values range between **10 to 40°C**, and energy output is calculated using the following equation:

```
Energy_Output = 2.5 * Temperature + 5 + noise
```

where **Gaussian noise** is added to simulate real-world variations.

---

## **Implementation Steps**

1. **Generating synthetic data**
2. **Exploratory Data Analysis (EDA)**
3. **Implementing simple linear regression using gradient descent**
4. **Training the model with scikit-learn and comparing results**
5. **Visualizing and evaluating the model**

---

## **Comparison of Both Methods**

✅ **Manual implementation using gradient descent**  
✅ **Using scikit-learn for training**

The results of both methods are compared based on **accuracy metrics (MSE, R²).**
