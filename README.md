PCA with Logistic Regression – Digit Recognition Mini Project
🎯 Objective
This mini-project demonstrates how to use Principal Component Analysis (PCA) to reduce the dimensionality of high-dimensional data and then use a Logistic Regression classifier to recognize handwritten digits.

📁 Dataset
Name: Digits Dataset (built-in from sklearn.datasets)

Shape:

Original: 1797 samples, 64 features (8×8 images)

After PCA: 1797 samples, 2 features

Target: Digit classes (0–9)

🧰 Technologies Used
Python

Scikit-learn

PCA (for dimensionality reduction)

Logistic Regression (for classification)

Seaborn/Matplotlib (for visualization)

🚀 What the Project Does
Loads the Digits dataset (images of handwritten numbers)

Scales the feature data using StandardScaler

Applies PCA to reduce 64 features → 2 principal components

Visualizes the dataset in 2D using a scatter plot

Splits data and trains a Logistic Regression model

Evaluates model using accuracy score

📈 Output Example
yaml
Copy
Edit
Original shape: (1797, 64)
Reduced shape after PCA: (1797, 2)

📈 Classification Accuracy using PCA-reduced data: 0.63
🧠 Learning Outcomes
Understand dimensionality reduction with PCA

Visualize high-dimensional data in 2D

Apply classification to reduced data

Interpret trade-offs in accuracy when reducing dimensions

