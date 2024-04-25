---
layout: default
title: Displaying Data
nav_order: 4
has_children: yes
---
# Displaying Data

Once you've gathered your relevant data you are ready to add it to a QGIS project. This group of pages documents how to load and display different kinds of data, examine the attribute of data layers, adjust the layers' symbology, and project/reproject as needed. 

A Geographic Information System (GIS) works with data that is tied to a location on Earth. This type of data is often referred to as GIS data, or geospatial data, and is spatially referenced to Earth using location information – most commonly geographic coordinates. A GIS uses this location information to project a geospatial file into a virtual geographic space where it can then be visualized and analyzed.

## Types of Geospatial Data
Geospatial data is often referred to as having two main types: raster and vector. These two data types, while both geospatial, are very different from one another. **Raster data** is data which is made up of pixels arranged in a grid, whereas vector data is made up of vertices and the paths between them – creating geometries that represent real-world features or phenomena. In other words, a **vector data** layer will be made up of either points, lines, or polygons. A third type of spatial data is tabular data. **Tabular data** are data formatted into a table by rows and columns. If the tabular dataset has columns referring to geometry such as latitude and longitude, then the dataset can be displayed in the virtual geographic space of a GIS. 

## Spatializing data
Finally, sometimes data that are not overtly geospatial data can be specialized by a GIS because they contain a locational component. For instance, a tabular dataset with street addresses can be geocoded, a historical map with streets and landform features can be georeferenced, and a spreadsheet of authors and their home cities can be joined to a vector layer of cities. 

The following pages will explain all these workflows further. 


