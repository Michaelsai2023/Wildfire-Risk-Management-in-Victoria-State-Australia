# Utilizing Data Analytics for Wildfire Risk Management in Victoria State, Australia

## Metrics and Dimensions

- Data Sources: MODIS satellite data, Australia weather data, and Victoria state shapefile.
- Analysis Methods: Spatial analysis, time series analysis, machine learning, and catastrophe modeling.
- Metrics: Wildfire occurrences, weather conditions, fire risk zones, and prediction accuracy.

<img width="920" alt="Screen Shot 2024-08-02 at 22 54 25" src="https://github.com/user-attachments/assets/c0485616-f98d-4c9e-b4f4-6d6c9aeb0d18">
<img width="920" alt="Screen Shot 2024-08-02 at 22 54 25" src="https://github.com/user-attachments/assets/79b9ad8f-5818-4d20-a976-e779be8dfbe6">



### Summary of Insights

### Wildfire Occurrences:
- Spatial Trends: Identified high-risk zones using heatmaps, with notable wildfire occurrences in specific latitudes and longitudes.
- Temporal Trends: Seasonal analysis revealed that autumn had the highest frequency of wildfires, followed by summer.

<img width="987" alt="Screen Shot 2024-08-02 at 22 53 34" src="https://github.com/user-attachments/assets/0576021e-209a-42a4-bfdc-3c22a6e6030b">
<img width="987" alt="Screen Shot 2024-08-02 at 22 53 34" src="https://github.com/user-attachments/assets/9a77b30b-fc50-4e24-930a-21293fb6f6bf">


###  Weather Conditions:

- Impact on Wildfires: Higher temperatures and lower relative humidity were associated with increased wildfire confidence and brightness.
- Predictive Variables: Wind speed significantly influenced fire radiative power, highlighting its role in wildfire behavior.


### Machine Learning Predictions:

- Model Selection: Utilized Random Forest and XGBoost for predicting wildfire occurrences.
- Model Performance: Random Forest outperformed XGBoost in predicting brightness, confidence, and fire radiative power, with higher R-squared values and lower MAE and MSE.

<img width="997" alt="Screen Shot 2024-08-02 at 22 55 11" src="https://github.com/user-attachments/assets/2a3c4e5d-2868-49ea-a04c-3c259bb5908e">
<img width="995" alt="Screen Shot 2024-08-02 at 22 55 23" src="https://github.com/user-attachments/assets/0b3c6e6d-3f25-4b4b-907c-731496964d54">


### Risk Management Strategies:

- Catastrophe Modeling: Implemented models to assess potential hazards and inform risk mitigation strategies.
- Resource Allocation: Prioritized high-risk areas for targeted interventions such as fuel reduction initiatives and enhanced surveillance.

### Recommendations & Next Steps

- Seasonal Preparedness: Allocate additional resources for wildfire prevention and suppression during autumn and summer.
- Localized Interventions: Focus on high-risk regions identified through spatial analysis for specific interventions.
- Enhanced Monitoring: Improve meteorological data integration for more accurate predictions and real-time risk assessment.
- Community Engagement: Develop public engagement events and collaborate with local stakeholders to enhance wildfire preparedness and response.


### Overview of Datasets
- MODIS Australia Wildfires Dataset (2017-2020): This dataset provides detailed satellite data and fire detec7on data crucial for monitoring wildfires in Australia. hcps://www.kaggle.com/datasets/brsdincer/australia-and-inves7ga7ve-special-wildfires-data
- Australia Weather Data: This dataset offers comprehensive meteorological informa7on, including temperature, rainfall, wind speed, humidity, and cloud cover, across various loca7ons in Australia. hcps://www.kaggle.com/datasets/gaurav896/weather-in-australia
- Victoria State Shape File: This shapefile provides geographical informa7on for the state of Victoria. hcps://gisdata.mapog.com/australia/States%20and%20Territories%20level%201/Victoria
