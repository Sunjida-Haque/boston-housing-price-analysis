# 🏡 Analytics for Business: Predicting House Prices with Statistical Modeling

This project is part of the *Analytics for Business* course (A220A0752) at LUT School of Business and Management. It demonstrates how data analytics, statistical modeling, and critical thinking can uncover the key factors influencing real estate prices.

We analyzed the **Boston Housing Dataset** using three regression techniques to answer the central question:

> ✨ What are the most critical factors influencing house prices?

---

## 🎯 Objective

To identify, evaluate, and compare the most significant predictors of residential property prices in urban areas using analytical techniques and models. The study aims to:
- Understand the relationship between socio-economic, environmental, and infrastructural features and house prices.
- Compare linear, ridge, and decision tree regression models for interpretability and accuracy.
- Provide actionable insights for policy makers and urban developers.

---

## 📊 Methodology

The following steps were conducted using MATLAB:

### 1. **Data Understanding & Preparation**
- Dataset: 506 observations, 13 predictors, 1 target variable (MEDV - Median value of owner-occupied homes).
- No missing values; handled outliers.
- Standardized all features.

### 2. **Exploratory Data Analysis**
- Generated boxplots and histograms to visualize data distribution and detect outliers.
- Created a correlation heatmap to explore relationships between variables.

### 3. **Model Development**
Three models were built and compared:
- **Linear Regression**
- **Ridge Regression** (with cross-validated lambda for regularization)
- **Decision Tree Regression** (with hyperparameter tuning)

### 4. **Model Evaluation**
- Split data: 70% training, 15% validation, 15% test
- Metric: Mean Squared Error (MSE)

---

## 📈 Key Results

| Model             | Validation MSE | Test MSE |
|------------------|----------------|----------|
| Linear Regression| 14.42          | 17.28    |
| Ridge Regression | 45.83          | 44.11    |
| Decision Tree    | **8.92**       | **11.77**|

🔍 **Decision Tree** achieved the lowest error, indicating its strength in capturing complex patterns, though at risk of overfitting.

---

## 🧠 Insights

- `LSTAT` (lower status population %) and `RM` (average rooms per dwelling) were the most influential variables across models.
- Socio-economic and environmental factors significantly affect property values.
- Ridge regression struggled due to model complexity and over-regularization.

---

## 🧑‍💻 Tools & Skills Demonstrated

- 📈 Statistical Modeling (Linear, Ridge, Decision Tree)
- 📊 Data Visualization
- 🧹 Data Cleaning & Outlier Detection
- 🧠 Feature Engineering & Interpretation
- 💡 Team Collaboration and Presentation
- 👨‍💻 MATLAB scripting and automation

---

## 👥 Team Members

- **Saleh Shahbaz** – Data selection, MATLAB coding, visualizations, formatting
- **Sunjida Haque** – EDA interpretation and results
- **Nicolas Pauli** – Background research, report writing, presentation
- **Arttu Rytkönen** – Modeling, evaluation, correlation analysis

---

## 📎 Files Included

- `report.pdf`: Full write-up of the assignment, findings, and graphs  
- `BA_Group_updated.mlx`: MATLAB Live Script with code for all data analysis and modeling  
- `README.md`: This file  

---

## 💬 Final Thoughts

This project reflects our enthusiasm for data-driven storytelling and our ability to turn raw data into actionable insight. It represents our confidence in analytical thinking, statistical programming, and effective collaboration.

📫 For questions or collaboration, feel free to connect on [LinkedIn](https://www.linkedin.com) or contact me via GitHub!

