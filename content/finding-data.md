---
layout: default
title: Finding Data
nav_order: 3
has_children: yes
---
# Finding Data

## Types of Geospatial Data
Geospatial data is often referred to as having two main types: raster and vector. These two data types, while both geospatial, are very different from one another. **Raster data** is data which is made up of pixels arranged in a grid, whereas vector data is made up of vertices and the paths between them – creating geometries that represent real-world features or phenomena. In other words, a **vector data** layer will be made up of either points, lines, or polygons. A third type of spatial data is tabular data. **Tabular data** are data formatted into a table by rows and columns. If the tabular dataset has columns referring to geometry such as latitude and longitude, then the dataset can be displayed in the virtual geographic space of a GIS. What type of data do you have? What type of data are you looking for? 

## Where to look
Municpal and federal data repositories are a good place to begin. If you have access to a data repository, either through a group you're working with/for or institutional library for example, reaching out to whoever coordinates on the matter can be useful. You can also begin with a google search and see what is returned. 

## Making your own data 
You can always make vector data from within QGIS, and of course modify and crop a dataset to suit your needs. 


## Considerations
Whether you're performing spatial analysis or making maps for yourself or a client, its important to keep a record of your data sources as you work. You'll figure out a system that make sense to you. Trial and error a few times. However, The following considerations are useful to note somewhere like a document or notes file as you go. 

```
- What is the dataset of and where did you download it from (save a link)
- What is the downloaded file called? Where is it stored on your computer/external storage device?
- Is there a visual data preview such as an interactive web map?
- What attributes are included in the dataset? 
- Who is the dataset published by and is there a contact for questions? 
- What is the dataset's license?
- When was it last updated?
- What formats can the dataset be downloaded in? 
- What projections can the dataset be downloaded in?
```
---

## Data Sources



[https://earthworks.stanford.edu/](https://earthworks.stanford.edu/)
[The Humanitarian Data Exchange](https://data.humdata.org/dataset)
[BC Data](https://catalogue.data.gov.bc.ca/)
[cov open data portal](https://opendata.vancouver.ca/pages/home/)
[metro vancouver open data](https://open-data-portal-metrovancouver.hub.arcgis.com/)

## Census Data Canada
- [Statistics Canada]()
- [Administrative and Statistical Boundaries 2021 (e.g., provinces, census divisions, dissemination areas)](https://www12.statcan.gc.ca/census-recensement/2021/geo/sip-pis/boundary-limites/index2021-eng.cfm?year=21)

## Census Data Global
- [World urbanization](https://population.un.org/wup/DataQuery/)
- [World demographics](https://population.un.org/dataportal/home?df=d7cac223-d504-404f-807a-03d475ad6c63)

## Global/Local Shapefiles
- [Natural Earth](https://www.naturalearthdata.com/downloads/) what it is....
- [USA TIGER line shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html)


## Street Network
- [osm street network]() --> how to download from within QGIS
- [canada road network file](https://www12.statcan.gc.ca/census-recensement/2021/geo/sip-pis/rnf-frr/index2021-eng.cfm?year=21)
- [usa primary roads](https://catalog.data.gov/dataset/tiger-line-shapefile-2019-nation-u-s-primary-roads-national-shapefile)
- [usa transportation atlas]
- [india 2016 roads](https://geodata.mit.edu/catalog/stanford-qf525mn4696)
- [EU](https://data.europa.eu/data/datasets/major-road-network?locale=en)

## Climate, Landcover, and Satellite Imagery
- [world climate data](https://www.worldclim.org/)
- [world land cover](https://data.apps.fao.org/catalog/iso/8cf69f76-1be0-4339-a0b0-18a93c7f4760)
- [another world land cover](https://viewer.esa-worldcover.org/worldcover/)
- [places to download tile by tile](https://gisgeography.com/free-satellite-imagery-data-list/)
- [Web Basemap plugin]
- [STRM Downloader plugin]
- [candada land cover](https://natural-resources.canada.ca/maps-tools-publications/satellite-imagery-air-photos/application-development/land-cover/21755)
- [bc lidar](https://lidar.gov.bc.ca/pages/download-discovery)

#### Resources to Learn more about Geospatial Data
[What is geospatial data?](https://ubc-library-rc.github.io/gis-intro-qgis/content/geospatial-data.html)
