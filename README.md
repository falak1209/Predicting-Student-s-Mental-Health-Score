# 📊 Predicting Student Mental Health Score using Machine Learning

## 📌 Overview

Mental health has become a growing concern among students, especially with the increasing use of social media. This project develops a Machine Learning regression model to predict a student's mental health score using demographic information, social media usage, academic behavior, and lifestyle factors.

The project follows a complete Machine Learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, hyperparameter tuning, and model evaluation.

---

## 🎯 Problem Statement

Develop a predictive model that estimates a student's mental health score based on:

- Social media usage
- Sleep duration
- Study hours
- Physical activity
- Stress level
- Academic level
- Lifestyle habits
- Demotional and demographic information

---

## 📂 Dataset

**Dataset:** Student Social Media and Mental Health Impact Dataset

The dataset contains information about students including:

- Age
- Gender
- Country
- Academic Level
- Average Daily Social Media Usage
- Daily Unlocks
- Sleep Hours
- Study Hours
- Physical Activity
- Stress Level
- Relationship Status
- Most Used Social Media Platform
- Mental Health Score (Target Variable)

---

# 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

# 📊 Project Workflow

### 1. Data Collection

- Loaded dataset
- Inspected data types
- Checked missing values
- Removed duplicate records

---

### 2. Data Cleaning

- Handled missing values
- Corrected unrealistic values
- Removed inconsistencies
- Prepared clean dataset for analysis

---

### 3. Exploratory Data Analysis (EDA)

Performed visual analysis using:

- Distribution plots
- Box plots
- Scatter plots
- Correlation heatmap
- Feature relationship analysis

Key insights were extracted regarding the impact of lifestyle and social media habits on mental health.

---

### 4. Feature Engineering

- Grouped countries into regions
- Encoded categorical variables
- Selected important features
- Prepared data for machine learning

---

### 5. Data Preprocessing

Implemented Scikit-learn Pipelines for:

- Missing value imputation
- One-Hot Encoding
- Ordinal Encoding
- Feature Scaling

Used:

- Pipeline
- ColumnTransformer

---

### 6. Model Building

Machine Learning models implemented:

- Linear Regression
- Random Forest Regressor

---

### 7. Hyperparameter Tuning

Optimized Random Forest using:

- RandomizedSearchCV

---

### 8. Model Evaluation

Evaluation metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 📈 Model Performance

| Model | Performance |
|---------|------------|
| Linear Regression | Baseline Regression Model |
| Random Forest Regressor | Best Performing Model |
| Tuned Random Forest | Optimized using RandomizedSearchCV |

The Random Forest model achieved the highest prediction accuracy and demonstrated strong generalization performance.

---

# 📌 Features Used

- Age
- Gender
- Academic Level
- Country
- Average Daily Usage Hours
- Daily Unlocks
- Sleep Hours
- Study Hours
- Physical Activity
- Stress Level
- Relationship Status
- Most Used Platform

Target Variable:

- Mental Health Score

---

# 📊 Machine Learning Concepts Used

- Regression
- Feature Engineering
- Exploratory Data Analysis
- Data Cleaning
- Data Visualization
- Model Comparison
- Hyperparameter Tuning
- Pipeline
- ColumnTransformer
- Feature Scaling
- One-Hot Encoding
- Ordinal Encoding

---

# 🚀 Future Improvements

- Deploy the model using Flask or FastAPI
- Build an interactive web application
- Deploy on Render or Streamlit Cloud
- Add SHAP for model explainability
- Integrate real-time prediction through an API

---

# 💡 Key Learnings

Through this project, I gained practical experience in:

- End-to-end Machine Learning workflow
- Data preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Scikit-learn Pipelines
- Model evaluation
- Hyperparameter tuning
- Building production-ready ML pipelines

---

## ⭐ If you found this project useful, don't forget to Star this repository!
