# 🍷 Red Wine Quality Analysis (EDA)

 ![Python](https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
---
 
## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Red Wine Quality dataset to identify the key factors influencing wine quality.

The analysis aims to:
- 📊 Understand feature distributions  
- 🔍 Discover hidden patterns  
- 📈 Identify relationships between variables  
- 🧠 Generate insights for predictive modeling  

---

## 📂 Dataset Details
- 📁 Source: UCI Machine Learning Repository  
- 🍷 Dataset: Red Wine Quality  
- 📊 Records: 1599 samples  
- 🔢 Features: 11 input variables + 1 target variable  

 ### 🔑 Features Description:

- **Fixed Acidity** → Non-volatile acids in wine  
- **Volatile Acidity** → Acetic acid content  
- **Citric Acid** → Freshness indicator  
- **Residual Sugar** → Sugar after fermentation  
- **Chlorides** → Salt content  
- **Free Sulfur Dioxide** → Prevents microbial growth  
- **Total Sulfur Dioxide** → Combined SO2  
- **Density** → Mass/volume ratio  
- **pH** → Acidity level  
- **Sulphates** → Preservative & antioxidant  
- **Alcohol** → Alcohol percentage  
- **Quality** → Wine quality score (Target)  

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## 📊 EDA Workflow

### 🔹 1. Data Understanding
- Shape, structure, and summary statistics
- Data types inspection

### 🔹 2. Data Cleaning
- Checked for missing/null values
- Verified dataset consistency

### 🔹 3. Univariate Analysis
- Distribution plots (Histograms, KDE)
- Skewness detection

### 🔹 4. Bivariate Analysis
- Feature vs Quality relationships
- Boxplots & scatter plots

### 🔹 5. Correlation Analysis
- Heatmap visualization
- Identified strong/weak correlations

---

## 📈 Key Insights

- 🍷 **Alcohol** shows a strong positive correlation with quality  
- ⚠️ **Volatile acidity** negatively impacts wine quality  
- 🧪 **Sulphates** contribute positively to quality  
- 📊 Most variables have **weak to moderate correlation**, indicating multi-factor influence  

---

## 📸 Sample Visualizations
```markdown
![Heatmap](images/heatmap.png)
![Distribution](images/distribution.png)
