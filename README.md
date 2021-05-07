[![gee_catalog](https://github.com/samapriya/Earth-Engine-Datasets-List/actions/workflows/gee_catalog.yml/badge.svg)](https://github.com/samapriya/Earth-Engine-Datasets-List/actions/workflows/gee_catalog.yml)
![GEE STAC Catalog](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/samapriya/34bc0c1280d475d3a69e3b60a706226e/raw/gee_catalog.json)

# Updated Dataset List (Included in Google Earth Engine)
The idea is to make this list machine readable so you can programmatically call assets based on filters and to have a list for users who are not yet registered but want to look at the dataset list within earth engine. Register for a free [Google Earth Engine account](https://earthengine.google.com/signup/). The datasets are generated as an always updated JSON file as well as a CSV file with the following setup

* [Always Updated JSON file](https://raw.githubusercontent.com/samapriya/Earth-Engine-Datasets-List/master/gee_catalog.json)

* [Always Updated CSV file](https://raw.githubusercontent.com/samapriya/Earth-Engine-Datasets-List/master/gee_catalog.csv)


|id                                                        |provider                                                                          |title                                                                                                                             |start_date|end_date  |startyear|endyear|type            |tags                                                                                                                                                                                                                                                                                                                                       |asset_url                                                                                                             |thumbnail_url                                                                                             |
|----------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|----------|----------|---------|-------|----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
|AAFC/ACI                                                  |Agriculture and Agri-Food Canada                                                  |Canada AAFC Annual Crop Inventory                                                                                                 |2009-01-01|2021-03-08|2009     |2020   |image_collection|aafc, canada, crop, landcover                                                                                                                                                                                                                                                                                                              |https://developers.google.com/earth-engine/datasets/catalog/AAFC_ACI                                                  |https://mw1.google.com/ges/dd/images/AAFC_ACI_sample.png                                                  |


The list allows for datasets to be built into a parser and we can pull these as though a dictionary for making selections before applying any other tool.

**Also check out the [awesome-gee-community-datasets project](https://samapriya.github.io/awesome-gee-community-datasets/) that provides additional datasets to the ones listed here.**

### Earth Engine Tools

* [geeadd](https://github.com/samapriya/gee_asset_manager_addon): This tool has had many iterations being developed to intergate additional features to google earthengine's own command line tool. Create an asset report, print your used and remaining quota, give permission to all assets in a folder to users and so on. You can read the [first Medium article here](https://medium.com/@samapriyaroy/google-earth-engine-asset-manager-and-addons-building-tools-of-the-trade-8eb493b21eda). **The most updated version lies in the [readme](https://samapriya.github.io/gee_asset_manager_addon/) and this tool is regularly updated.**

* [geeup](https://github.com/samapriya/geeup): As the name suggests this tool was designed to upload both images and tables to Google Earth Engine. This tool functions as a batch uploader while adding additional features to generate metadata, to parse any metadata into manifest and then allowing for you to upload these files into your assets. **This tool is constantly updated and the most updated [ReadMe](https://samapriya.github.io/geeup) should be the best source on usage**


* [earthengine standalone tools](https://github.com/samapriya/earthengine-standalone-tools)Standalone tools for Google Earth Engine operations. To get all the tools clone the repo and install requirements. Tools are added adhoc not set frequency but the idea is to be able to bring them to a single place of reference.

* [gee-takeout](https://github.com/samapriya/gee-takeout): This was born out of need to migrate all your earthengine assets and codes from one account to the other. This tool basically clones your Google Earth Engine account and is named after Google's beloved tool, Google Take Out. You can read the [Medium article and tutorial here](https://medium.com/@samapriyaroy/google-earth-engine-takeout-tools-and-guide-for-code-and-asset-transfer-aa865e0046e3). The tool was designed around those migrating between short lived accounts like university accounts and personal google accounts you get to keep. **This tool is not regularly updated but updates are based on GitHub** issues.

## Changelog
* Now uses Github workflow to generate parsed catalog
* Find most updated version [here](https://raw.githubusercontent.com/samapriya/Earth-Engine-Datasets-List/master/gee_catalog.json)
* Now uses STAC 1.0.0-beta.2
* Now inclues asset url and thumbnail_url
* Now uses STAC
* Now includes dataset tags

### Now updated every day
