Phishing URL Detection Using Ridge- and Lasso-Regularized Logistic Regression
Overview

This project is a machine learning-based phishing URL detection system that classifies website URLs as Legitimate or Phishing using Logistic Regression with Ridge (L2) and Lasso (L1) regularization. The model is trained on a labeled dataset of URLs and uses various URL-based features to identify malicious websites.

Objective

The main objective of this project is to help users identify phishing websites before visiting them, reducing the risk of online scams, identity theft, and data breaches.

Features
Detects phishing and legitimate URLs.
Uses Logistic Regression for binary classification.
Implements Ridge (L2) and Lasso (L1) regularization to improve model performance.
Extracts meaningful URL-based features for prediction.
Evaluates model performance using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
Lightweight, fast, and easy to deploy.
Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn (optional for visualization)
Workflow
Collect and preprocess the phishing URL dataset.
Extract URL-based features.
Split the dataset into training and testing sets.
Train Logistic Regression models with Ridge and Lasso regularization.
Evaluate model performance.
Predict whether a new URL is Safe or Phishing.
Project Motivation

Phishing attacks continue to be one of the leading causes of cybercrime. This project aims to provide a simple and effective solution that helps users identify suspicious URLs before accessing them. By combining machine learning with regularization techniques, the system improves prediction accuracy while reducing overfitting and selecting the most relevant features.

Future Enhancements
Browser extension for real-time phishing detection.
Web application with an interactive user interface.
Integration with live threat intelligence feeds.
Support for deep learning models for improved accuracy.
