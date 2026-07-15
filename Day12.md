## Day 12 — 15 July 2026

### Topics Covered

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Applications of KNN and SVM

---

### Learning Summary

#### K-Nearest Neighbors (KNN)

K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for both classification and regression tasks. It predicts the output of a new data point based on the majority class or average value of its **K** nearest neighbors.

**Working of KNN:**
1. Choose the value of **K** (number of nearest neighbors).
2. Calculate the distance between the new data point and all training data points.
3. Select the **K** nearest neighbors.
4. For classification, assign the majority class.
5. For regression, calculate the average value of the nearest neighbors.

**Advantages:**
- Simple and easy to implement.
- No training phase required.
- Effective for small datasets.

**Limitations:**
- Computationally expensive for large datasets.
- Sensitive to the choice of **K**.
- Performance decreases with high-dimensional data.

---

#### Support Vector Machine (SVM)

Support Vector Machine (SVM) is a supervised machine learning algorithm mainly used for classification and also for regression tasks. It finds the optimal hyperplane that separates different classes while maximizing the margin between them.

**Working of SVM:**
1. Identify the support vectors (critical data points).
2. Find the optimal hyperplane that best separates the classes.
3. Maximize the margin between the classes.
4. Classify new data points based on their position relative to the hyperplane.

**Advantages:**
- Effective for high-dimensional datasets.
- Works well when classes are clearly separated.
- Provides good generalization performance.

**Limitations:**
- Computationally expensive for large datasets.
- Choosing the appropriate kernel can be challenging.
- Less effective when classes overlap significantly.

---

### Applications of KNN and SVM

**KNN Applications:**
- Recommendation systems.
- Image classification.
- Pattern recognition.
- Medical diagnosis.

**SVM Applications:**
- Text classification.
- Face detection.
- Spam email detection.
- Bioinformatics.
- Handwriting recognition.

---

### Key Takeaways

- Learned the working principles of KNN and SVM algorithms.
- Understood the advantages and limitations of both algorithms.
- Explored real-world applications of KNN and SVM.
- Gained knowledge of how supervised learning algorithms are used for classification and regression tasks.

---

### Reflection

Today's session focused on two important supervised learning algorithms: K-Nearest Neighbors (KNN) and Support Vector Machine (SVM). I learned how KNN classifies data based on nearby examples, while SVM separates classes using an optimal hyperplane. Both algorithms are widely used for solving classification problems in machine learning.

---

**Status:** Completed
