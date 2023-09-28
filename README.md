# Customer Product Review Analysis and Recommendation

## Project Description:

In today's digital age, customer reviews play a crucial role in shaping consumer decisions. This GitHub project focuses on analyzing and predicting product recommendations based on customer reviews. Leveraging a diverse dataset of customer reviews for various products, the project employs multiple machine learning algorithms to predict whether a product is recommended or not.

## Components:

Data Exploration:
The project begins by loading a dataset containing customer reviews and product-related information. This dataset is sourced from a retail environment and includes details like customer age, review text, product rating, and more.

Data Preprocessing:
Data preprocessing steps involve cleaning and preparing the dataset. Irrelevant columns are removed, and categorical variables are encoded to facilitate machine learning model training.

Exploratory Data Analysis (EDA):
EDA involves visualizing and understanding the dataset. It includes generating plots and statistics to gain insights into customer ratings, age distribution, and more.

Model Building:
Three machine learning models are implemented and evaluated for predicting product recommendations:
K-Nearest Neighbors (KNN): GridSearchCV is used to find the best number of neighbors.
Support Vector Machine (SVM): A Radial Basis Kernel SVM is employed.
Logistic Regression: A logistic regression classifier is utilized.
Multi-Layer Perceptron (MLP): A neural network classifier with two hidden layers is trained.

Model Evaluation:
The performance of each model is assessed using accuracy scores. These scores are a measure of how well the models predict product recommendations based on customer attributes and reviews.

Ensemble Learning:
An ensemble model is created using the VotingClassifier, combining the predictions of the KNN, SVM, Logistic Regression, and MLP models. This ensemble leverages the strength of multiple models to improve prediction accuracy.

Conclusion:
The project delivers insights into customer product reviews and recommendations. It provides a comparison of different machine learning models and demonstrates the power of ensemble learning in improving prediction accuracy.

## Results:

The project evaluates and compares four machine learning models for product recommendation prediction: KNN, SVM, Logistic Regression, and MLP.
An ensemble model combining these algorithms achieves a high prediction accuracy.
