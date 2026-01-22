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
- Tree-based models captured non-linear patterns but showed similar performance to linear models  
- Earthquake magnitude is influenced most by:
  - Latitude  
  - Longitude  
  - Depth  
- Temporal features (Year, Month, Hour) showed lower predictive impact  

---

## 📈 Visualizations Included

- Earthquake location heatmap  
- Time-series plot of average magnitude over years  
- Feature importance bar chart (Random Forest)  
- Depth vs Magnitude scatter plot  
- Magnitude distribution histogram  

---

## 🔍 Visual Insights

### Average Magnitude Over Time
![Average Magnitude Over Time](https://raw.githubusercontent.com/pasupulety/earthquake-magnitude-prediction/main/images/avg_magnitude_over_time.png)

---

### Earthquake Location Heatmap
![Earthquake Heatmap](https://raw.githubusercontent.com/pasupulety/earthquake-magnitude-prediction/main/images/earthquake_heatmap.png)

---

### Feature Importance (Random Forest)
![Feature Importance](https://raw.githubusercontent.com/pasupulety/earthquake-magnitude-prediction/main/images/feature_importance.png)

---

### Depth vs Magnitude
![Depth vs Magnitude](https://raw.githubusercontent.com/pasupulety/earthquake-magnitude-prediction/main/images/depth_vs_magnitude.png)

---

### Distribution of Earthquake Magnitudes
![Magnitude Distribution](https://raw.githubusercontent.com/pasupulety/earthquake-magnitude-prediction/main/images/magnitude_distribution.png)

---

## 🧠 Conclusion & Insights

- Earthquake magnitude prediction is challenging due to complex geophysical factors  
- Tree-based models captured non-linear relationships but did not significantly outperform linear regression  
- Spatial features (Latitude, Longitude, Depth) were more influential than temporal features  
- This project demonstrates a complete ML workflow from **EDA → Feature Engineering → Modeling → Evaluation → Visualization**

---

## 🚀 Future Improvements

- Hyperparameter tuning for Random Forest  
- Try advanced models (XGBoost, Gradient Boosting)  
- Incorporate tectonic plate boundary data  
- Build an interactive dashboard (Plotly / Power BI)

---

## 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📄 License

This project is licensed under the **MIT License**.
