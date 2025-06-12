# 🌍 SDG 13: Climate Action – Forecasting Carbon Emissions Using Machine Learning

## 📘 Project Overview

This project supports **Sustainable Development Goal 13: Climate Action** by forecasting **carbon dioxide (CO₂) emissions** using machine learning regression models. By predicting future emission trends, this project aims to support policy makers, climate researchers, and environmental organizations in developing timely interventions for carbon reduction.

---

## 🎯 Problem Statement

Carbon emissions are a key driver of global climate change. Forecasting future CO₂ emission levels using historical and socio-economic data can help in:

- Anticipating the environmental impact of current trends
- Supporting sustainable policy decisions
- Identifying high-emission sectors or regions for targeted action

---

## 🤖 Machine Learning Approach

- **Type**: Supervised Learning
- **Task**: Regression (Predict continuous emission values)
- **Models Used**:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor

---

## 📊 Dataset and Tools

### Datasets

- [World Bank Open Data](https://data.worldbank.org)
- [UN SDG Global Database](https://unstats.un.org/sdgs/indicators/database/)
- [Kaggle – CO2 Emissions Dataset](https://www.kaggle.com/datasets)

**Features include**:
- Yearly carbon emissions (in metric tons)
- Energy consumption (fossil fuel %, renewables %, electricity use)
- GDP per capita
- Urbanization rate
- Population size

### Tools and Libraries

- Python 3.9
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 🏗️ Model Development Workflow

### 1. Preprocessing

- Handled missing values and duplicates
- Feature scaling using StandardScaler
- Train-test split (80-20)

### 2. Training

- Implemented multiple regression models
- Cross-validated using 5-fold CV

### 3. Evaluation Metrics

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score
- Visualizations: Residual plots, prediction vs actual graphs

## ⚖️ Ethical Reflection

### Bias & Fairness

- **Bias Risks**: Data quality and diverse representation of data.
- **Mitigation**: Included a diverse set of countries and normalized data across economic variables.

### Promoting Sustainability

- **Impact**: Helps identify future carbon emission hotspots and supports long-term sustainable planning.
- **Access**: Uses open data and transparent models to allow adaptation for regional use.

---

## 📁 Repository Structure

