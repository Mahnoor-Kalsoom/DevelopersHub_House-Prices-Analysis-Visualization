# 🏠 House Prices Analysis & Prediction

*(AI/ML Internship – Task 6)*

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** and **house price prediction** using a real-world housing dataset.
The aim is to understand the key factors that influence house prices and build a baseline regression model.

This task is part of the **AI/ML Engineering Internship** at **DevelopersHub Corporation**.

---

## 🎯 Objectives

* Explore the structure and characteristics of the dataset
* Identify and handle missing values
* Visualize relationships between features and house prices
* Analyze correlations among numerical variables
* Build and evaluate a regression model for predicting house prices

---

## 📊 Dataset

* **Dataset Name:** House Prices Dataset
* **File:** `house.csv`
* **Description:**
  The dataset contains residential housing data including:

  * Living area size
  * Overall quality
  * Number of rooms
  * Year built
  * Neighborhood and style features
  * **SalePrice** (target variable)

---

## 🧹 Data Preprocessing

The following preprocessing steps were applied:

* Dataset loaded using **Pandas**
* Checked data types and missing values
* Missing value handling:

  * Numerical features filled using **median**
  * Categorical features filled using **mode**
* Converted categorical features into numeric format
* Selected relevant features for modeling
* Split data into **training** and **testing** sets

---

## 🔍 Exploratory Data Analysis (EDA)

### ✔ Dataset Inspection

* Dataset shape and structure
* Summary statistics

### ✔ Visualizations

* **Histogram & KDE:** Distribution of house prices
* **Correlation Heatmap:** Relationships between numeric features
* **Scatter Plots:** Living area vs SalePrice
* **Box Plots:** Overall quality vs SalePrice
* **Count Plots:** Distribution of categorical features

These analyses help identify important predictors and patterns affecting house prices.

---

## 🤖 Model Building

* **Algorithm:** Linear Regression
* **Reason:**
  Linear Regression provides a simple and interpretable approach for predicting continuous values such as house prices.

---

## 📈 Model Evaluation

Model performance was evaluated using:

* ✅ **Mean Absolute Error (MAE)**
* ✅ **Root Mean Squared Error (RMSE)**
* 📊 **Actual vs Predicted Prices Visualization**

These metrics measure how closely the predicted prices match actual house prices.

---

## 🛠 Technologies Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🎯 Learning Outcomes

* Practical experience with:

  * Exploratory Data Analysis
  * Regression modeling
  * Feature relationships and interpretation
* Better understanding of:

  * Data preprocessing techniques
  * Regression evaluation metrics

---

## ✅ Conclusion

This project demonstrates a complete data analysis and regression workflow for predicting house prices.
The results highlight the impact of key housing features and provide a strong foundation for applying advanced regression models in future work.

---

## 👩‍💻 Author

**Name:** Mahnoor Kalsoom
**Task:** AI/ML Internship – Task 6
**Organization:** DevelopersHub Corporation

---