### Arizona Electricity Demand Forecasting
#### Student: Assanali Kakenov

### Overview
This project forecasts residential electricity demand in Arizona using time series forecasting techniques. The dataset includes monthly electricity consumption and climate variables such as cooling and heating degree days.

### Dataset
Electricity consumption and climate datasets for Arizona are available in this repository:

electricity_resid_AZ.csv
climate_Phoenix_AZ

Variables used:
- Q : electricity demand
- CLDD : cooling degree days
- HTDD : heating degree days
- DX90 : days above 90°F

### Methodology
1. Exploratory Data Analysis
2. Stationarity test (ADF test)
3. Seasonal decomposition
4. ARIMA model
5. Forecast

### How to Run

Install required packages: pip install -r requirements.txt

Run the notebook: AssanaliKakenov_TimeSeriesForecasting.ipynb
