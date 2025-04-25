# Task1-heart-disease-preprocessing
# Heart Disease Dataset - Data Cleaning & Preprocessing

This project was completed as part of the AI & ML Internship Task 1. The goal is to clean and preprocess raw data to make it suitable for machine learning models.

---

## Objective
Learn how to:
- Handle missing values
- Encode categorical features
- Scale numerical data
- Detect and treat outliers

---

## Dataset
We used the [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

---

## Tools & Libraries
- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for encoding and feature scaling

---

## Steps Performed

### 1. Imported Dataset
Loaded the heart disease dataset and checked for nulls and data types.

### 2. Handled Missing Values
- Used `.fillna()` with median for numerical features.
- Ensured no null values were left.

### 3. Encoded Categorical Variables
- Used `pd.get_dummies()` on columns like `cp`, `thal`, and `slope`.

### 4. Feature Scaling
- Standardized features like `age`, `chol`, `trestbps`, `thalach`, and `oldpeak` using `StandardScaler`.

### 5. Outlier Detection
- Used boxplots to visualize and manually removed extreme outliers from the `chol` column.

---

## Visualizations Included
- Boxplots to detect outliers

---

## Final Outcome
A clean, numerical dataset ready for use in a machine learning model.

