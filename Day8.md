## Day 8 — 09 July 2026

### Topics Covered

- Introduction to Class Imbalance
- Causes of Class Imbalance
- Impact of Class Imbalance on Machine Learning Models
- Techniques to Handle Class Imbalance

---

### Learning Summary

#### Class Imbalance

Class imbalance occurs when the distribution of classes in a dataset is not equal, where one class has significantly more samples than another class. It is commonly found in classification problems where the minority class represents important but rare events.

**Examples:**
- Fraud detection (few fraudulent transactions compared to normal transactions)
- Medical diagnosis (fewer disease cases compared to healthy cases)
- Spam detection (fewer spam messages compared to normal messages)

#### Causes of Class Imbalance

Class imbalance can occur due to:

- Natural differences in real-world data distribution.
- Difficulty in collecting samples from minority classes.
- Rare occurrence of certain events.
- Data collection limitations.

#### Impact of Class Imbalance

Class imbalance can negatively affect machine learning models by:

- Making the model biased toward the majority class.
- Reducing the ability to correctly identify minority classes.
- Producing misleading accuracy results.
- Decreasing model performance for important cases.

#### Evaluation Metrics for Imbalanced Data

Accuracy alone is not sufficient for evaluating imbalanced datasets. Other important metrics include:

- **Precision** – Measures the correctness of positive predictions.
- **Recall** – Measures how many actual positive cases are correctly identified.
- **F1-Score** – Combines precision and recall into a single metric.
- **Confusion Matrix** – Shows correct and incorrect predictions for each class.

#### Techniques to Handle Class Imbalance

**1. Resampling Techniques**

- **Oversampling:** Increases the number of minority class samples.
  - Example: SMOTE (Synthetic Minority Over-sampling Technique)

- **Undersampling:** Reduces the number of majority class samples.

**2. Data Augmentation**
- Generates new samples for the minority class using existing data patterns.

**3. Algorithm-Level Techniques**
- Using machine learning algorithms that support class weights.
- Assigning higher importance to minority class samples during training.

**4. Ensemble Methods**
- Combining multiple models to improve classification performance on imbalanced datasets.

---

### Key Takeaways

- Understood the concept and challenges of class imbalance in machine learning.
- Learned why accuracy is not always a reliable evaluation metric for imbalanced datasets.
- Explored different techniques such as oversampling, undersampling, and SMOTE.
- Learned the importance of selecting appropriate evaluation metrics.

---

### Reflection

Today's session focused on handling class imbalance, which is an important challenge in machine learning classification problems. I learned how imbalanced datasets can affect model performance and how different balancing techniques help create more reliable and unbiased machine learning models.

---

**Status:** Completed
