# Earthquake Magnitude Prediction 🌍

This project performs **Exploratory Data Analysis (EDA)** and builds **machine learning models** to predict earthquake magnitude using historical earthquake data.

---

## 📌 Project Objectives
- Understand earthquake patterns using EDA
- Engineer meaningful time-based features
- Build and compare regression models
- Evaluate models using RMSE
- Visualize spatial and temporal earthquake trends

---

## 📊 Dataset Overview
The dataset contains global earthquake records with:
- Location information (Latitude, Longitude)
- Depth of the earthquake
- Date and time of occurrence
- Magnitude (target variable)

Missing and low-quality columns were removed during preprocessing.

---

## 🔍 Exploratory Data Analysis (EDA)
Key analyses performed:
- Distribution of earthquake magnitudes
- Scatter plot: **Depth vs Magnitude**
- Heatmap of earthquake locations
- Time-series trend of average magnitude over years

---

## 🛠 Feature Engineering
New features were extracted from datetime:
- Year
- Month
- Day
- Hour

These features help capture temporal patterns in earthquakes.

---

## 🤖 Models Used

### 1️⃣ Linear Regression
- Baseline regression model
- Used to understand linear relationships

### 2️⃣ Random Forest Regressor
- Ensemble model using multiple decision trees
- Captures non-linear relationships
- Provides feature importance insights

---

## 📈 Model Evaluation
Evaluation metric used:
- **RMSE (Root Mean Squared Error)**

| Model | RMSE |
|------|------|
| Linear Regression | ~0.43 |
| Random Forest | ~0.43 |

Random Forest performed slightly better and provided interpretability through feature importance.

---

## 🔑 Key Insights
- Earthquake magnitude shows **weak linear relation** with depth
- Location (latitude & longitude) is the strongest predictor
- Temporal features add moderate predictive value
- Random Forest handles complexity better than Linear Regression

---

## 🚀 Future Improvements
- Hyperparameter tuning for Random Forest
- Try Gradient Boosting / XGBoost
- Predict earthquake **severity categories**
- Interactive visualizations using Plotly or Folium

---

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 👤 Author
**Harshita Pasupulety**  
Graduate Student | Data Analytics & Machine Learning  
