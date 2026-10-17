# KNN-imputer
AI &amp; Machin learning project
# 🚢 KNN Imputer – Titanic Dataset

## 📌 Project Overview
This project demonstrates how to handle missing values in the Titanic dataset using the **K-Nearest Neighbors (KNN) Imputer** from Scikit-learn.

The project focuses on the `Age` and `Fare` columns and shows how missing age values can be estimated using information from nearby data points.

## 🎯 Project Objectives
- Identify and handle missing values.
- Apply KNN Imputation using Scikit-learn.
- Compare the data before and after imputation.
- Understand a practical data preprocessing technique used in Machine Learning.

## 🛠️ Technologies & Libraries
- **Python**
- **Pandas** – Data manipulation and DataFrames.
- **NumPy** – Randomly creating missing values for demonstration.
- **Scikit-learn** – Applying `KNNImputer`.

## ⚙️ Project Workflow
1. Load the Titanic dataset using Pandas.
2. Select the `Age` and `Fare` columns.
3. Randomly mask approximately 10% of the age values to simulate missing data.
4. Create a `KNNImputer` with `n_neighbors=5`.
5. Fit the imputer and transform the dataset.
6. Display the data before and after imputation.

## 🧠 What Is KNN Imputation?
KNN Imputation estimates missing values by finding nearby data points and using their values to fill the gaps.

In this project, the imputer uses **5 neighbors** to estimate missing values.

## 📊 Example Results
The notebook displays the first five rows before and after imputation.

For example, some missing `Age` values are filled with estimated values, while existing values remain unchanged.

## 📚 Learning Outcomes
- Handling missing data.
- Using Scikit-learn preprocessing tools.
- Understanding KNN-based imputation.
- Preparing data for Machine Learning workflows.

## 🚀 Future Improvements
- Compare KNN Imputation with mean and median imputation.
- Evaluate different values of `n_neighbors`.
- Scale features before applying KNN Imputation.
- Compare the imputed values with the original values when available.

## 👨‍💻 Author
Loay Nady

---

*This project was created for learning and practicing data preprocessing techniques in Python.*
