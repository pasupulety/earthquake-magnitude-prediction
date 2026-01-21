# 🌍 Earthquake Magnitude Prediction

This project performs **Exploratory Data Analysis (EDA)** and builds **machine learning models** to predict earthquake magnitude using historical global earthquake data.

---

## 📌 Project Objectives
- Understand earthquake patterns using EDA  
- Engineer meaningful time-based features  
- Build and compare regression models  
- Evaluate models using RMSE  
- Visualize spatial and temporal earthquake trends  

---

## 📊 Key Results & Insights
- **Linear Regression RMSE:** ~0.428  
- **Random Forest RMSE:** ~0.429  
- Tree-based models captured non-linear patterns but showed similar performance  
- Earthquake magnitude is influenced most by:
  - Latitude  
  - Longitude  
  - Depth  
- Temporal features (Year, Month, Hour) showed lower predictive impact  

---

## 📁 Dataset Overview
The dataset contains global earthquake records with:
- Location information (Latitude, Longitude)  
- Depth of the earthquake  
- Date and time of occurrence  
- Magnitude (target variable)  

Missing and low-quality columns were removed during preprocessing.

---

## 📂 Project Structure

```text
earthquake-magnitude-prediction/
├── 01_data_exploration.ipynb   # EDA, feature engineering, modeling
├── database.csv               # Raw earthquake dataset
├── README.md                  # Project documentation
├── LICENSE                    # MIT License
└── .gitignore                 # Ignored files
