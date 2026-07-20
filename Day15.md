## Day 15 — 20 July 2026

### Topics Covered

- Linear Regression
- Ridge Regression
- Lasso Regression
- Comparison of Linear, Ridge, and Lasso Regression
- Applications of Regression Models

---

### Learning Summary

#### Linear Regression

Linear Regression is a supervised machine learning algorithm used for predicting continuous numerical values. It establishes a linear relationship between one or more independent variables (features) and a dependent variable (target).

**Working of Linear Regression:**
1. Collect and preprocess the dataset.
2. Fit the best possible line to the training data.
3. Learn the relationship between input and output variables.
4. Use the trained model to predict continuous values for new data.

**Advantages:**
- Simple and easy to implement.
- Easy to interpret.
- Works well for linear relationships.

**Limitations:**
- Assumes a linear relationship between variables.
- Sensitive to outliers.
- Performance decreases when features are highly correlated.

---

#### Ridge Regression

Ridge Regression is an extension of Linear Regression that uses **L2 Regularization** to reduce overfitting. It adds a penalty term to the loss function, shrinking the coefficients but not reducing them to zero.

**Advantages:**
- Reduces overfitting.
- Handles multicollinearity effectively.
- Improves model generalization.

**Limitations:**
- Does not perform feature selection.
- All features remain in the model.

---

#### Lasso Regression

Lasso Regression is another regularized version of Linear Regression that uses **L1 Regularization**. It can reduce some feature coefficients to exactly zero, effectively performing feature selection.

**Advantages:**
- Performs automatic feature selection.
- Reduces model complexity.
- Helps prevent overfitting.

**Limitations:**
- May remove useful features if regularization is too strong.
- Performance depends on the choice of the regularization parameter.

---

### Comparison of Regression Models

| Linear Regression | Ridge Regression | Lasso Regression |
|-------------------|------------------|------------------|
| No regularization. | Uses L2 regularization. | Uses L1 regularization. |
| May overfit on complex data. | Reduces overfitting by shrinking coefficients. | Reduces overfitting and performs feature selection. |
| Keeps all features. | Keeps all features with smaller coefficients. | Can eliminate less important features by making coefficients zero. |

---

### Applications

- House price prediction.
- Sales forecasting.
- Stock price prediction.
- Demand forecasting.
- Business analytics.
- Financial analysis.

---

### Key Takeaways

- Learned the fundamentals of Linear Regression.
- Understood the purpose of regularization in regression models.
- Explored Ridge Regression using L2 regularization.
- Learned how Lasso Regression performs feature selection using L1 regularization.
- Compared Linear, Ridge, and Lasso Regression models.

---

### Reflection

Today's session focused on regression techniques used for predicting continuous values. I learned how Linear Regression models relationships between variables, while Ridge and Lasso Regression improve model performance by reducing overfitting through regularization. These algorithms are widely used in predictive analytics and machine learning applications.

---

**Status:** Completed
