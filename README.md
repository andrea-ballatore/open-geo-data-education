# Open Geospatial Datasets for GIS Education

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

TBC

## Formats

All datasets are encoded in open formats:

* __CSV/TSV__ (.csv, .tsv): Comma or tab-separated values. It can be opened with R, Python, Excel.
* __GeoJSON__ (.geojson): Text-based geospatial vector datasets. It can be opened with QGIS, R, and Python.
* __GeoPackage__ (.gpkg): Single-file DB with geospatial datasets. It can be opened with QGIS, R, and Python.
* __GeoTiff__ (.tif): Geospatial raster datasets. It can be opened with QGIS, ArcMap, R, and Python.
* __R dataset__ (.rds): Native R binary format containing a data frame or a spatial data frame.
* I do not use shapefiles: (http://switchfromshapefile.org)

All datasets are smaller than 50 MB, in an effort to make them suitable for dated hardware. 
Some files are compressed with **gzip** (.gz extension), which is available natively on Mac and Linux. 
[7 Zip](https://www.7-zip.org) handles the format on Windows.

## Other great sources of free open geospatial data

When pages are missing, the Wayback Machine can help: https://archive.org/web

* https://automaticknowledge.co.uk/resources
* https://freegisdata.rtwilson.com
* https://github.com/awesomedata/awesome-public-datasets

Last update: Jan 2021