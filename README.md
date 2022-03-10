# Bike Share Toronto 2021 Data Analysis

## Objective

- To better understand how people in Toronto are using Bike Share
- To highlight some usage patterns for potential and exsiting users (e.g. popular routes, rush hours, avg speed, etc.)
- To generate insights for maintenance and management (e.g. allocating bikes, identify broken bikes & stations, etc.)

## Background

Bike Share Toronto was designed to allow users to make short trips around town. The sturdy-framed bikes are available at any docking station in the city. The bikes can be taken from any station and returned to any station in the bike share system. 

There are 6,850 bikes and 625 stations are available throughout Toronto. A station is the strip of bikes that are available around the city, placed based on population and transport needs.

There are two major user categories in the dataset:
- Annual Member: including Annual 30 Member (unlimited trips under 30 min) per year, and Annual 45 Member (unlimited trips under 45 min).
- Casual Member: including Single Trip Passes, Day Passes and 3-Day Passes.

Official website: https://bikesharetoronto.com/

## Datasets

- Bike Share Toronto Ridership Data from [City of Toronto's Open Data Portal](https://open.toronto.ca/dataset/bike-share-toronto-ridership-data/)
- Bike Share stations profile in [json](https://tor.publicbikesystem.net/ube/gbfs/v1/en/station_information)
- Daily weather data of 2021 at Toronto City weather station from [Canada.ca](https://climate.weather.gc.ca/historical_data/search_historic_data_e.html)

## Results & Key Findings

Report with interactive graphs: https://dailyli.github.io/toronto_bike_share/

## Packages & documents

The code was written in Jupyter Notebook with Python, using **Pandas** for data manipulation, and **Plotly** for visualization.
- [Preprocessing.ipynb](https://github.com/dailyLi/toronto_bike_share/blob/main/Preprocessing.ipynb): data cleaning and processing with Jan 2021 dataset
- [functions.ipynb](https://github.com/dailyLi/toronto_bike_share/blob/main/functions.ipynb): workflows for processing the whole 2021 datasets
- [Analysis.ipynb](https://github.com/dailyLi/toronto_bike_share/blob/main/Analysis.ipynb): data visualization, analysis and some discussion

