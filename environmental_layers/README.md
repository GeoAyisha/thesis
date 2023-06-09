# Environmental layers of the street network of Tallinn, Master's Thesis

## Requirements
QGIS (recommended 3.16.11 or newer version)

## Data description
The environmental layers of the street network of Tallinn consist of 5 GeoPackage (GPKG) files containing vector line layers with values per street segment with a maximum length of 200 m
for the following variables:
- PM2.5 (2020): Annual particulate matter with a diameter of 2.5 micrometres or smaller, measured in mean street segment µg/m3.
- PM10 (2020): Annual particulate matter with a diameter of 10 micrometres or smaller, measured in mean street segment µg/m3.
- NO2 (2020): Annual nitrogen dioxide, measured in mean street segment µg/m3.
- Noise pollution (2019): Strategic noise pollution levels for Lden (day-evening-night), measured in mean street segment dB.
- Greenery (18/06/2021): Derived from Normalised Difference Vegetation Index (NDVI) values, ranging between 0 and 1.
For more detailed information refer to (DSpace Link). 

## Workflow description
Data derived from a GIS workflow over the street network layer of Tallinn city using raster layers of annual outdoors air pollution (PM2.5, PM10 and NO2), reclassified NDVI
as greenery indicator and strategic noise pollution. The tools used in the analysis are Split Line by Maximum Length for creation of the street segments,  Buffer for defining the 
street environment around street segments, and Zonal Statistics for projecting environmetal layers to the street environment. For more details refer to (DSpace Link).

## Usage
The layers can be used for performing exposure analysis to annual levels of the included variables within the street network environment. Other socio-economic and
socio-demographic variables can be addressed to indentify differences between them. For an example of the later refer to (DSpace Link).

## Support
Email: yusibovaayise@gmail.com

## RoadMap
Expected release of layers with seasonal / temporal levels of the variables.

## Installation
Data layers can be downloaded directly and opened as a GeoPackage file in any GIS software or Python using "Geopandas" package, R through "sf" (Simple Features) package etc. 

## DOI and data
https://doi.org/10.5281/zenodo.8016625

## Authors
Ayisha Yusibova

## License
This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Project status
Completed