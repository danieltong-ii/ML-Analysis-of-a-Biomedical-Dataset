# Machine Learning Analysis of a Vertebral Column Dataset

## Introduction

This project applies Machine Learning techniques to analyze and classify the Vertebral Column Data Set, which is composed of biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine. Our primary objective is to automate the classification process between Normal (NO=0) and Abnormal (AB=1) cases, offering a computational approach to identifying potential spinal conditions.

## Educational Context

### Studying in class:

This work is conducted as part of DSCI 552 (Machine Learning for Data Science), aiming to directly apply learned machine learning concepts on a biomedical dataset to solve a classification problem.

### Application of theory:

Key theoretical concepts from the course are utilized, including:
- **K-Nearest Neighbors (KNN):** Demonstrating this simple, yet effective classification algorithm by identifying the 'k' nearest data points to predict the class of a given point.
- **Distance Metrics:** Investigating the influence of various distance metrics (Euclidean, Minkowski, Manhattan, Chebyshev, and Mahalanobis) on the model's classification performance.
- **Model Evaluation Techniques:** Employing tools like the confusion matrix, precision, recall, F1 score, and learning curves to evaluate and refine the classifier's accuracy.

## Technical Details

### Technologies used:
- **Python:** For programming.
- **NumPy & pandas:** Used for data manipulation.
- **Matplotlib & seaborn:** For creating visualizations such as scatterplots and boxplots.
- **scikit-learn:** Utilized for the KNN algorithm and calculating various distance metrics.

### Architecture overview:
The project workflow encompasses:
1. **Data Preprocessing:** Preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA):** Visual inspection of data to understand distributions and relationships.
3. **Model Training:** Applying KNN with different distance metrics to the training set.
4. **Evaluation:** Using the test set to assess the model's performance with several metrics.

### Main features:
- **Binary Classification:** Uses machine learning to distinguish between Normal and Abnormal spinal conditions.
- **Distance Metrics Comparison:** Evaluates how different metrics affect the accuracy of the classification.
- **Optimal 'k' Determination:** Identifies the most suitable 'k' value for the KNN algorithm to minimize test error.
- **Weighted Voting in KNN:** Enhances classification accuracy through weighted decision-making based on distance.

