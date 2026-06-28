# Time-sereis-Project Intern ID: CITS2712
# Time Series Forecasting of Electricity Consumption

## Project Overview

This project aims to forecast electricity consumption using historical power usage data and time series forecasting techniques. Accurate electricity demand forecasting helps utility companies optimize power generation, reduce operational costs, improve grid reliability, and support efficient energy management.

---

## Business Problem

Electricity demand changes throughout the day due to factors such as weather conditions, holidays, weekdays, and consumer behavior. Incorrect demand forecasting can lead to:

- Power shortages
- Excess electricity generation
- Increased operational costs
- Inefficient resource allocation

The objective of this project is to build forecasting models that accurately predict future electricity consumption, enabling better planning and decision-making.

---

## Project Objectives

- Analyze historical electricity consumption data.
- Perform data cleaning and preprocessing.
- Identify trends, seasonality, and patterns.
- Build forecasting models.
- Compare model performance using evaluation metrics.
- Select the best-performing model for future predictions.

---

## Dataset Description

The dataset contains hourly electricity consumption records along with time-related features.

### Features

| Column | Description |
|---------|-------------|
| Datetime | Date and time of observation |
| PowerConsumption | Electricity consumed (kWh) |
| Hour | Hour of the day |
| Day | Day of the month |
| Month | Month |
| Weekday | Day of the week |
| IsWeekend | Weekend indicator |
| Holiday | Holiday indicator (if available) |

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Missing value analysis
- Duplicate value check
- Data type verification
- Statistical summary
- Time series visualization
- Trend analysis
- Seasonality analysis
- Rolling mean and rolling standard deviation
- Correlation analysis
- Distribution of electricity consumption

---

## Data Preprocessing

- Converted datetime column to datetime format
- Set datetime as the index
- Sorted observations chronologically
- Handled missing values
- Created lag features
- Generated rolling statistics
- Extracted time-based features
- Scaled data where required

---

## Models Used

The following forecasting models were implemented and compared:

- ARIMA
- SARIMA
- XGBoost
- LSTM (Long Short-Term Memory)

---

## Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score (for machine learning models)

The model with the lowest prediction error was selected as the final forecasting model.

---

## Results

The forecasting models successfully captured historical electricity consumption patterns and generated future demand predictions. Model comparison showed differences in forecasting accuracy, allowing selection of the most reliable model for deployment.

---

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- XGBoost
- TensorFlow / Keras

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Stationarity Testing
6. Model Building
7. Model Evaluation
8. Forecasting Future Electricity Consumption
9. Business Insights

---

## Future Improvements

- Incorporate weather data (temperature, humidity)
- Include holiday and special event information
- Experiment with Prophet and Transformer-based forecasting models
- Deploy the model as a real-time forecasting API
- Build an interactive dashboard for visualization

---

## Conclusion

This project demonstrates how time series forecasting techniques can accurately predict electricity consumption using historical data. The insights generated from the analysis can help utility providers optimize power generation, improve resource planning, reduce operational costs, and support data-driven decision-making.
