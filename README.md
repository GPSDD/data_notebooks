# Data prep notebooks

This repository contains some Jupyter Notebooks with example code relating to API Highways.

## Data prep and import

`sdg_datasets.ipynb` deals with the parsing and import of data from
[api.resourcewatch.org](https://api.resourcewatch.org). ResourceWatch
is provided by the World Resources Institute, and contains many
datasets related to several topics related to the Sustainable
Development Goals: society, cities, climate, energy, food, forests,
and water and oceans

`ee_parsing_and_import.ipynb` deals with the dataprep and import of
datasets provided in [Google Earth
Engine](https://earthengine.google.com/).  Google Earth Engine
provides many datasets, both in raster and vector format. GEE is a
managed computing enviroment that provides researchers around the
world access to massive datasets, from satellite imagery to
demographic data.

## Data access through the API
`Google Earth Engine dataset import and querying.ipynb` contains
python tooling and examples for a complete 'data pipeline' for a
Google Earth Engine dataset, from registering it to making queries to the API.

`nightlights_analysis.ipynb` deals with using the API for filtering
data and consuming it with the Google Earth Engine python API.
