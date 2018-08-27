# UrbanClimateSummerSchool2018
Lectures given at the Urban Climate Summer School 2018 organized by Research Institute of University of Bucharest (ICUB), Urban Climate Research Center at Arizona State University (ASU), Ghent University (Belgium), National Meteorological Administration (Meteo Romania) , Interdisciplinary Center of Advanced Research on Territorial Dynamics (CICADIT)


# Installation Prerequisites

## Windows, Linux and macOS are supported

* Install Anaconda https://www.anaconda.com/download
* In a terminal run *conda install -c esri arcgis* to install ArcGIS Pyrhon API
* Test your install: 
    * In a command line in the folder where you want to start your project run:
        - *jupyter notebook*
     * In the Jupyter Notebook enter the following lines:
        - *from arcgis.gis import GIS*
        - *my_gis = GIS()*
        - *my_gis.map()*
        
* More information are provided at https://developers.arcgis.com/python/guide/install-and-set-up

* For remote desktop support install one of the following software:
    * Install Anydesk from https://anydesk.com/remote-desktop
    * Install Chrome Remote Desktop from https://chrome.google.com/webstore/detail/chrome-remote-desktop/gbchcmhmhahfdphkhkmpfmihenigjmpp