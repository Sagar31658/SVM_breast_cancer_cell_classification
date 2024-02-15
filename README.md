# Breast Cancer SVM Classification Analysis

## Overview

This project focuses on the classification of breast cancer tumors into benign or malignant categories using Support Vector Machine (SVM) models with various kernels. The analysis leverages a dataset comprising several features obtained from breast mass samples.

## Data Description

The dataset includes 10 features for each sample, excluding the identifier column, with a total of 699 records. Each feature is numerical, except for one categorical feature that required preprocessing due to the presence of missing values.

## Analysis Highlights

- **Data Exploration**: Initial data analysis revealed discrepancies in data types and the presence of missing values in one of the columns, necessitating data cleaning and preprocessing steps.

- **Model Performance**: Four SVM kernels (linear, RBF, polynomial, and sigmoid) were evaluated based on their accuracy, precision, recall, and F1 scores on both training and testing sets. The RBF kernel outperformed others, showing high accuracy and balance across metrics, making it the preferred choice for this classification problem.

- **Recommendations**: The RBF kernel is recommended for its superior performance in identifying malignant cases with high precision and accuracy. The linear kernel is also a viable option, while the sigmoid kernel showed significantly lower performance.

## Conclusion

The analysis underscores the effectiveness of SVM models, especially with the RBF kernel, in classifying breast cancer tumors. Future work could explore more advanced preprocessing techniques, feature selection methods, and comparison with other machine learning algorithms.
