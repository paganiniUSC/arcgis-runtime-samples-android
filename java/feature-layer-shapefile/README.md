# Feature Layer Shapefile

This sample demonstrates how to open a shapefile stored on the device and display it as a feature layer with default symbology.

![Feature Layer App](feature-layer-shapefile.png)

## Features

* FeatureLayer
* ShapefileFeatureTable

## How it works

1. Create a `ShapefileFeatureTable` a path to a shapefile (.shp) on loaded onto the device.
1. Use the `ShapefileFeatureTable` to create a `FeatureLayer`
1. Add the `FeatureLayer` to the `ArcGISMap` as an operational layer, using default symbology and rendering.

## Provision your device
1. Download the data from [ArcGIS Online](https://www.arcgis.com/home/item.html?id=d98b3e5293834c5f852f13c569930caa).
1. Extract the contents of the downloaded zip file to disk.
1. Open your command prompt and navigate to the folder where you extracted the contents of the data from step 1.
1. Execute the following command:

`adb push Public_Art.shp /sdcard/ArcGIS/Samples/ShapeFile/Aurora_CO_shp/Public_Art.shp`


Link | Local Location
---------|-------|
|[Public Art Shapefile](https://www.arcgis.com/home/item.html?id=d98b3e5293834c5f852f13c569930caa)| `<sdcard>`/ArcGIS/Samples/ShapeFile/Aurora_CO_shp/Public_Art.shp|