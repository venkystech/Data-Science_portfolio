# EDA2 – Adult Income Dataset Analysis

## 🧾 Objective
This assignment focuses on **data preprocessing, feature engineering, and feature selection** for machine learning tasks. The goal is to prepare the dataset for predictive modeling to determine whether an individual's income exceeds $50K/yr based on census data.

---

## 📂 Dataset
**Filename:** `adult_with_headers.csv`  
Contains census data with features like age, workclass, education, marital status, occupation, hours per week, and more. The target variable is `income` (<=50K or >50K).

---

## 🔧 Tasks and Steps

### 1. Data Exploration and Preprocessing
- Loaded dataset and inspected summary statistics, missing values, and data types.
- Handled missing values using appropriate methods (e.g., imputation or removal).
- Applied scaling techniques for numerical features:
  - Standard Scaling
  - Min-Max Scaling
- Explained scenarios where each scaling technique is preferred.

### 2. Encoding Techniques
- Applied **One-Hot Encoding** for categorical variables with less than 5 categories.
- Applied **Label Encoding** for categorical variables with more than 5 categories.
- Discussed pros and cons of each encoding technique.

### 3. Feature Engineering
- Created at least 2 new features beneficial for model performance.
- Applied a transformation (e.g., log transformation) to skewed numerical features with justification.

### 4. Feature Selection
- Used **Isolation Forest** to identify and remove outliers.
- Applied **Predictive Power Score (PPS)** to examine relationships between features and compare with correlation analysis.

---

## 📊 Tools and Libraries
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook / Google Colab
- scikit-learn for preprocessing, scaling, encoding, and outlier detection
- ppscore for feature relationship analysis

---

## 📌 Key Insights
- Cleaned and preprocessed data suitable for ML modeling.
- Engineered new features improving model interpretability.
- Identified and removed outliers to reduce model bias.
- Highlighted relationships between features for better feature selection.

---

## 📂 Deliverables
- Jupyter Notebooks EDA1.ipynb EDA2.ipynb with full analysis: code, visualizations, and explanations.
- Processed dataset ready for modeling.

---
