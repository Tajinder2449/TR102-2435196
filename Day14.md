## Day 14 — 17 July 2026

### Topics Covered

- Decision Tree
- Random Forest
- Comparison of Decision Tree and Random Forest
- Applications of Decision Tree and Random Forest

---

### Learning Summary

#### Decision Tree

A Decision Tree is a supervised machine learning algorithm used for both classification and regression tasks. It represents decisions and their possible outcomes in the form of a tree structure, where each internal node represents a feature, each branch represents a decision, and each leaf node represents the final prediction.

**Working of Decision Tree:**
1. Select the best feature to split the dataset.
2. Divide the data into subsets based on the selected feature.
3. Repeat the process recursively until a stopping condition is reached.
4. Assign the final prediction at the leaf nodes.

**Advantages:**
- Easy to understand and interpret.
- Handles both numerical and categorical data.
- Requires minimal data preprocessing.

**Limitations:**
- Prone to overfitting.
- Small changes in data may produce different trees.
- Can become complex for large datasets.

---

#### Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting. Each tree is trained on a random subset of the data, and the final prediction is obtained through majority voting (classification) or averaging (regression).

**Working of Random Forest:**
1. Create multiple random subsets of the training dataset.
2. Train a separate decision tree on each subset.
3. Generate predictions from all trees.
4. Combine the predictions using majority voting or averaging.

**Advantages:**
- Higher accuracy than a single decision tree.
- Reduces overfitting.
- Handles large datasets and high-dimensional data effectively.
- Robust to noise and missing values.

**Limitations:**
- More computationally intensive.
- Less interpretable than a single decision tree.
- Requires more memory.

---

### Comparison of Decision Tree and Random Forest

| Decision Tree | Random Forest |
|---------------|---------------|
| Uses a single decision tree. | Uses multiple decision trees. |
| Faster to train and interpret. | More accurate and robust. |
| More prone to overfitting. | Reduces overfitting through ensemble learning. |
| Simpler model. | More complex model with better generalization. |

---

### Applications

**Decision Tree**
- Customer segmentation.
- Credit risk assessment.
- Medical diagnosis.
- Decision support systems.

**Random Forest**
- Fraud detection.
- Disease prediction.
- Recommendation systems.
- Stock market analysis.
- Image classification.

---

### Key Takeaways

- Learned the working principles of Decision Tree and Random Forest algorithms.
- Understood the differences between single-tree and ensemble-based models.
- Explored the advantages, limitations, and applications of both algorithms.
- Learned how Random Forest improves prediction accuracy by combining multiple decision trees.

---

### Reflection

Today's session focused on Decision Tree and Random Forest, two widely used supervised learning algorithms. I learned how Decision Trees make predictions through a tree-like structure and how Random Forest combines multiple trees to produce more accurate and reliable results while reducing overfitting.

---

**Status:** Completed
