# 🧠 Stroke Dataset – Exploratory Data Analysis (EDA)

This repository contains an **Exploratory Data Analysis (EDA)** performed on a **Stroke dataset** using **Python**.  
The goal of this analysis is to understand the data structure, handle missing values, and uncover patterns related to stroke occurrence before any model building.

---

## 📊 Dataset Overview

The dataset includes both **categorical** and **numerical** features related to patient demographics, health conditions, and lifestyle factors.

### Key Columns
- **Categorical Features**
  - gender  
  - hypertension (0/1)  
  - heart_disease (0/1)  
  - ever_married  
  - work_type  
  - Residence_type  
  - smoking_status  
  - stroke (target variable)

- **Numerical Features**
  - age  
  - avg_glucose_level  
  - bmi  

---

## 🛠️ Work Done in This EDA

### 1️⃣ Data Understanding
- Inspected dataset structure
- Identified numerical and categorical columns
- Checked for missing values column-wise

### 2️⃣ Missing Value Handling
- Identified missing values in the **BMI** column
- Applied appropriate imputation to handle missing data
- Verified that all missing values were handled successfully

### 3️⃣ Data Sanity Checks
- Checked for invalid or inconsistent values
- Ensured numerical columns had valid ranges
- Verified data consistency before analysis

### 4️⃣ Exploratory Analysis
- Univariate analysis for numerical features
- Frequency analysis for categorical variables
- Visualizations to understand distributions and patterns

---

## 📈 Key Insights

- Age shows a strong relationship with stroke occurrence  
- Health conditions such as **hypertension** and **heart disease** are important indicators  
- Data preprocessing significantly improves clarity of insights  
- Proper handling of missing values is essential before further analysis  

---

## 🧰 Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Repository Structure

stroke_dataset_eda.ipynb : Jupyter notebook containing complete exploratory data analysis

stroke-data.csv : Stroke dataset used for analysis

README.md : Project documentation and overview


---

## 🚀 Next Steps

- Outlier detection using boxplots  
- Feature engineering  
- Preparing data for machine learning models  

---

⭐ If you find this analysis useful, feel free to explore the notebook and provide feedback.
