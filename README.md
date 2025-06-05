# Task-4-Classification-with-Logistic-Regression.

1. Loaded the dataset and dropped irrelevant columns (id, Unnamed: 32).

2. Encoded the target column diagnosis as binary: Malignant (1), Benign (0).

3. Checked numerical feature distribution — most were right-skewed.

4. Applied Standardization to all numerical features using StandardScaler.

5. Split the dataset into training and test sets using train_test_split.

6. Trained a Logistic Regression model using LogisticRegression from sklearn.

7. Evaluated model on both train and test sets using:

* Confusion Matrix

* Precision, Recall, F1 Score

* ROC-AUC Score

8. Plotted ROC Curve to visualize performance across all classification thresholds.

9. Plotted Precision-Recall Curve to check performance with respect to imbalanced classes.

10. Found and applied optimal threshold from ROC curve using Youden’s J statistic.

**Tools and Libraries Used:**
* pandas, numpy – data manipulation

* matplotlib.pyplot – plotting

* sklearn – modeling and evaluation (LogisticRegression, StandardScaler, metrics, model_selection)
