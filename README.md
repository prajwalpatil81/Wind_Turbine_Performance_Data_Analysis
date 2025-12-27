# 🌬️ Wind Turbine Performance Data Analysis

## 📌 Project Overview
This project performs an end-to-end **exploratory data analysis (EDA)** and **statistical analysis** on wind turbine operational data.  
The objective is to understand turbine performance, power generation efficiency, and the relationship between wind characteristics and actual power output.

The analysis includes:
- Data cleaning and preprocessing
- Outlier detection and treatment
- Descriptive and inferential statistics
- Power curve and efficiency analysis
- Temporal, seasonal, and directional insights
- Correlation analysis and visualizations

---

## 📊 Dataset Description
The dataset contains time-series data recorded from a wind turbine, including:

| Feature | Description |
|------|------------|
| Date/Time | Timestamp of observation |
| LV ActivePower (kW) | Actual power generated |
| Wind Speed (m/s) | Measured wind speed |
| Theoretical_Power_Curve (kWh) | Expected power output |
| Wind Direction (°) | Wind direction in degrees |

Additional features such as **hour, day, month, season, efficiency, and time-of-day** are engineered during preprocessing.

---

## 🧰 Technologies Used
- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **SciPy** – Statistical analysis
- **Jupyter Notebook / Python Script**

---

## ⚙️ Project Workflow
1. Import required libraries  
2. Load and inspect dataset  
3. Data type conversion & feature engineering  
4. Missing value treatment  
5. Duplicate and outlier handling (IQR & Z-score)  
6. Descriptive statistical analysis  
7. Exploratory data analysis (EDA)  
8. Efficiency and power curve analysis  
9. Temporal & seasonal analysis  
10. Wind direction analysis  
11. Correlation analysis  

---

## 📈 Key Analyses & Visualizations
- Wind Speed vs Active Power (Power Curve)
- Actual vs Theoretical Power
- Efficiency distribution and trends
- Hourly, daily, monthly, and seasonal patterns
- Wind direction impact using polar plots
- Pearson & Spearman correlation heatmaps

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/prajwalpatil81/Wind_Turbine_Performance_Data_Analysis.git
cd your-repo-name
