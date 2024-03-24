# Breast Cancer Prediction

## Overview
This project focuses on the development of a breast cancer prediction system utilizing machine learning techniques. The dataset used for this project is sourced from Kaggle ([Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)), which provides features extracted from digitized images of fine needle aspirates (FNAs) of breast masses. The goal is to classify breast masses as either malignant or benign based on various quantitative metrics extracted from cell nuclei characteristics.

## Dataset Description
- **Source:** Kaggle
- **Features:** The dataset comprises ten real-valued features computed from cell nuclei characteristics, including radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.
- **Target:** The target variable indicates the diagnosis, with 'M' representing malignant and 'B' representing benign.

## Methodology
1. **Exploratory Data Analysis (EDA):** Initial exploration of the dataset to understand the distribution of features and identify any patterns or correlations.
2. **Preprocessing:** Data preprocessing steps include handling missing values, feature scaling, and encoding categorical variables.
3. **Model Training:** Several machine learning algorithms such as Support Vector Machine (SVM), Random Forest Classifier, Logistic Regression, Gradient Boosting Classifier, K-Nearest Neighbors (KNN), Decision Tree Classifier, and XGBoost are trained on the dataset.
4. **Model Evaluation:** The models are evaluated using accuracy scores to assess their performance in predicting breast cancer diagnosis.

## Results
The following table summarizes the accuracy scores achieved by different machine learning models:

| Model                        | Accuracy Score |
|------------------------------|----------------|
| SVM                          | 98.25%         |
| Random Forest Classifier     | 98.25%         |
| Gradient Boosting Classifier | 97.37%         |
| Logistic Regression          | 96.49%         |
| XGBoost                      | 96.49%         |
| KNN                          | 95.61%         |
| Decision Tree Classifier     | 92.98%         |

## Conclusion
The SVM and Random Forest Classifier models demonstrated the highest accuracy of 98.25% in predicting breast cancer diagnosis. These models, along with other machine learning algorithms, provide valuable tools for early detection and diagnosis of breast cancer, potentially improving patient outcomes.
