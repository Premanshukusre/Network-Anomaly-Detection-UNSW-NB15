Network Anomaly Detection using UNSW-NB15

This project is part of Machine Learning TAE-1 (Project Based Learning).

The objective of this project is to detect network anomalies using multiple machine learning algorithms on the UNSW-NB15 dataset.

Introduction

This project focuses on identifying malicious network activities using supervised machine learning techniques. It compares multiple models to determine the most effective approach for intrusion detection.

Dataset

The dataset used is UNSW-NB15 [1], [2] (also available on Kaggle).

It contains modern network traffic with both normal and attack data.

Target Variable:

0 → Normal Traffic
1 → Attack / Anomaly

Models Implemented

Decision Tree
Random Forest
XGBoost
K-Nearest Neighbors (KNN)
Logistic Regression
Support Vector Machine (SVM)
Naive Bayes

Project Structure

Network-Anomaly-Detection-UNSW-NB15
│── README.md
│── datasets/
│── models/
│── logs/
│── notebooks/

How to Run the Project

Clone the repository:

git clone <your-repo-link>
cd Network-Anomaly-Detection-UNSW-NB15

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost

Download dataset:

Place dataset files inside the datasets/ folder
Or upload in Google Colab

Open the project:

Open .ipynb files in Google Colab or Jupyter Notebook

Run the code:

Execute all cells step-by-step
Models will train and display results
Accuracy Comparison
Model	Accuracy
Decision Tree	99.96%
Random Forest	99.92%
XGBoost	97.76%
KNN	97.61%
Logistic Regression	94.98%
SVM	94.77%
Naive Bayes	71.09%
Objective

To build and compare multiple machine learning models for detecting network intrusions and analyze their performance.

Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost

Highlights
Implemented multiple machine learning models
Compared performance using accuracy, precision, recall, and F1-score
Applied preprocessing and feature scaling where required
Maintained structured workflow using GitHub
Best Model

Random Forest performed best due to its ensemble learning capability and stability.

Limitations
Possible overfitting in Decision Tree
Limited hyperparameter tuning
Higher computation time for some models
Model Insights

Decision Tree: High accuracy but prone to overfitting
Random Forest: Best overall performance
XGBoost: Balanced and reliable
SVM and Logistic Regression: Moderate performance
KNN: Good accuracy but slower prediction
Naive Bayes: Lowest performance due to feature independence assumption

Future Scope
Apply deep learning models (ANN, CNN)
Perform hyperparameter tuning
Improve feature engineering
Develop real-time intrusion detection system
Use Explainable AI techniques
