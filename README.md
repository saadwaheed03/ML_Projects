# ML_Projects
# Salary Prediction Using Linear Regression - Project 1

This project explores the relationship between years of work experience and salary using a simple linear regression model. It was designed as a foundational machine learning exercise using a dummy dataset, but the methods and evaluation techniques are directly transferable to real-world applications such as HR analytics and workforce compensation modeling.

## 📌 Project Overview

The primary objective was to build a regression model that can predict salaries based on an individual's years of experience. The project includes:
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Assumption testing through residual diagnostics
- Cross-validation for generalizability
- An interactive salary prediction tool using Jupyter widgets

## 🧠 Key Concepts and Techniques

- **Linear Regression** using scikit-learn
- **Exploratory Data Analysis** using seaborn and matplotlib
- **Train/test split** and **5-fold cross-validation**
- **Model Evaluation**: R² score, residual analysis
- **Validation of Linear Regression Assumptions**:
  - Linearity
  - Independence
  - Homoscedasticity
  - Normality of residuals
- **Interactive Widgets** for real-time salary prediction in Jupyter

## 📊 Results

- **R² Score**: 0.89 — indicating that approximately 89% of the variance in salaries was explained by years of experience
- Residuals passed diagnostic checks for normality, independence, and homoscedasticity
- Cross-validation confirmed consistent model performance

## 💡 What I Learned

This project taught me:
- How to implement and interpret linear regression models
- The importance of validating model assumptions before deployment
- How even simple models can be powerful and interpretable when used correctly
- How to communicate ML insights visually and interactively

## 🌍 Why This Matters

Salary prediction models are increasingly relevant in today’s data-driven world, especially in domains like HR analytics, where transparency and fairness are critical. This kind of modeling can inform compensation strategies, help detect wage disparities and support informed hiring decisions.

## 📂 Files

- `Linear_Regression_Salary.ipynb`: The main Jupyter notebook




## 🙏 Acknowledgements

Special thanks to **Vishal Khemani** for his guidance and support during this project.

## 🔧 Tools Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- ipywidgets
- scipy

