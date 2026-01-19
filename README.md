# Disease Risk Analysis Using Machine Learning

## Project Summary

This project focuses on predicting disease risk levels using a rich dataset comprising clinical, demographic, and medication-related information. Multiple data mining and machine learning techniques were applied to build accurate, reliable, and interpretable predictive models.

---

## Contents

* Overview
* Data Preparation
* Feature Construction
* Model Building
* Performance Evaluation
* Clustering & Unsupervised Insights
* Key Outcomes
* Project Files

---

## Overview

The objective of this project is to develop a robust disease risk prediction system through systematic data preprocessing, feature engineering, supervised learning, and unsupervised analysis. Emphasis was placed on data quality, model comparison, and interpretability to ensure dependable results.

---

## Data Preparation

* Handled missing values using **KNN imputation** along with **mean/mode imputation** where appropriate.
* Detected and treated outliers using **DBSCAN**, **Isolation Forest**, and **Local Outlier Factor (LOF)**.
* Applied **standardization** to numerical features to maintain consistent scaling.

---

## Feature Construction

* Created informative derived features such as **age groups** to improve model expressiveness.
* Removed irrelevant or low-impact attributes.
* Transformed categorical data using **One-Hot Encoding** and **Ordinal Encoding**.

---

## Model Building

* Trained multiple machine learning models including:

  * k-Nearest Neighbors (KNN)
  * Support Vector Machine (SVM)
  * Decision Tree
  * Random Forest
* Performed **hyperparameter optimization** using grid search with cross-validation.
* Evaluated performance using both complete and optimized feature sets.

---

## Performance Evaluation

* Assessed models using **accuracy, precision, recall, and F1-score**.
* The **Decision Tree model** delivered the best performance with an accuracy of **99%**.
* Confusion matrices were analyzed to understand classification behavior across risk categories.

---

## Clustering & Unsupervised Insights

* Implemented **K-Means** and **Hierarchical Clustering** to explore inherent data structures.
* Determined optimal clusters using the **elbow method** and **silhouette analysis**.
* Compared clustering patterns with supervised predictions for additional interpretability.

---

## Key Outcomes

* Achieved highly accurate disease risk classification with optimized models.
* Addressed class imbalance using **manual upsampling** and **SMOTE**, improving generalization.
* Conducted detailed exploratory data analysis with meaningful visual insights.
* Built a reusable and scalable feature engineering workflow.
* Demonstrated effective use of machine learning in healthcare analytics.
* Ensured statistical robustness through proper outlier handling and scaling.
* Produced comprehensive documentation to support reproducibility and transparency.
* Highlighted best practices for handling imbalanced medical datasets.
* Extracted hidden patterns in disease risk factors using clustering techniques.
