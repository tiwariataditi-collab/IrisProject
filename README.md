Summary---
A comprehensive machine learning project using the classic Iris dataset to perform exploratory data analysis, visualization, and classification. The project demonstrates the full data science pipeline—from data cleaning and feature analysis to model evaluation and decision boundary visualization.

Project Overview---
This repository contains a Jupyter Notebook that explores the structural differences between three species of the Iris flower (Iris setosa, Iris virginica, and Iris versicolor) based on sepal and petal measurements.

The primary goal is to build a classification model capable of predicting the species of an iris flower based on its geometric features.

Key Features---
Exploratory Data Analysis (EDA): Uses pandas and seaborn to provide statistical summaries and check for missing values.

Data Visualization: Includes distribution plots and pairwise feature analysis using matplotlib and seaborn.

Machine Learning Pipeline:

Data preprocessing and feature scaling.

Classification using Scikit-Learn models.

Decision Regions: Advanced visualization using mlxtend to show how the model differentiates between species based on two primary features.

Performance Metrics: The model achieves high accuracy (e.g., 0.93 on the decision region plot) in classifying iris species.

Technologies Used----
Python 3
Pandas: For data manipulation and analysis.
Seaborn & Matplotlib: For statistical data visualization.
Scikit-Learn: For machine learning modeling and evaluation.
Mlxtend: For plotting classification decision regions.

Dataset--
The project utilizes the Iris Dataset, which includes 150 samples with four features:

Sepal Length

Sepal Width

Petal Length

Petal Width


Result---
The analysis reveals significant clustering between species, particularly with petal length and width being strong indicators for classification. The final model effectively maps these features to identify species with high precision.
