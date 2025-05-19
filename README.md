# 💎 Diamond Price Prediction Project

This project uses Exploratory Data Analysis (EDA) and machine learning techniques to predict the **price of diamonds** using features like carat, cut, color, and clarity. The dataset contains **219,703 rows** and **7 important features**.

## 📊 Dataset Overview

- **Source**: Kaggle
- **Rows**: 219,703
- **Columns**: 7 features (`carat`, `cut`, `color`, `clarity`, `depth`, `table`, `price`)
- **Target Variable**: `price`

## 🧪 Techniques Used

- Data Cleaning and Preprocessing
- Handling Missing Values
- Label Encoding (for categorical features)
- Log Transformation (to normalize price)
- Principal Component Analysis (PCA)
- Normalization / Standardization
- Data Visualization (Seaborn, Matplotlib)
- Linear Regression Modeling

## 📌 Steps Performed

1. **Data Loading & Cleaning**  
   ➤ Removed missing or null values  
   ➤ Standardized column values

2. **Feature Engineering**  
   ➤ Encoded categorical columns like `cut`, `color`, and `clarity`  
   ➤ Applied log transformation on skewed `price` column

3. **Dimensionality Reduction**  
   ➤ Applied PCA to reduce multicollinearity and noise

4. **Modeling**  
   ➤ Trained a **Linear Regression** model  
   ➤ Evaluated using RMSE, MAE, and R² score

## 📈 Visualization Examples

- Pairplots and Correlation Heatmaps
- Price distribution before and after log transformation
- PCA components and variance explained
- Regression line and residual plots

## 🧠 Model Summary

- Model: **Linear Regression**
- Score (R²): ~High (based on transformed data)
- Error Metrics: Low RMSE after preprocessing

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📁 Folder Structure


## 🚀 Future Improvements

- Use more advanced models (XGBoost, Random Forest)
- Hyperparameter tuning with GridSearchCV
- Web app deployment using Flask or Streamlit

## 🙌 Acknowledgments

- [Kaggle Dataset](https://www.kaggle.com/)
- Inspiration from various EDA and ML tutorials
