# Crop Recommendations for Zones of Quito
## Overview
Analysis matching local weather conditions to optimal crop recommendations for different zones.

## Data Sources
- Local weather data: Secretaria de Ambiente of Municipio de Quito
- Crop recommendation dataset: Kaggle

## Methods
- Removed unnecessary features (air quality metrics from weather data, soil characteristic from crop recommendations)
- Handled missing values by deletion
- Matched districts to crops based on temperature, humidity, and rainfall requirements

## Key Findings
- [District A]: Best suited for [crop] based on temperature match
- [District B]: Best suited for [crop] based on humidity/rainfall
- [Add 2-3 bullet points of actual results]

## Tools Used
Python, pandas

## Files
- `crop_analysis.ipynb` or `crop_analysis.py` - Main analysis
- `README.md` - This file
