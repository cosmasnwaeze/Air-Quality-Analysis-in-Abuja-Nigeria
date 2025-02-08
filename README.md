# Air-Quality-Analysis-in-Abuja-Nigeria
Air Quality Analysis in Abuja, Nigeria using autoregression model for predicting PM2.5 readings an tuning hyperparameters to improve predictive accuracy

![Air Qaulity](https://i.postimg.cc/TY4L04Dg/AIR-QALTY.png)

## Introduction
Air pollution is a growing concern in urban environments, affecting public health and environmental sustainability. Monitoring air quality is essential for understanding pollution patterns and implementing effective mitigation strategies. This project aims to analyze air quality data from Abuja, Nigeria, using sensor-based particulate matter (PM) measurements.

## Objective
To analyze air quality data in Abuja using low-cost sensors and gain insights into PM concentration levels.

## Summary Objective
- Investigate air quality trends in Abuja using PM, temperature, and humidity data.
- Assess the relationship between particulate matter concentrations and environmental factors.
- Provide insights into pollution levels using data-driven approaches.
- Build a time series model to predict PM 2.5 readings throughout the day.
- Time series models are not only important in public health; to build an autoregression model.
- To improve a model by tuning its hyperparameters.

## Methodology
The project utilizes the **[sensors.AFRICA Air Quality Archive](https://open.africa/dataset/sensorsafrica-airquality-archive-abuja)** dataset, which includes PM1 (P0), PM2.5 (P2), and PM10 (P1) measurements, along with temperature and humidity readings. The dataset is stored in CSV format and will undergo preprocessing and analysis using data science techniques.

The analysis will include:
1. **Exploratory Data Analysis (EDA)** to understand the distribution and trends of air quality parameters.
2. **Data Preprocessing** to clean missing values and standardize sensor readings.
3. **Visualization Techniques** to display air pollution trends over time and across locations.
4. **Correlation Analysis** to examine the relationship between PM levels, temperature, and humidity.
5. **Time Series Analysis** to build an autoregression model for predicting PM2.5 readings throughout the day.
6. **Model Optimization** by tuning hyperparameters to improve predictive accuracy.

## Conclusion
This project will contribute to understanding air pollution trends in Abuja, Nigeria, using low-cost sensor data. The findings can help policymakers, researchers, and the general public take informed actions to improve air quality.

## Recommendations
Future research can focus on expanding the dataset, incorporating additional sensor locations, and developing predictive models for air pollution forecasting.

## Table of Contents

- [Importing Libraries](#importing-libraries)
- [Loading Data](#loading-data)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Analysis of Air Quality Trends](#analysis-of-air-quality-trends)
- [Time Series Modeling](#time-series-modeling)
- [Results](#results)

# ARIMA Model Performance and Insights on Air Quality in Abuja

## Model Performance

### Mean Absolute Error (MAE)
The MAE of **26.55** indicates that, on average, the model's predictions are off by approximately **26.55 units** from the actual values. This suggests that the model is reasonably accurate, but there is still some room for improvement.

### Root Mean Squared Error (RMSE)
The RMSE of **37.22** indicates that the model's predictions are more sensitive to larger errors. This suggests that there may be some outliers or unusual patterns in the data that the model is struggling to capture.

## Air Quality Insights

### General Trends
Based on the ARIMA model, it appears that the air quality in Abuja follows a relatively stable pattern, with some fluctuations over time. The model's ability to capture these patterns suggests that there may be some underlying factors driving the air quality, such as seasonal changes, weather patterns, or human activities.

### Potential Factors Influencing Air Quality
Given the location of Abuja, Nigeria, it's possible that the air quality is influenced by factors such as:

- Seasonal changes in temperature and humidity  
- Agricultural activities and burning of crops  
- Urbanization and industrialization  
- Weather patterns, such as dust storms or haze  

## Future Directions
To improve the model's performance and gain more insights into the air quality in Abuja, it may be helpful to:

- Incorporate additional data sources, such as weather patterns, traffic data, or land use information  
- Explore other machine learning models or techniques, such as neural networks or decision trees  
- Consider using more advanced time series analysis techniques, such as seasonal decomposition or spectral analysis  
