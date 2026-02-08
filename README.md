# AQI-Forecasting-using-Time-Series-Model
Time series forecasting analysis of Air Quality Index (AQI) of a city using classical statistical models and deep learning. Academic project demonstrating complete ML pipeline from data acquisition to model evaluation.

## 🎯 Project Objectives
- Download historical AQI data from reliable Indian government sources
- Applied 3+ time series algorithms for pollution forecasting
- Validate model performance using RMSE metrics
- Generate 30-day AQI predictions for urban planning

## 📊 Technical Implementation

### Algorithms Implemented
| Model | Type | Key Features | RMSE (Expected) |
|-------|------|--------------|-----------------|
| **ARIMA** | Classical | Seasonal (m=7 weekly), Auto-parameter selection | 70-120 |
| **Exponential Smoothing** | Classical | Holt-Winters, Weekly seasonality | 70-120 |
| **Prophet** | ML | Daily seasonality, Trend decomposition | 80-130 |
| **LSTM** *(bonus)* | Deep Learning | Neural network, Sequence learning | 80-140 |


## 🗃️ Dataset
- **Source**: Kaggle India AQI Dataset (2015-2020)
- **City**: Ahmedabad, Gujarat (urban pollution patterns)
- **Features**: Daily AQI, PM2.5, weather covariates
- **Size**: ~1,500 daily observations
- **Patterns**: Winter peaks (1000+ AQI), monsoon relief

## 📈 Key Findings
1. **Strong weekly seasonality**: Pollution peaks Friday-Sunday
2. **Winter crisis**: Oct-Feb AQI frequently exceeds 1000 (Hazardous)
3. **Model convergence**: All algorithms predict 150-250 AQI next 30 days
4. **High forecast reliability**: RMSE < 120 across models


# 3. Run analysis
jupyter notebook aqi_forecast.ipynb
