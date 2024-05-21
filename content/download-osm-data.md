---
layout: default
title: Download OSM data
nav_order: 2
parent: Finding Data
---
# Downloading OSM Street Network Data
Need data on street networks? There's a QGIS Plugin that allows you to download and save OSM data to your local device. 

First you'll need to load OSM Street Network into your QGIS Project. See [Adding a Basemap](./content/web-basemap.md) for demonstration. 


From the Plugins menu at the top of your screen, navigate to “Manage and Install Plugins…” In the Plugins dialogue box that opens, first go to Settings and enable experimental and deprecated plugins. Return back to All and search “QuickOSM.” Install the plugin and close the dialogue box. Now click on the Processing menu at the top of your screen and open the Toolbox. Search for “QuickOSM.” Select “Download OSM data from a query in an extent.” In the dialogue box that opens you only need to set an extent and location to save the street networks. From the Extent drop-down menu select “Calculate from Layer” and then census-DAs. To save the output as a permanent file, click the ellipses and navigate to your workshop-data folder. Now run the tool; it may take a while.



---
#### Resources 
[QGIS Plugins](https://plugins.qgis.org/)
