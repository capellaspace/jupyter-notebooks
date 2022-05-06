# jupyter-notebooks
Jupyter notebooks for accessing Capella's API and basic SAR change detection.

## Providing Credentials

Your username and password must be saved in a .json file named 'credentials.json'.
The file should be placed in the parent directory (one level above the notebook) if possible. 
Otherwise you can edit each notebook to point at the location of your credentials.json file.
Format the credential file a follows.

{"username": "yourusername","password": "xxxxxxxxx"}

## Tasking

 - Capella-API-task-example.ipynb (to how task satellites from the API)
 
 - Capella-API-task-monitor-accepted-example.ipynb (how to monitor task and collection activities)
 
## Catalog Search, Order and Download

Capella-API-search-order-and-download-example.ipynb (find data in the catalog, order it, and download it)

## Working with Capella Open Data

Capella-API-Open-Data-search.ipynb (search example using open data. Visual map shows open data footprints)

## Tools

 - Capella-Log-Ratio-Change-Detection-Example-Using-API-and-COGs.ipynb (simple pixel based change detection from two Capella GEO images)

 - Capella-Time-Series-GIF-Example.ipynb (Create a timeseries GIF from two or more Capella GEO images)

## Examples for working with Capella data using TileDB

 - various examples