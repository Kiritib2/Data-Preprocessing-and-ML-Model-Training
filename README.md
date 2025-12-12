# Data-Preprocessing-and-ML-Model-Training
A learning project exploring the full lifecycle of an ML experiment. From raw data to trained models, the repo demonstrates preprocessing, feature preparation, model building, and evaluation in a clean, reproducible format.
Data Preprocessing, EDA & Machine Learning Model Training

# This repository showcases a structured, end-to-end machine learning workflow across three stages:
data preprocessing, exploratory data analysis, and model training.
Each stage is documented in a dedicated Jupyter notebook to reflect real-world data science practices.

The project demonstrates how raw data travels through cleaning, exploration, feature shaping, and predictive modeling to uncover meaningful insights.

🗂 Notebook Overview
## Data Preprocessing: Data Preprocessing (Titanic Dataset)

Focused on foundational data preparation steps, including:

Inspecting missing values

Understanding dataset structure

Initial feature preparation

Preparing raw data for deeper analysis

This notebook lays the groundwork for all later ML tasks.

## DecisionTreeand other: Exploratory Data Analysis & Feature Engineering

This notebook acts as the bridge between preprocessing and machine learning by:

Exploring distributions and variable relationships

Identifying patterns, correlations, and outliers

Creating or transforming features for improved model performance

Making data-driven decisions before training begins

This stage strengthens intuition about the dataset and helps shape better ML models.

## KNN: Machine Learning Model Training (Breast Cancer Dataset)

Implements supervised ML using the K-Nearest Neighbors (KNN) algorithm.

Key tasks include:

Loading the Breast Cancer Wisconsin dataset

Train-test splitting

Training KNN models for K = 1 to 10

Tracking training and testing accuracy

Plotting accuracy trends

Identifying optimal K and understanding bias–variance behavior

This notebook demonstrates hyperparameter tuning and performance visualization.

## Datasets Used
1. Titanic Passenger Dataset
   Used for: preprocessing, EDA
   Source: Data Science Dojo GitHub

2. Breast Cancer Wisconsin Diagnostic Dataset
   Used for: ML model training
   Source: Scikit-learn built-in datasets

3. Wine Dataset
   Used for: preprocessing, EDA
   source: GitHub 
   

## Data Workflow

The full ML pipeline covered in this project includes:

Data Cleaning

Handling Missing Values

EDA & Insight Extraction

Feature Engineering & Selection

Model Training (KNN)

Hyperparameter Tuning

Performance Evaluation & Visualization

This mirrors workflows used in real analytics and ML projects.

 ## Model Performance (KNNandRandomforest)

The KNN model was evaluated across multiple values of K, with insights such as:

Lower K values tend to overfit

Higher K values generalize better

Optimal K lies in the mid-range

Training and testing accuracy curves reveal model stability

I can insert exact accuracy tables and charts if you want them included.

 ## Repository Structure
### Data-Preprocessing-and-ML-Model-Training
│
├── Day_10.ipynb      # Preprocessing using Titanic dataset
├── Day_11.ipynb      # Exploratory Data Analysis & Feature Engineering
├── Day_12.ipynb      # KNN Model Training & Evaluation
└── README.md         # Project Documentation

## Tech Stack

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

 ## Skills Demonstrated

Real-world data cleaning

EDA and visualization

Feature engineering

Supervised ML model development

Hyperparameter tuning

Accuracy evaluation

Reproducible ML workflow design

## Future Enhancements

Add more ML models (Logistic Regression, SVM, Random Forest)

Implement full preprocessing pipelines with Pipeline()

Add classification reports and confusion matrices

Deploy model using Flask or FastAPI

Convert notebooks into a unified ML script

 ## Author

Kiriti Nomula
Aspiring Data Scientist | ML Enthusiast
LinkedIn: linkedin.com/in/kiriti-nomula  
GitHub: github.com/Kiritib2 
