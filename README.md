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

---

## 🔍 Exploratory Data Analysis (EDA)

Key analyses performed:
- Distribution of earthquake magnitudes  
- Scatter plot: **Depth vs Magnitude**  
- Heatmap of earthquake locations (Latitude vs Longitude)  
- Time-series trend of average earthquake magnitude over years  

---

## 🛠 Feature Engineering

New features extracted from the datetime column:
- Year  
- Month  
- Day  
- Hour  

These features help capture temporal patterns in earthquake occurrences.

---

## 🤖 Models Used

### 1️⃣ Linear Regression
- Baseline regression model  
- Used to understand linear relationships between features and magnitude  

### 2️⃣ Random Forest Regressor
- Ensemble model using multiple decision trees  
- Captures non-linear relationships  
- Feature importance analysis performed  

---

## 📈 Model Evaluation

- Evaluation Metric: **Root Mean Squared Error (RMSE)**  
- RMSE provides an interpretable measure of prediction error in magnitude units  

**Results:**
- Linear Regression RMSE: ~0.428  
- Random Forest RMSE: ~0.429  

---

## 📊 Visualizations Included
- Earthquake location heatmap  
- Time-series plot of average magnitude over years  
- Feature importance bar chart (Random Forest)  

These improve interpretability and storytelling.

---

## 🚀 Future Improvements
- Hyperparameter tuning for Random Forest  
- Try advanced models (XGBoost, Gradient Boosting)  
- Incorporate tectonic plate data  
- Build an interactive dashboard (Plotly / Power BI)  

---

## 🧰 Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📜 License
This project is licensed under the **MIT License**.

