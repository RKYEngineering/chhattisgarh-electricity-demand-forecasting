# ⚡ Chhattisgarh Electricity Demand Forecasting

A time series forecasting project analyzing electricity consumption patterns across Chhattisgarh using Python and Prophet.

---

## 📌 Project Overview

This project explores electricity consumption across Chhattisgarh at the **division and monthly level**. The analysis focuses on identifying long-term trends, seasonal variations, and regional differences influenced by factors such as industrial activity, urbanization, and temperature.

The dataset is aggregated at the monthly level to perform time series analysis and forecasting.

---

## 🎯 Objectives

* Analyze electricity consumption trends over time
* Identify seasonal patterns in electricity demand
* Compare consumption across different divisions
* Understand the impact of temperature, industrialization, and urbanization
* Forecast future electricity demand using time series modeling

---

## 📊 Dataset

The dataset contains **50,000 records** of electricity consumption data from **2012 to 2022** across multiple divisions in Chhattisgarh.

### Features include:

* Division
* Consumer Category
* Consumption (KWH, KW)
* Charges (KWH, KW, Fixed, Other)
* Temperature
* Industrial Index
* Urbanization Level
* Revenue Month

> Note: The dataset is synthetically generated but designed to reflect realistic electricity consumption patterns.

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Prophet (Time Series Forecasting)
* Scikit-learn

---

## 🔍 Key Analysis

### 📈 Trend Analysis

* Electricity demand shows a consistent upward trend from 2012 to 2022

### 🔁 Seasonality

* Higher consumption in **summer months (April–June)**
* Lower consumption in **winter months (December–January)**

### 🏭 Division-wise Insights

* Higher consumption in **Durg and Raipur divisions** (industrial & urban regions)
* Lower consumption in **Bastar and Surguja divisions** (rural & forest regions)

### 🔗 Correlation Analysis

* Strong positive correlation between:

  * Consumption & Industrial Index
  * Consumption & Urbanization Level
* Moderate relationship with temperature

### ⚠️ Outliers

* High consumption spikes observed, representing industrial demand variations

---

## 🤖 Forecasting Model

A **Prophet time series model** was used to forecast electricity consumption.

### Key Results:

* Successfully captured **trend and seasonality**
* Forecast shows **continued increase in electricity demand**
* Predictions align closely with actual values

---

## 📉 Model Evaluation

* RMSE: ~526,000
* MAE: ~409,000

Despite appearing large, these errors are small relative to the scale of consumption (millions), indicating good model performance.

---

## 📊 Results

* Clear upward trend in electricity demand
* Strong seasonal patterns
* Significant regional differences
* Reliable future forecasts

---

## 🏁 Conclusion

The analysis demonstrates that electricity consumption in Chhattisgarh is increasing over time with strong seasonal variations. Industrial activity and urbanization are key drivers of demand.

The forecasting model provides reliable predictions, highlighting the importance of efficient energy planning to meet future demand.

---

## 📁 Project Structure

```
chhattisgarh-electricity-demand-forecasting/
│
├── data/
│   └── chhattisgarh-electricity-consumption-2012-2022.csv
│
├── Electricity_Demand_Forecasting_Chhattisgarh_Presentation.ppt
├── README.md
├── cg_power_banner.png 
├── chhattisgarh_power_forecasting.ipynb

```

---

## 🚀 Future Improvements

* Incorporate real-world datasets
* Add weather API integration
* Build interactive dashboards (Power BI / Streamlit)
* Improve model with additional features

---

## 👨‍💻 Author

Ritik Kumar Yadav 
M.Tech Student | Aspiring Data Analyst 
Developed as part of M.Tech research and data analytics portfolio.

- LinkedIn: https://www.linkedin.com/in/ritik-kumar-yadav-70a81435a/
- GitHub: https://github.com/RKYEngineering
  
---

## ⭐ If you found this useful, give it a star!
