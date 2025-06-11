# U.C.-Berkely-Assignments
Professional Certificate in Machine Learning and Artificial Intelligence

""" 
# 🚗 Module 11: Used Car Price Prediction with Machine Learning

This project explores a dataset of over 400,000 used vehicles to identify the key features that influence car prices. Using data preprocessing and machine learning models, we built a predictive model that helps used car dealerships make data-driven decisions.

---

## 📊 Project Objective

To determine the **most significant predictors** of used car prices using regression analysis and feature importance. This insight can be used to guide **inventory acquisition**, **pricing strategy**, and **marketing focus** for a used car dealership.

---

## 🧾 Dataset

- **Source:** Kaggle
- **Original Size:** ~3 million records  
- **Processed Subset:** ~426,000 entries (for speed & memory efficiency)

**Key Features:**
- `price` (target variable)
- `odometer`, `year`, `price_per_mile`
- `fuel_type`, `vehicle_type`, `state`, `title_status`, etc.

---

## 🧪 Methodology (CRISP-DM Framework)

### 1. Business Understanding
- Understand what vehicle attributes affect resale value.
- Determine which features dealerships should prioritize.

### 2. Data Understanding
- Visualized price distribution
- Evaluated correlations via heatmap

### 3. Data Preparation
- Removed outliers (e.g., prices > $100,000)
- Handled missing values with `SimpleImputer`
- Encoded categorical variables using `OneHotEncoder`

### 4. Modeling
- Trained multiple models (Linear Regression, Random Forest)
- Final model: **RandomForestRegressor**

### 5. Evaluation
- R² Score: **0.8213**
- MAE (Mean Absolute Error): **$10,247.73**

---

## 🔍 Key Insights

| Rank | Feature         | Insight Summary |
|------|------------------|-----------------|
| 1    | `odometer`       | Strongest negative impact; low mileage = higher price |
| 2    | `price_per_mile` | Indicates perceived value; high scores = premium vehicles |
| 3    | `state_nj`       | Regional pricing variation found in NJ |
| 4    | `fuel_gas`       | Traditional fuel types still dominant |
| 5    | `type_pickup`    | Pickup trucks show strong price retention |

---

## 📈 Visualizations

- 📉 **Price Distribution Histogram**
- 🔥 **Correlation Heatmap**
- 📊 **Top Feature Importances** (bar chart)

---

## 📁 Files

- `car analysis.ipynb`: Main notebook with full analysis
- `Module 11 for submission.ipynb`: Final notebook for grading
- `README.md`: Project summary

---

## 🚀 Future Improvements

- Add more granular location data (city-level)
- Include time-on-market as a feature
- Try gradient boosting models (e.g., XGBoost, LightGBM)

---

## 🤝 Acknowledgments

Thanks to [Kaggle](https://www.kaggle.com) for the dataset and U.C. Berkley for the module framework.--

""""
