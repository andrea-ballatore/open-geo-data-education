# Open Geospatial Datasets for GIS Education

<img src="img/gis_data.png" width=200 align="right" />

This is a repository of open geospatial datasets to be used in an educational context.
I created these files over years of teaching Geographic Data Science and GIS.

All original datasets are freely available online with open data licenses (see the dataset attribution for details).
All the datasets in this repository have been selected, cleaned, harmonised, and repackaged for GIS exercises in a higher-education context.
This is a pretty time-intensive process that other educators can hopefully avoid by using these versions.

## Maintainer

Andrea Ballatore (Birkbeck, University of London) &bull; [aballatore.space](https://aballatore.space)

## Disclaimer

- These datasets are strictly intended for **educational, non-commercial use**.
- The datasets have been heavily processed and simplified, removing some meta-data and details.
- If you want to use these datasets for scientific research or commercial activities, please refer to the original data source.
- If you think that my version of a dataset infringes its license, please let me know and I will remove it.

## Datasets

All the datasets are in the folder `datasets`.

| Dataset                                      | Data         | Spatial scope       
|----------------------------------------------|--------------|---------------------
| ancient boundaries                           | Polygons     | Global
| ancient roman roads                          | Network      | Europe/North Africa
| darmc historical shipwrecks 500bce 1500ce    | Points       | Europe/North Africa
| digital elevation models                     | Raster       | Global
| dmsp ols nighttime lights 1995 2013          | Raster       | Global
| eu air quality 2016                          | Raster       | European Union
| eu eurostat indicators 2005 2020             | Polygons     | European Union
| europe boundaries 1914                       | Polygons     | Europe
| global air temperature 1950 2017             | Raster       | Global
| global historical earthquakes 1000 1903      | Points       | Global
| global precipitation 1950 2017               | Raster       | Global
| gpw global population density 2000 2020      | Raster       | Global
| london borough profiles 2015                 | Polygons     | Greater London
| london deprivation index wards 2019          | Polygons     | Greater London
| london openstreetmap points of interest 2020 | Points       | Greater London
| london ward profiles 2015                    | Polygons     | Greater London
| los angeles census and deprivation 2013      | Polygons     | Los Angeles County
| tectonic plates 2002                         | Polygons     | Global
| uk brexit 2016                               | Polygons     | UK
| uk hexagonal grids                           | Polygons     | UK
| uk local authority districts 2019            | Polygons     | UK
| uk local authority districts cartogram 2019  | Polygons     | UK
| uk nations and regions 2011                  | Polygons     | UK
| uk population estimates 1838 2016            | --           | UK
| uk urban areas 2016                          | Polygons     | UK
| world bank country indicators 2000 2020      | Polygons     | Global
| world country boundaries 2018                | Polygons     | Global

## Formats

All datasets are encoded in open formats:

* __CSV/TSV__ (.csv, .tsv): Comma or tab-separated values. It can be opened with R, Python, Excel.
* __GeoJSON__ (.geojson): Text-based geospatial vector datasets. It can be opened with QGIS, R, and Python.
* __GeoPackage__ (.gpkg): Single-file DB with geospatial datasets. It can be opened with QGIS, R, and Python.
* __GeoTiff__ (.tif): Geospatial raster datasets. It can be opened with QGIS, ArcMap, R, and Python.
* __R dataset__ (.rds): Native R binary format containing a data frame or a spatial data frame.
* Do not use shapefiles: http://switchfromshapefile.org

All datasets are smaller than 50 MB, in an effort to make them suitable for cheap hardware. 
Some files are compressed with **gzip** (.gz extension), which is available natively on Mac and Linux. 
[7 Zip](https://www.7-zip.org) handles the format on Windows.

## Other great sources of free open geospatial data

When pages are missing, the Wayback Machine can help: https://archive.org/web

* [FiveThirtyEight](https://github.com/fivethirtyeight/data): Amazing collection of various datasets (mostly non-geographical) with Jupyter notebooks
* [Free GIS Data](https://freegisdata.rtwilson.com): Thematically grouped geo-datasets.
* [Awesome Data](https://github.com/awesomedata/awesome-public-datasets): Various datasets for data science.
* [Automatic Knowledge](https://automaticknowledge.co.uk/resources): Very well packaged geospatial datasets about the UK.

Last update: Jan 2021