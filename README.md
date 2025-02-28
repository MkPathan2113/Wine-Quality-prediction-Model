# 🍷 Wine Quality Prediction

## 📌 Project Overview
The **Wine Quality Prediction** project aims to build a **machine learning model** that predicts the quality of wine based on its **physicochemical properties**. The dataset contains **red and white wine samples**, each labeled with a quality score ranging from **0 to 10**.

## 📂 Dataset Information
The dataset is sourced from the **UCI Machine Learning Repository** and includes the following features:

### 🔬 **Physicochemical Properties**
- **Fixed Acidity** - Non-volatile acids contributing to tartness.
- **Volatile Acidity** - High values lead to an unpleasant vinegar taste.
- **Citric Acid** - Enhances flavor and adds freshness.
- **Residual Sugar** - Affects sweetness.
- **Chlorides** - Salt content in wine.
- **Free Sulfur Dioxide** - Helps prevent oxidation.
- **Total Sulfur Dioxide** - Used as a preservative.
- **Density** - Affected by sugar and alcohol content.
- **pH** - Determines acidity (scale: 0-14).
- **Sulphates** - Used as an antioxidant and preservative.
- **Alcohol** - Percentage of alcohol in wine.

### 🎯 **Target Variable**
- **Quality (0-10)** - A score assigned by wine experts.

## 📊 Exploratory Data Analysis (EDA)
- Checked for **missing values** and **duplicates**.
- Analyzed **feature distributions** and **correlations**.
- Found that **alcohol content** has a **strong positive correlation** with quality.
- Observed that most wines have a **quality score of 5 or 6** (~80%).

## 🛠️ Model Building
### 🔹 **Data Preprocessing**
- Removed **duplicate entries**.
- Used **StandardScaler** for feature normalization.
- Split data into **training (70%)** and **testing (30%)** sets.

### 🔹 **Machine Learning Models**
- **Linear Regression**
- **Random Forest Classifier** (Best Performance ✅)
- **Support Vector Machine (SVM)**

### 📈 **Model Evaluation**
| Model | RMSE | R² Score |
|--------|------|---------|
| **Linear Regression** | High | Low |
| **Random Forest Classifier** | Best | High |
| **SVM** | Moderate | Moderate |

The **Random Forest Classifier** achieved the best accuracy.  

## 🚀 Future Improvements
- **Hyperparameter tuning** for better performance.
- **Deep Learning models** for advanced predictions.
- **Ensemble techniques** to enhance model accuracy.
- **Expand dataset** for broader applicability.

