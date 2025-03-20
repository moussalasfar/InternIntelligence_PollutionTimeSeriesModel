# 🌍 Time Series Forecasting for Air Pollution  

## 📌 Project Overview  
This project focuses on predicting **air pollution levels** using **time series forecasting** techniques. By analyzing historical air quality data (2000-2016, USA), we can anticipate future trends and support proactive environmental policies.  

## 📊 Dataset  
- **Features**:  
  - **NO2 (Nitrogen Dioxide)**  
  - **O3 (Ozone)**  
  - **SO2 (Sulfur Dioxide)**  
  - **CO (Carbon Monoxide)**  
  - **Timestamp (Daily)**  

## 🚀 Methodology  
### 1️⃣ **Data Preprocessing**  
✔ Handled missing values  
✔ Extracted time-based features (Year, Month, Day, Season)  
✔ Visualized seasonal trends in pollution levels  

### 2️⃣ **Model Development**  
✔ Applied **ARIMA** model for time series forecasting  
✔ Used exogenous variables to improve predictions  
✔ Split data into **training (80%)** and **testing (20%)** sets  

### 3️⃣ **Model Evaluation**  
✔ Performance metrics:  
   - **Mean Absolute Error (MAE)**  
   - **Root Mean Squared Error (RMSE)**

✔ Compared actual vs. predicted values with visualizations  

## 📈 Results & Insights  
🔹 Pollution levels tend to **drop during holidays** due to reduced traffic  
🔹 **ARIMA model** effectively captures seasonal variations  
🔹 Predictive models can help governments create **better air quality policies**  

## 🛠️ Tech Stack  
🔹 **Python** (Pandas, NumPy, Matplotlib)  
🔹 **Statsmodels** (ARIMA)  
🔹 **Scikit-learn**  
🔹 **Google Colab** (for model development)  

## 📌 How to Run  
1️⃣ **Clone the repository**  
```bash
git clone https://github.com/moussalasfar/InternIntelligence_PollutionTimeSeriesModel.git
cd InternIntelligence_PollutionTimeSeriesModel
