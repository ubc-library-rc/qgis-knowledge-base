---
layout: default
title: Projections
nav_order: 5
---

# Coordinate Reference Systems (CRS)

Making Cartesian maps requires some method for flattening out the earth so we can represent portions of it on our 2-dimensional computer screens. A **Coordinate Reference System (CRS)** defines this transformation. A CRS contains two components: a **datum** and a **coordinate system**. 

## Datums
Earth is not a perfect sphere but rather a *spheroid* as it is flattened slightly at the poles. *Ellipsoid*, referencing a 3-dimensional ellipse, describes the same shape. [From Esri's description:](https://desktop.arcgis.com/en/arcmap/latest/map/projections/datums.htm) "While a spheroid approximates the shape of the earth, a datum defines the position of the spheroid relative to the center of the earth. A datum provides a frame of reference for measuring locations on the surface of the earth. It defines the origin and orientation of latitude and longitude lines." A **geocentric datum** positions the center of the spheroid, aka ellipsoid, at the earth's center of mass. A **local datum** "aligns its spheroid to closely fit the earth's surface in a particular area." Datums are developed using satellite data.

A geocentric datums is useful when a map is meant to show the whole earth, such as a World Map or Open Street Maps' web map. Local datums are useful when the area of interest is confined to a continent such as North America or a single country. Because local datums are accurate precisely for the area of their ellipsoid's best fit, it would be unwise to use a local datum for a global map, or a datum specific to North America for Africa. Datums are named by their extent and survey year. Today, the most common geocentric datum is WGS 84 (World Geodetic System 1984), and the most common local datum for the United States and Canada is NAD 83 (North American Datum 1983). Notice that Vancouver Open Data allows you to download data in either NAD 83 or WGS 84.
 <!-- The data for this project has been downloaded in WGS 84 so as to align with Open Street Maps' datum.  -->

## Coordinate Systems
A coordinate system is the math governing the projection of points on an ellipsoid to a 2-dimensional plane. A coordinate system is either a **Projected Coordinate system (PCS)** or **Geographic Coordinate system (GCS)**. Move your cursor around on your map canvas and look at the status bar. You should see coordinate pairs.

<!-- You may also have noticed your map looks a bit squashed or slanted:

<img src="./images/GCS-example.png" style="height:50%;"> -->


These  tells us that our project is in a GCS because geographic coordinate systems plot points in decimal degrees, whereas the unit for projected coordinate systems is meters. If you are interested in any sort of distance or area measurement, you'll want to ensure your project has a defined PCS. 


