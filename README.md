# 📈 Forecasting Food Pricing Using Time Series Analysis in R

## 📌 Project Overview

This project focuses on forecasting food commodity prices using **Time Series Analysis** and the **ARIMA (Autoregressive Integrated Moving Average)** model in **R Studio**. Historical monthly food price data was analyzed to identify trends, seasonality, and future price movements. The project demonstrates how predictive analytics can support data-driven decision-making in agriculture, supply chain management, and business planning.

This project was completed as part of my **Summer Internship at MedTourEasy**.

---

## 🎯 Objectives

- Import and clean historical food price data.
- Perform Exploratory Data Analysis (EDA).
- Convert the dataset into time series objects.
- Test stationarity using the Augmented Dickey-Fuller (ADF) Test.
- Analyze Auto-Correlation Function (ACF) and Partial Auto-Correlation Function (PACF).
- Develop ARIMA forecasting models.
- Forecast future prices of selected food commodities.
- Generate business insights based on forecast results.

---

## 📂 Dataset

The historical food price dataset was provided by **MedTourEasy** for academic and internship purposes.

**Selected Commodities**
- Beans (Dry)
- Irish Potatoes

**Time Period**
- 2008 – 2015

**Frequency**
- Monthly

---

## 🛠️ Technologies Used

- R Programming
- R Studio
- readr
- dplyr
- lubridate
- ggplot2
- forecast
- tseries
- magrittr

---

## 📊 Project Workflow

```text
Historical Food Price Dataset
            │
            ▼
      Data Import
            │
            ▼
      Data Cleaning
            │
            ▼
 Exploratory Data Analysis
            │
            ▼
 Time Series Conversion
            │
            ▼
 Stationarity Test (ADF)
            │
            ▼
   ACF & PACF Analysis
            │
            ▼
  ARIMA Model Development
            │
            ▼
    Price Forecasting
            │
            ▼
   Business Insights
```

---

## 📁 Repository Structure

```
Forecasting-Food-Pricing-Using-Time-Series-Analysis-in-R
│
├── data/
├── scripts/
├── graphs/
├── output/
├── report/
├── presentation/
└── README.md
```

---

## 📈 Analysis Performed

✔ Data Cleaning

✔ Historical Price Trend Analysis

✔ Time Series Conversion

✔ Stationarity Testing (ADF Test)

✔ ACF Analysis

✔ PACF Analysis

✔ ARIMA Model Selection

✔ 12-Month Price Forecasting

✔ Forecast Interpretation

✔ Business Insights

---

## 📉 Results

The ARIMA forecasting models successfully captured historical price behaviour and generated reliable forecasts for both selected commodities.

### Irish Potatoes

- Selected Model: **ARIMA(4,0,0)(2,1,1)[12] with Drift**
- RMSE: **9.82**
- MAE: **7.33**
- MAPE: **4.54%**

The model demonstrated good forecasting accuracy and effectively captured seasonal price movements.

---

## 📷 Visualizations

The project includes:

- Historical Price Trend
- Stationarity Plots
- ACF Plots
- PACF Plots
- ARIMA Forecast Plots

All graphs were generated using **R Studio**.

---

## 💼 Business Insights

The forecasting results can support:

- Agricultural Price Forecasting
- Procurement Planning
- Inventory Management
- Supply Chain Optimization
- Market Trend Analysis
- Data-Driven Decision Making

---

## 🚀 Future Improvements

- Compare ARIMA with Prophet and LSTM models.
- Develop an interactive forecasting dashboard using Shiny.
- Integrate real-time food price data.
- Extend forecasting to additional food commodities.

---

## 📚 Source

Historical food price dataset provided by **MedTourEasy**.

All analysis, visualizations, and forecasting models were developed using **R Studio**.

---

## 👩‍💻 Author

**Mahek Manilal Gupta**

MBA (Finance)

Balaji Institute of Modern Management (BIMM)

Sri Balaji University, Pune

### Skills

- Financial Analytics
- Business Analytics
- Time Series Forecasting
- R Programming
- Python
- SQL
- Power BI
- Excel
- Data Visualization

---

