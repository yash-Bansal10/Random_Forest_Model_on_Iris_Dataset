🌸 Iris Flower Classification using Random Forest
An End-to-End Machine Learning Project
This project provides a complete, end-to-end walkthrough of a classic machine learning classification problem. The goal is to classify the species of Iris flowers (Setosa, Versicolor, and Virginica) based on their sepal and petal measurements.

This repository demonstrates the entire machine learning lifecycle, from initial data exploration and visualization to model training, evaluation, and persistence, using a Random Forest Classifier. All code is contained within the Random_Forest_Model.ipynb Jupyter Notebook.

📊 Key Features
In-depth Exploratory Data Analysis (EDA): Utilizes Seaborn and Matplotlib to create insightful visualizations like pair plots and correlation heatmaps to understand data distributions and feature relationships.

Model Training: Implements a RandomForestClassifier from Scikit-learn, a powerful and popular ensemble model for classification tasks.

Comprehensive Model Evaluation: Goes beyond simple accuracy to calculate and analyze Precision, Recall, and F1-Score.

Performance Visualization: Generates a Confusion Matrix to visualize prediction accuracy per class and a Feature Importance plot to understand which features contribute most to the model's decisions.

Model Persistence: Shows how to save the trained model using joblib for future use in other applications without needing to retrain.

🛠️ Tech Stack
Python 3.9+

Jupyter Notebook

Scikit-learn: For machine learning models, data splitting, and evaluation metrics.

Pandas: For data manipulation and analysis.

Matplotlib & Seaborn: For data visualization.

Joblib: For model serialization (saving/loading).

✨ Results and Visualizations
The notebook generates several key visualizations that provide deep insights into the data and the model's performance.

Exploratory Data Analysis
The pair plot shows the distributions of each feature and their relationships, colored by species. It's clear that the petal measurements are strong predictors for separating the classes.

Model Performance
The confusion matrix shows that the model achieved 100% accuracy on the test set, with zero misclassifications.

The feature importance plot reveals that Petal Width and Petal Length were the most influential features for the Random Forest model.
