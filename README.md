# fire-prediction
### tensorflow machine learning model to predict wildfire likelihood
redict fire (boolean) in unit area over next unit of time (ex. 7 days - prediction time frame has to match data training time frame)
supervised learning based on past fire perimeter data - train before wildfire season then add real-time data

- features:
  - weather (temp, humidity, wind speed, precipitation)
  - long-term climate data (averages over time)
  - land use (wilderness, agricultural, suburban)
  - topography (elevation, slope)
  - forestry conditions (fuel load, vegetation etc) 
  - fire history
  - human activity (roads etc)
  - proximity to current wildfires
  
- training data sources:
  - National Land Cover Database (NLCD) - Normalized Difference Vegetation Index (NDVI)
  - USGS National Elevation Dataset (NED)
  - Wildland Fire Assessment System (WFAS)
  - US Forest Service Remote Sensing Applications Center (RSAC)
  - National Land Cover Database (NLCD)
  - National Climatic Data Center (NCDC)
  
- training data formats: {csv, parquet, avro, orc, json} ?

