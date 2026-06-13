# Titanic Survival Prediction 🚢

## Overview

This project aims to predict whether a passenger survived the Titanic disaster using Machine Learning techniques. The model is trained on the famous Titanic dataset and uses passenger information such as age, gender, passenger class, fare, and family details to make predictions.

This project was completed as **Task 1** during my **Data Science Internship at CodSoft**.

---

## Problem Statement

Build a machine learning model that predicts whether a passenger on the Titanic survived or not based on available passenger data.

---

## Dataset

The dataset contains information about Titanic passengers, including:

* PassengerId
* Pclass (Passenger Class)
* Name
* Sex
* Age
* SibSp (Number of Siblings/Spouses Aboard)
* Parch (Number of Parents/Children Aboard)
* Ticket
* Fare
* Cabin
* Embarked
* Survived (Target Variable)

Target Variable:

* 0 → Did Not Survive
* 1 → Survived

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

* Loaded the Titanic dataset using Pandas.

### 2. Data Preprocessing

* Handled missing values.
* Filled missing Age values with median.
* Filled missing Embarked values with mode.
* Removed unnecessary columns.
* Encoded categorical features.

### 3. Exploratory Data Analysis (EDA)

* Survival Count Visualization
* Survival by Gender
* Survival by Passenger Class
* Age Distribution Analysis
* Fare Distribution Analysis
* Correlation Heatmap

### 4. Model Building

* Split data into training and testing sets.
* Trained a Logistic Regression model.

### 5. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## Visualizations

The project includes various visualizations:

* Survival Count Plot
* Survival by Gender Plot
* Survival by Passenger Class Plot
* Age Distribution Histogram
* Fare Distribution Histogram
* Correlation Heatmap
* Confusion Matrix Heatmap

---

## Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for binary classification problems. In this project, it predicts whether a passenger survived (1) or not (0).

---

## Results

The model successfully predicts passenger survival based on the given features and achieves good classification performance on the test dataset.

Evaluation Metrics:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/Titanic-Survival-Prediction.git
```

2. Navigate to the project folder

```bash
cd Titanic-Survival-Prediction
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open Jupyter Notebook

```bash
jupyter notebook
```

5. Run the notebook cells sequentially.

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Machine Learning Model Building
* Model Evaluation
* Working with Real-World Datasets

---

## Internship

**Organization:** CodSoft
**Role:** Data Science Intern

---

## Author

**Aniruddha Shirke**

