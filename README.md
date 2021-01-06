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

| Dataset                                      | Spatial data |
|----------------------------------------------|--------------|
| ancient_boundaries                           | Polygons     |
| ancient_roman_roads                          | Network      |
| darmc_historical_shipwrecks_500bce_1500ce    | Points       |
| digital_elevation_models                     | Raster       |
| dmsp_ols_nighttime_lights_1995_2013          | Raster       |
| eu_air_quality_2016                          | Raster       |
| eu_eurostat_indicators_2005_2020             | Polygons     |
| europe_boundaries_1914                       | Polygons     |
| global_air_temperature_1950_2017             | Raster       |
| global_historical_earthquakes_1000_1903      | Points       |
| global_precipitation_1950_2017               | Raster       |
| gpw_global_population_density_2000_2020      | Raster       |
| london_borough_profiles_2015                 | Polygons     |
| london_deprivation_index_wards_2019          | Polygons     |
| london_openstreetmap_points_of_interest_2020 | Points       |
| london_ward_profiles_2015                    | Polygons     |
| los_angeles_census_and_deprivation_2013      | Polygons     |
| tectonic_plates_2002                         | Polygons     |
| uk_brexit_2016                               | Polygons     |
| uk_hexagonal_grids                           | Polygons     |
| uk_local_authority_districts_2019            | Polygons     |
| uk_local_authority_districts_cartogram_2019  | Polygons     |
| uk_nations_and_regions_2011                  | Polygons     |
| uk_population_estimates_1838_2016            | --           |
| uk_urban_areas_2016                          | Polygons     |
| world_bank_country_indicators_2000_2020      | Polygons     |
| world_country_boundaries_2018                | Polygons     |
|----------------------------------------------|--------------|

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