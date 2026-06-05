# ML-1---Air-Quality-Prediction
Air Quality Prediction using Meta Prophet
# AQI Forecasting with Prophet

Time series forecasting of Air Quality Index (AQI) 
for Ahmedabad using Facebook Prophet.

## Dataset
- 26 Indian cities, daily AQI reading
- Features: no, o3, so2, pm10, pm2_5, no2, co, nh3
- Source: air_pollution_data.csv

## Model
- Facebook Prophet with logistic growth
- External regressors: pm10, pm2_5, no2, co, nh3
- Yearly and weekly seasonality

## Results
| Metric | Score |
|--------|-------|
| MAE    | 0.81  |
| RMSE   | 0.95  |
| R²     | 0.00  |

## Usage
1. Install dependencies
2. Open `notebook.ipynb`
3. Run all cells
