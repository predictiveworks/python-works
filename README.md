
# PythonWorks.<a id="top"></a>

Welcome to PredictiveWorks. *Python* branch. PythonWorks. has a strong focus on data science
and illustrates recent project results. This repository was made to be helpful for others and
to provide technical hints in case of poorly documented open source libraries. 

* [Climate Change](#cc)
* [Earth Observation](#eo)
* [Geo Marketing](#gm)  
* [Smart Agriculture](#sa)  
* [Smart Building](#sb)  
* [Smart City](#sc)  
* [Smart Energy](#se)
* [Smart Infrastructure](#si)  
* [Sustainability Reporting](#sr)

## Climate Change (CC)<a id="cc"></a>

[Top](#top)

The June to August 2022 temperature distribution in Austria in action:

https://user-images.githubusercontent.com/49725564/219854667-7b2bb2b8-f825-4483-9184-4b1025267a57.mp4

## Earth Observation (EO)<a id="eo"></a>

[Top](#top)

This section introduces (visualization) results from projects related to open EO datasets.

### Corine Land Cover (2018)

Copernicus Land Monitoring Service for Italy's field detection and monitoring.

![Corine 2018 Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/corine2018-overlay-for-carto.png)

### Sentinel 3

![Sentinel-3 OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/sentinel-3-overlay-for-osm.png)

### Topographic Maps

![EU-DEM Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/topography-austria-copernicus-overlay-for-carto.png)

![GMTED2010 OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/topography-italy-gmted2010-overlay-for-osm.png)

Selected list of 4 European NUTS 3 regions (Bern, Torino, Munich, Stuttgart) enriched with EU-DEM dataset.

![EU-DEM Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/eu-cities-dem-overlay-for-carto.png)

## Smart Energy<a id="se"></a>

[Top](#top)

This section introduces (visualization) results from recent smart energy projects.

### Coal Power Plants

The image below illustrates the capacity in MW of active coal fueled power plants in Europe.

![Coal Power Plants Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/coal-plants-europe-overlay-for-carto.png)

### Solar Power Efficiency

The image below illustrates the potential net power of private solar units, aggregated at German county level (left side).
The net power distribution is compared to the spatial distribution of annual solar radiation (right side). As a result, there 
is no spatial correlation of areas with high net power & radiation.

![Solar Power vs Radiation OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/solar-power-vs-radiation-overlay-for-osm.png)

### New European Wind Atlas (NEWA)

This section leverages the NEWA Mesoscale Atlas. The mesoscale part of the New European Wind Atlas (NEWA) 
was created from WRF model simulations for all of Europe at a grid spacing of 3 km x 3 km, initially covering
the 30 years from 1989 to 2018. 

The WRF model simulations (using WRF V3.8.1) were done in 10 partly overlapping domains using ERA5 reanalysis 
and OSTIA sea surface temperatures. The model configuration, production and evaluation of the results against 
observations are described in Hahmann et al. (2020) and Dörenkämper et al. (2020). 

The image below visualizes wind speeds in 100 m (above ground) in Germany.

![NEWA (100m) OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/newa-100m-overlay-for-osm.png)

## Smart Agriculture<a id="sa"></a>

[Top](#top)

This section introduces (visualization) results from recent smart agriculture projects.

### LoRaWAN Gateways (TTN)

The image below visualizes the number of gateways per NUTS-3 regions in Germany.

![LoRaWAN Gateways OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/lorawan-gateways-overlay-for-osm.png)

The image shows the individual gateways for Vienna, Austria as an overlay for the Vienna elevation model (Copernicus DEM), 
and the Vienna vegetation index (Sentinel. This map is part of a project that evaluates the usability of LoRaWAN technology 
for urban-near agriculture.

![Vienna LoRaWAN Gateways](https://github.com/predictiveworks/python-works/blob/main/images/agritech_field-dem-lorawan.png)

### Drought Index (DWD)

The image below visualizes drought index in mm/°C (de Martonne), Germany 2018-08.

![Soil Moisture Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/drought-index-2018-overlay-for-carto.png)

### Soil Moisture (DWD)

The image below visualizes soil moisture in % nFK, Germany 2018-08.

![Soil Moisture Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/soil-moisture-2018-overlay-for-carto.png)

### Multiple Vegetation Indexes (MSAVI, NDMI & NDVI)

The image below shows multiple vegetation indexes for a summer day in Vienna, including the Sentinel-2 true color image.

![Multiple Vegetation Indexes for Vienna](https://github.com/predictiveworks/python-works/blob/main/images/agritech_field-multiview-1200x800.png)

## Smart Building<a id="sb"></a>

[Top](#top)

This section introduces (visualization) results from recent smart building projects.

### Sensors as Graph Network

![Sensors as Graph Network](https://github.com/predictiveworks/python-works/blob/main/images/building-sensor-network-3d.png)

## Smart City<a id="sc"></a>

[Top](#top)

This section introduces (visualization) results from recent smart city projects.

### Buildings 

![Hamburg Buildings Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/hamburg-buildings-overlay-for-carto.png)

![Hamburg Buildings 3D Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/hamburg-buildings-3d-overlay-for-carto.png)

### Heat Zones (ECOSTRESS, Sentinel-2)

![Heat Zone DEM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/earthdata_vienna-ecostress-dem.png)

![Heat Zone TCI Overlay](https://github.com/predictiveworks/python-works/blob/main/images/earthdata_vienna-ecostress-tci.png)

### Vegetation

The image illustrates the vegetation index (NDVI) of the city of Bern. The data were extracted from Sentinel-2 (relative orbit, 108).

![Bern Sentinel-2 NDVI OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/bern-s2-ndvi-overlay-for-osm.png)

## Smart Infrastructure<a id="si"></a>

[Top](#top)

The image visualizes the LTE cell towers in Austria, Germany, Italy and Poland. It is based on OpenCelliD, the world's largest open database 
of cell towers, which so far, is one of the most precise publicly available data sources for telecom-related projects.

![LTE Cell Towers in European Cities](https://github.com/predictiveworks/python-works/blob/main/images/countries-ocid.png)

## Geo Marketing<a id="gm"></a>

[Top](#top)

This section introduces (visualization) results from recent geo marketing projects. Geo-referenced socio-demographic, energy, 
climate, behavior and regional trends data form an important basis for hyper-local customer segmentation. 

### Population Age Distribution

The image below illustrates the age distribution of German counties, elder persons (>= 60) on the left side, and children (<= 10)
on the right side.

![Population Age OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/population-age-overlay-for-osm.png)

## Sustainability Reporting<a id="sr"></a>

[Top](#top)

This section introduces (visualization) results from recent sustainability projects.

### Biodiversity

The image below visualizes the protected areas in Italy.

![Protected Areas Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/protected-areas-italy-overlay-for-carto.png)

### Social Forensic Services

The social dimension of sustainability reporting (e.g., to disclose global supplier relations) needs a world's eye
on conflicts, human rights violation and more. The image below illustrates 15 minutes of the world's sentiment.

![World Sentiment Carto Overlay](https://github.com/predictiveworks/python-works/blob/main/images/world-sentiment-15min-overlay-for-carto.png)

### Water Risk

The image shows the annual water risk in 4 European countries for the agricultural sector. The risk is normalized
according to the following categories: Low (0, 1), Low-Medium (1, 2), Medium-High (2, 3), High (3, 4), Extremely High (4, 5).

![European Water Risk OSM Overlay](https://github.com/predictiveworks/python-works/blob/main/images/annual-water-risk-europe-overlay-for-osm.png)


