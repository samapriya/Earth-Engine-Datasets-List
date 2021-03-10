[![gee_catalog](https://github.com/samapriya/Earth-Engine-Datasets-List/actions/workflows/gee_catalog.yml/badge.svg)](https://github.com/samapriya/Earth-Engine-Datasets-List/actions/workflows/gee_catalog.yml)

# Updated Dataset List (Included in Google Earth Engine)
The idea is to make this list machine readable so you can programmatically call assets based on filters and to have a list for users who are not yet registered but want to look at the dataset list within earth engine. Register for a free [Google Earth Engine account](https://earthengine.google.com/signup/). The datasets are generated as an always updated JSON file as well as a CSV file with the following setup

* [Always Updated JSON file](https://raw.githubusercontent.com/samapriya/Earth-Engine-Datasets-List/master/gee_catalog.json)

* [Always Updated CSV file](https://raw.githubusercontent.com/samapriya/Earth-Engine-Datasets-List/master/gee_catalog.csv)


|id                                                        |provider                                                                          |title                                                                                                                             |start_date|end_date  |startyear|endyear|type            |tags                                                                                                                                                                                                                                                                                                                                       |asset_url                                                                                                             |thumbnail_url                                                                                             |
|----------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|----------|----------|---------|-------|----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
|AAFC/ACI                                                  |Agriculture and Agri-Food Canada                                                  |Canada AAFC Annual Crop Inventory                                                                                                 |2009-01-01|2021-03-08|2009     |2020   |image_collection|aafc, canada, crop, landcover                                                                                                                                                                                                                                                                                                              |https://developers.google.com/earth-engine/datasets/catalog/AAFC_ACI                                                  |https://mw1.google.com/ges/dd/images/AAFC_ACI_sample.png                                                  |


The list allows for datasets to be built into a parser and we can pull these as though a dictionary for making selections before applying any other tool.

### Earth Engine Tools

* [geeadd](https://github.com/samapriya/gee_asset_manager_addon): This tool has had many iterations being developed to intergate additional features to google earthengine's own command line tool. Create an asset report, print your used and remaining quota, give permission to all assets in a folder to users and so on. You can read the [first Medium article here](https://medium.com/@samapriyaroy/google-earth-engine-asset-manager-and-addons-building-tools-of-the-trade-8eb493b21eda). **The most updated version lies in the [readme](https://github.com/samapriya/gee_asset_manager_addon/blob/master/README.md) and this tool is regularly updated.**

* [geeup](https://github.com/samapriya/geeup): As the name suggests this tool was designed to upload both images and tables to Google Earth Engine. This tool functions as a batch uploader while adding additional features to generate metadata, to parse any metadata into manifest and then allowing for you to upload these files into your assets. **This tool is constantly updated and the most updated [ReadMe](https://github.com/samapriya/geeup/blob/master/README.md) should be the best source on usage**

* [gee2drive](https://github.com/samapriya/gee2drive)This tool which allows you to run a terminal environment where your personal and general catalog images are part of a autosuggest feature. This tool allows you to look for images based on names for example " you can search for Sentinel and it will show you full path of images which have the word sentinel in the title". It also creates a report for your image collections and images so apart from the public datasets this can also find your own datasets as well. You can then generate bandlist to make sure all bands you are exporting are of the same type and then export all images that intersect you aoi. **This tool was currently updated and updated based on issues [ReadMe](https://github.com/samapriya/gee2drive/blob/master/README.md) should be the best source on usage**

* [ft2gee](https://github.com/samapriya/ft2gee): This is a lesser know tool but I wrote this tool so you can convert all your fusion tables into Google Earth Engine assets for continued use after December 2019 when fusion tables are discontinued. If you are interested in using this tool find the [Medium article with the complete tutorial here](https://medium.com/@samapriyaroy/google-fusion-table-migration-with-within-google-earth-engine-93d103111ce7). **This tool is not regularly updated but updates are based on GitHub issues.**

* [gee-takeout](https://github.com/samapriya/gee-takeout): This was born out of need to migrate all your earthengine assets and codes from one account to the other. This tool basically clones your Google Earth Engine account and is named after Google's beloved tool, Google Take Out. You can read the [Medium article and tutorial here](https://medium.com/@samapriyaroy/google-earth-engine-takeout-tools-and-guide-for-code-and-asset-transfer-aa865e0046e3). The tool was designed around those migrating between short lived accounts like university accounts and personal google accounts you get to keep. **This tool is not regularly updated but updates are based on GitHub** issues.

## Changelog
* Now uses Github workflow to generate parsed catalog
* Find most updated version [here](https://raw.githubusercontent.com/samapriya/Earth-Engine-Datasets-List/master/gee_catalog.json)
* Now uses STAC 1.0.0-beta.2
* Now inclues asset url and thumbnail_url
* Now uses STAC
* Now includes dataset tags

### Now updated every day
