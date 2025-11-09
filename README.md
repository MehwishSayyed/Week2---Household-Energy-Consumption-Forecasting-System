# ⚡ Electric Power Consumption Prediction using Random Forest

This project predicts **household electric power consumption** using the **UCI Individual Household Electric Power Consumption Dataset**.  
The goal is to accurately forecast **Global Active Power** based on features such as voltage, reactive power, current, and sub-meter readings.

---

## 📘 Project Overview

This notebook demonstrates the full pipeline of a **Machine Learning regression project**:

1. **Data Loading** – Imported directly from the UCI Machine Learning Repository  
2. **Data Cleaning** – Handled missing values, replaced `'?'` with NaN, interpolated time-series data  
3. **Feature Engineering** – Combined date and time columns, removed outliers, and converted all data to numeric types  
4. **Model Training** – Used **Random Forest Regressor** for prediction  
5. **Model Evaluation** – Evaluated using metrics like R², MAE, MSE, and MAPE  
6. **Visualization** – Compared actual vs predicted power consumption using scatter plots and line charts  

---

## 🧠 Key Features

- Cleaned and preprocessed 1.9 million energy data points  
- Used Random Forest for robust and high-accuracy regression  
- Achieved **R² = 0.998** and **Average Accuracy ≈ 96.7%**  
- Generated performance visualizations:
  - Actual vs Predicted Scatter Plot  
  - Residual Distribution  
  - Feature Importance Plot  

---

## 📊 Dataset Information

**Dataset Name:** Individual Household Electric Power Consumption  
**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)  
**Rows:** ~2 million  
**Columns:**
- `Global_active_power` — Total active power consumed (Target)  
- `Global_reactive_power` — Reactive power  
- `Voltage` — Average voltage  
- `Global_intensity` — Average current  
- `Sub_metering_1`, `Sub_metering_2`, `Sub_metering_3` — Energy consumption in different household areas  

---

## 🧰 Tech Stack

- **Python 3**
- **Pandas**, **NumPy** — Data manipulation  
- **Scikit-learn** — Model training and evaluation  
- **Matplotlib**, **Seaborn** — Visualization  
- **ucimlrepo** — Fetch dataset from UCI repository  

---

## 🧪 Model Evaluation Results

| Metric | Value |
|--------|--------|
| **R² Score** | 0.998 |
| **Mean Absolute Error (MAE)** | 0.0176 |
| **Mean Squared Error (MSE)** | 0.00098 |
| **Average Accuracy** | 96.67% |
| **Mean Absolute Percentage Error (MAPE)** | 3.32% |

✅ These results show the model predicts energy usage with extremely high precision.

---

## 📈 Visualizations

- **Actual vs Predicted Scatter Plot**
- **Residual Distribution**
- **Feature Importance Bar Chart**

These plots help visualize how close predictions are to actual values and which features influence power usage the most.

---

## 🚀 How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

2. Install required dependencies

       pip install 


3. Open the notebook

       jupyter notebook Electric_Power_Prediction.ipynb
  

4. Run all cells sequentially to reproduce results.


🏁 Results Summary

The Random Forest model provides near-perfect predictions for household energy consumption.
It can be extended for real-time power monitoring, energy efficiency analysis, or smart grid applications.

🌟 Acknowledgments

UCI Machine Learning Repository for the dataset

Scikit-learn Team for ML tools

Google Colab for providing a free compute environment
