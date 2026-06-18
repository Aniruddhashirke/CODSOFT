# Data Science Internship Projects 🚀

This repository contains Machine Learning projects completed during my **Data Science Internship at CodSoft**. These projects demonstrate practical skills in data preprocessing, exploratory data analysis, feature engineering, machine learning model development, model evaluation, and data visualization using Python.

---

# Project 1: Titanic Survival Prediction 🚢

## Overview

The Titanic Survival Prediction project aims to predict whether a passenger survived the Titanic disaster using passenger information such as age, gender, ticket class, fare, and family details.

## Problem Statement

Build a machine learning model that predicts whether a passenger survived or not based on available passenger data.

## Dataset Features

* PassengerId
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked
* Survived (Target Variable)

### Target Variable

* 0 → Did Not Survive
* 1 → Survived

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Workflow

### Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Feature selection and transformation

### Exploratory Data Analysis (EDA)

* Survival Count Plot
* Survival by Gender
* Survival by Passenger Class
* Age Distribution
* Fare Distribution
* Correlation Heatmap

### Model Building

* Logistic Regression

### Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Learning Outcomes

* Data Cleaning
* Feature Engineering
* Data Visualization
* Classification Models
* Model Evaluation

---

# Project 2: Movie Rating Prediction 🎬

## Overview

The Movie Rating Prediction project focuses on predicting movie ratings based on features such as genre, director, actors, release year, duration, and vote count. The project applies machine learning regression techniques to estimate movie ratings accurately.

## Problem Statement

Develop a machine learning model that predicts movie ratings using historical movie data and relevant movie features.

## Dataset Features

* Movie Name
* Year
* Duration
* Genre
* Director
* Actor 1
* Actor 2
* Actor 3
* Votes
* Rating (Target Variable)

### Target Variable

* Movie Rating

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Workflow

### Data Preprocessing

* Removed missing target values
* Cleaned Year, Duration, and Votes columns
* Handled missing values
* Converted data into machine-learning-friendly format

### Exploratory Data Analysis (EDA)

* Rating Distribution
* Correlation Heatmap
* Movies Released Per Year
* Duration Distribution
* Votes vs Rating Analysis
* Top Genres by Rating
* Top Directors by Rating

### Feature Engineering

* One-Hot Encoding for:

  * Genre
  * Director
  * Actor 1
  * Actor 2
  * Actor 3

### Model Building

* Random Forest Regressor

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### Visualizations

* Rating Distribution Histogram
* Correlation Heatmap
* Votes vs Rating Scatter Plot
* Movies Released Per Year
* Top Genres by Average Rating
* Top Directors by Average Rating
* Actual vs Predicted Ratings Plot
* Error Distribution Plot
* Feature Importance Plot

## Learning Outcomes

* Regression Modeling
* Feature Engineering
* Data Visualization
* Machine Learning Pipelines
* Model Performance Evaluation
* Working with Real-World Movie Data

---

# Project 3: Credit Card Fraud Detection 💳

## Overview

The Credit Card Fraud Detection project focuses on identifying fraudulent credit card transactions using machine learning techniques. Since fraudulent transactions represent only a small portion of the dataset, special attention was given to handling class imbalance and improving fraud detection performance.

## Problem Statement

Build a machine learning model that can classify transactions as fraudulent or genuine based on transaction-related features.

## Dataset Features

* Time
* Amount
* V1 – V28 (Anonymized Features)
* Class (Target Variable)

### Target Variable

* 0 → Genuine Transaction
* 1 → Fraudulent Transaction

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Jupyter Notebook

## Workflow

### Data Preprocessing

* Checked and handled missing values
* Standardized numerical features
* Normalized transaction data
* Prepared data for model training

### Handling Class Imbalance

* Analyzed class distribution
* Applied SMOTE (Synthetic Minority Oversampling Technique)
* Balanced training data for improved fraud detection

### Exploratory Data Analysis (EDA)

* Class Distribution Analysis
* Fraud vs Genuine Transaction Comparison
* Correlation Analysis
* Data Visualization

### Model Building

* Logistic Regression
* Random Forest Classifier

### Evaluation Metrics

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Classification Report
* Confusion Matrix

### Visualizations

* Class Distribution Plot
* Correlation Heatmap
* Confusion Matrix
* Fraud Detection Analysis
* Feature Importance Plot

## Learning Outcomes

* Handling Imbalanced Datasets
* Feature Scaling and Normalization
* Fraud Detection Techniques
* Classification Algorithms
* Model Evaluation using Precision, Recall, and F1-Score
* Real-World Financial Data Analysis

---

# Technologies Used Across Projects

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# How to Run

## Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

## Navigate to the Project Folder

```bash
cd YOUR_REPOSITORY
```

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

## Run Notebook Cells Sequentially

---

# Internship Details

**Organization:** CodSoft
**Role:** Data Science Intern

---

# Author

## Aniruddha Shirke
