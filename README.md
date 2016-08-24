## ph-regions-2015
This notebook goes through the steps of preparing and generating up-to-date shape files of the Philippine administrative regions.

## Data Sources
The original shape files used here are downloaded from the following:

* [**PhilGIS.org**](http://philgis.org/) - for the regions shape files.
* [**GADM Database**](http://www.gadm.org/download) - for the provincial-level shape files.
* [**Phil. Statistics Authority**](http://www.nscb.gov.ph/activestats/psgc/SUMWEBPROV-JUNE2016-CODED-HUC-FINAL.pdf) - for the PDF file containing updated PSGG codes.

**IMPORTANT:** Because of the license terms accompanying the shape files downloaded from the GDAM Database, I did not push those files into this repository. So, in order to have all the needed shape files to run this notebook, please do the following:

1. Go to the [GDAM download page](http://www.gadm.org/download).
2. Choose country data for the Philippines and hit download.
3. Unzip the downloaded zip file.
4. Copy the files `PHL_adm1.shp`, `PHL_adm1.dbf`, and `PHL_adm1.shx` into the directory named `Original` of this project.

## Dependencies
This notebook uses Geopandas which you can easily install with pip or conda install if you're not on a Windows machine. But, if you are, please [check out Jeff Boeing's installation guide](http://geoffboeing.com/2014/09/using-geopandas-windows/) to properly set up Geopandas and its dependencies such as Shapely and Fiona. Anyway, here's a partial list of the packages you need to install to get this notebook up and running (see the `requirements.txt` for the full list):

1. geopandas.
2. shapely
3. gdal
4. fiona
5. descartes
6. pandas
7. matplotlib
8. fuzzywuzzy

## Output
Please see the `Updated` directory of this repository to access the updated shape files, or [click here to download a zip file containing the output](https://drive.google.com/open?id=0Bz3ja0Q9BLsPZEpwdmZWckRCazQ).

## License
The files contained in the directory named `Updated` of this project are made available free of charge to anyone under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license](https://creativecommons.org/licenses/by-sa/4.0/legalcode). Please see the `license.txxt` file in the `Updated` directory.

## Contributing
Please do feel free to contribute in whatever capacity.