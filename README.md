# FOSS4GPH 2016 Workshop Setup Guide

## OSM for Beginners
1. Install JRE through [http://www.java.com/download](http://www.java.com/download)
2. Install the latest Java OpenStreetMap Editor (JOSM) [https://josm.openstreetmap.de/wiki/Download](https://josm.openstreetmap.de/wiki/Download)
3. Enable "Remote Connection" for JOSM
4. Make sure your computer's firewall is not blocking the default remote port of JOSM 8111(http), 8112(https)

Download the [manual](http://blog.noah.dost.gov.ph/2016/04/12/openstreetmap-editing-for-the-philippines-in-support-of-risk-analysis-map-development/) and the [presentation](http://www.slideshare.net/schadow1/introduction-to-openstreetmap-its-extracts-and-relation-to-project-noah)

## GeoPython Workshop
1. Download Miniconda with the appropriate version for your operating system using the following link: [http://conda.pydata.org/miniconda.html](http://conda.pydata.org/miniconda.html)
2. Install Miniconda using the installer and check all the boxes when prompted. <br />
   **Note:** If you have a previous installation of python, you don't need to check the second box.
3. After installing miniconda, open your command prompt.
4. Type the following in your command prompt to install the required packages<br />
   - `conda install jupyter`
   - `conda install gdal`
   - `conda install fiona` 
   - `conda install -c http://conda.anaconda.org/scitools shapely`
   - `conda install rasterio`
   - `conda install -c http://conda.anaconda.org/ioos folium`
5. Test if you have installed the jupyter notebook. Type the following in your command prompt <br />
   `jupyter notebook` <br />
   This will open a web browser. If the command does not open up browser just open your browser and go to http://localhost:8888
6. You should now see the jupyter notebook running in your browser.

Check the material [here](https://github.com/lkpanganiban/geopython-tutorial) 

## Grass GIS Workshop
Install Grass GIS 7.0.3 using [https://grass.osgeo.org/news/54/56/GRASS-GIS-7-0-3-released/](https://grass.osgeo.org/news/54/56/GRASS-GIS-7-0-3-released/)

Check the material [here](https://benhur07b.github.io/foss4gph2016-workshop-grass) and the [data](https://github.com/benhur07b/foss4gph2016-workshop-grass) 

## Invitation to QGIS and QGIS Map Composer Workshops
1. Link to the workshop datasets [here](https://www.dropbox.com/sh/klf9uhgc09kgyxf/AABlkQOgyrQS1yTlNqGCoXJEa?dl=0) <br />
2. OpenLayers plugin installation <br />
    - Go to the "Plugins" menu and select "Manage and Install Plugins"
    - Once the list of plugins are listed down, scroll down the list and find the OpenLayer plugin.
    - Click on the "Install plugin" button and wait for QGIS to download and finish


QGIS Installer: [http://www.qgis.org/en/site/forusers/download.html](http://www.qgis.org/en/site/forusers/download.html) <br /> 

Check the course materials:
  - [Intro to QGIS](https://www.dropbox.com/sh/klf9uhgc09kgyxf/AABlkQOgyrQS1yTlNqGCoXJEa?dl=0)
  - [QGIS Map Composer](https://drive.google.com/open?id=0BwvO6IOR4gglbkFyQXczc1FOOEk) 

## Reminders
 - Bring your Laptop
 - Laptop Charger
 - Internet/WIFI Dongles
 - Yourself
