# Elevate Labs Internship 
## Task 1 - Data Cleaning & Preprocessing

This repository contains a comprehensive exploratory data analysis (EDA) of the **Life Expectancy Dataset**, focusing on data cleaning, visualization, and preprocessing techniques to prepare the dataset for future modeling.

---

## 📂 Dataset

- **File Used**: `Life Expectancy Data.csv`
- The dataset consists of global life expectancy information, including social, economic, and health-related indicators.

---

## ✅ Libraries Used

- `pandas` – data manipulation  
- `numpy` – numerical operations  
- `matplotlib` & `seaborn` – data visualization  
- `sklearn.impute.KNNImputer` – for missing value imputation  
- `sklearn.preprocessing.LabelEncoder` – for encoding categorical variables  

---

## 🔍 Data Preprocessing Steps

1. **Imported the Dataset** using pandas.
2. **Checked for Missing Values** and calculated the percentage of missing data for each column.
3. **Removed Duplicate Records**, if present.
4. **Inspected Garbage/Unexpected Values** in categorical columns to ensure clean labels.
5. **Handled Missing Values** using:
   - **K-Nearest Neighbors (KNN) Imputation** with `n_neighbors = 5` for numerical features.
6. **Converted Categorical Variables** (`Country`, `Status`) into numeric format using `LabelEncoder`.
7. **Outlier Detection & Treatment**:
   - Created **Boxplots** to visualize outliers.
   - Applied **Outlier Treatment Function** to cap extreme values based on the Interquartile Range (IQR) method.

---

## 📊 Exploratory Data Analysis (EDA)

- **Histograms**: To analyze the distribution and skewness of numerical columns.
- **Boxplots**: To identify and handle outliers in each numerical feature.
- **Scatter Plots**: To visualize the relationship between numerical features and the target variable `Life expectancy`.
- **Correlation Heatmap**: To identify highly correlated features and understand overall data relationships.

---

## 🎯 Target Variable

- `Life expectancy` – the main variable of interest, analyzed against multiple independent features to understand patterns and dependencies.

---

## ⚙️ Tools & Technologies

- Python 3.x
- Jupyter Notebook or Google Colab
- Scikit-learn for preprocessing and imputation
- Seaborn & Matplotlib for rich data visualization

---
