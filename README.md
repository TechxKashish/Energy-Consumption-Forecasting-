# Energy-Consumption-Forecasting-

## Overview
Energy consumption forecasting is a critical task for efficient energy management. This project utilizes machine learning techniques to predict energy consumption based on historical data and weather conditions. By analyzing past usage trends and external factors, the model helps in optimizing resource allocation and reducing costs.

## Dataset
The dataset used in this project is the **Building Energy Consumption Dataset**, which contains:
- Energy consumption data (kWh)
- Weather attributes (temperature, humidity, wind speed, etc.)
- Time-based features (hour, day, month, etc.)

This dataset has been sourced from publicly available energy repositories that provide real-world data for analysis.

## Project Workflow
1. **Data Collection**: Importing and loading the dataset.
2. **Data Preprocessing**:
   - Handling missing values
   - Resampling time-series data
   - Creating additional time-based features
3. **Exploratory Data Analysis (EDA)**:
   - Visualizing energy consumption trends
   - Understanding correlations between weather conditions and energy usage
   - Identifying seasonality and patterns
4. **Machine Learning Models Used**:
   - **Support Vector Machine (SVM)**: Applied for regression but showed lower accuracy.
   - **Random Forest Regressor (RF)**: Provided better results due to its ability to capture complex patterns.
   - **Extreme Gradient Boosting (XGBoost)**: Performed the best with high accuracy and reduced errors.
5. **Model Evaluation**:
   - Metrics used: Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score
   - Comparison of model performances
6. **Predictions & Visualizations**:
   - Forecasting future energy consumption
   - Plotting actual vs predicted values

## Data Visualizations
To better understand the dataset, several plots are used:
- **Energy Consumption Over Time**: Line plots to observe consumption trends.
- **Histogram & Boxplots**: To study data distribution and outliers.
- **Correlation Heatmap**: To check relationships between features.
- **Temperature, Humidity & Wind Speed vs Energy Consumption**: Scatter plots showing their impact.
- **Feature Importance (XGBoost & Random Forest)**: Displays which factors influence energy usage the most.

## Model Performance
| Model  | MAE  | MSE  | R² Score |
|--------|------|------|----------|
| SVM    | High | High | Low      |
| RF     | Medium | Medium | Good    |
| XGBoost | Low | Low | Best     |

The XGBoost model outperformed the others, making it the best choice for accurate forecasting.

## Conclusion
This project demonstrates how machine learning can be used for energy consumption forecasting. The XGBoost model proved to be the most efficient in predicting energy usage. The insights gained can help businesses and organizations optimize their energy management strategies.

## Future Enhancements
- **Real-time Forecasting**: Integrate IoT sensors for real-time energy monitoring.
- **Deep Learning Models**: Experiment with LSTM/GRU networks for improved accuracy.
- **Energy Optimization**: Implement reinforcement learning to suggest energy-saving strategies.

---
This project serves as a foundation for data-driven energy forecasting, enabling better decision-making for sustainable energy consumption.

