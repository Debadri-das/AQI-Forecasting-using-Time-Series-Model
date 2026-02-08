# AQI-Forecasting-using-Time-Series-Model
Time series forecasting analysis of Air Quality Index (AQI) of a city using classical statistical models and deep learning. Academic project demonstrating complete ML pipeline from data acquisition to model evaluation.

## 🎯 Project Objectives
- Download historical AQI data from reliable Indian government sources
- Apply 3+ time series algorithms for pollution forecasting
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

### Key Technical Features
