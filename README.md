# hawker-nearby

* Scraped the [Hawker United Dabao 2020 facebook page](https://www.facebook.com/groups/HawkersUnited2020/) and MissTamChiak's #savefnbsg [directory](https://www.misstamchiak.com/savefnbsg/) using [pandas read_html](https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.read_html.html).

* Used gis to [batch geocode](https://developers.arcgis.com/python/guide/batch-geocoding/) the addresses

* Used mapbox Isochrone API to generate the isochrone polygone, then used [turf.intersect()](https://turfjs.org/docs/) to find the hawker stores which reside in the polygon

* Finally converted the data to geojson using [geojson.io](https://geojson.io/)  
  
# acknowledgements

* [cerivitos](https://github.com/cerivitos/INeedToilet) for providing the tools he used

* Hawker United facebook group and MissTamChiak's directory for the data.


 
