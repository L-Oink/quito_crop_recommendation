# Crop Recommendations for Zones of Quito
## Overview
Analysis matching local weather conditions to optimal crop recommendations for different zones.

## Data Sources
- Local weather data: Secretaria de Ambiente of Municipio de Quito
  (retrieved from Kaggle in https://www.kaggle.com/datasets/sebas02/quito-weather-time-series)
- Crop recommendation dataset: Kaggle
  (retrived from Kaggle in https://www.kaggle.com/datasets/varshitanalluri/crop-recommendation-dataset)

## Methods
- Removed unnecessary features (air quality metrics from weather data, soil characteristic from crop recommendations)
- Handled missing values by deletion
- Matched districts to crops based on average temperature, humidity, and rainfall requirements

## Key Findings
- Based on temperature, the ideal crop is chickpea for all zones.
- Based on humidity, recommended crops are blackgram and jute.
- Based on rainfall, recommended crops are mango, blackgram, banana, kidneybeans, papaya, and pomegranate.

## Tools Used
- Python 
- Pandas

## Files
- crop_recommendations_quito.ipynb - Main analysis
- weather_quito_reduce.ipynb - Remotion of unnecessary features from weather data
- crops_reduce.ipynb - Remotion of unnecessary features from crop recommendations data
- crops_reduced.csv - output file from weather_quito_reduce.ipynb
- weather_clean.csv - output file from weather_quito_reduce.ipynb
- quito_weather.parquet - Quito Weather Timeseries
- Crop_recommenation.csv - Crop Recommendations Dataset
- `README.md` - This file
