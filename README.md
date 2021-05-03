# Medium Satellite Imagery 

This repository is meant to allow reproducibility of the steps provided in an [article on 
preprocessing satellite imagery for machine learning application](https://medium.com/artefact-engineering-and-data-science/LINK_TO_ARTICLE) 
showcased in the [Artefact tech medium](https://medium.com/artefact-engineering-and-data-science)
 
 
All the code is included in `notebooks/preprocessing_satellite_imagery.ipynb`

Before running the notebook, do the following steps first:

- run `pip install requirements.txt`
- create a geojson file of the zone you want a satellite imagery of and save it in `data/target_zone.geojson`
- create an account at [Coppernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/home). 
Write the username and the password in a json file and save it in `secrets/sentinel_api_credentials.json`.
Format: `{"username": "XXXX", "password": "XXXX"}`


