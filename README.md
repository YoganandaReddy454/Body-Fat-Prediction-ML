# Body Fat Prediction Using Machine Learning

![ML](https://img.shields.io/badge/Machine%20Learning-Project-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![EDA](https://img.shields.io/badge/EDA-Pandas%20%7C%20Matplotlib%20%7C%20Seaborn-yellow)

## 📌 Project Overview

This project aims to predict **body fat percentage** using machine learning techniques by analyzing various body measurement features. It involves **Exploratory Data Analysis (EDA)**, **feature engineering**, **data preprocessing**, and training ML models to estimate body fat percentage with high accuracy. 

The dataset contains body composition and anthropometric data of individuals including their age, weight, height, and circumference measurements like abdomen, wrist, hip, etc.

## 🎯 Objectives

- Perform exploratory data analysis on the body fat dataset.
- Identify and remove outliers.
- Train multiple machine learning models.
- Evaluate and compare model performance.
- Predict body fat percentage for new individuals.

---

## 📁 Repository Structure

```bash
Body-Fat-Prediction-ML/
│
├── Data/
│   └── bodyfat.csv                  # Dataset used for training and testing
│
├── Images/
│   └── *.png                        # Visualizations from EDA and model evaluation
│
├── ML Body Fat Prediction.ipynb     # Main Jupyter Notebook with EDA and ML
├── README.md                        # Project documentation
└── requirements.txt                 # Dependencies
```

## 📊 Dataset Description
The dataset used contains 252 records and 15+ attributes. Some of the important features are:

Density – Body density (used to calculate body fat %)

BodyFat – Body fat percentage (Target variable)

Age, Weight, Height – Basic body measurements

Circumference features: Abdomen, Hip, Thigh, Knee, Ankle, Biceps, Forearm, Wrist

The target variable is BodyFat, which is continuous.

## 🧪 Exploratory Data Analysis
EDA was performed using:

Univariate analysis to check distributions (histograms, boxplots)

Bivariate analysis to identify correlations with target

Heatmaps to visualize multicollinearity

Outlier detection using Z-score and IQR method

Data imputation and cleaning

Key Insights:
Abdomen circumference has a strong correlation with body fat.

Several features had outliers which were removed before model training.

Highly correlated variables were used for feature selection.


## ⚙️ Machine Learning Models Used
Multiple regression models were evaluated to predict body fat:

Model	Description
Linear Regression	Baseline model
Lasso Regression	L1 regularization for feature selection
Ridge Regression	L2 regularization to avoid overfitting
Random Forest Regressor	Non-linear ensemble method
Gradient Boosting	Boosted tree-based regression


## 👨‍💻 Author
Nakkala Yogananda Reddy
B.Tech Data Science & ML – Lovely Professional University
🔗 LinkedIn
📧 Email: yoganandareddy454@gmail.com


## 📜 License
This project is open-source and available under the MIT License.

---

### ✅ What to Do Next:

1. **Add the `requirements.txt`** file if not already present:
```bash
pip freeze > requirements.txt

