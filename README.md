# geojson_layers

Only to add a geoJSON to our layers control (tree structure) (i.e. designated areas for wind energy, protected areas, military areas). Otherwise use GeoLayers.
Use the same structure: you can modify your geoJSON file on QGIS, etc.

Name: COUNTRY_TYPE_LAYERNAME. 

      Examples: GERMANY_ENVIRONMENT_NATURA2000, DENMARK_CABLES_TELECOMCABLES

Attribute: SITE_NAME (there can be more attributes if convenient)

Type: MultiPolygon, MultiPoint

EPSG: 4326

      Example:

      {
      "type": "FeatureCollection",
      "name": "COUNTRY_TYPE_LAYERNAME",
      "crs": { "type": "name", "properties": { "name": "urn:ogc:def:crs:OGC:1.3:CRS84" } },
      "features": [
            { "type": "Feature", "properties": { "SITE_NAME": "[ADD SITE NAME]" }, "geometry": { "type": "MultiPolygon", 
                  "coordinates": [ [ [ [ 77.620005737750006, 7.981995028527778 ], [ 77.645588884083338, 8.062183859361111 ], 
                      [ 77.681388220972224, 8.063079081 ], [ 77.743692710805561, 7.870508620694444 ],...

![image](https://user-images.githubusercontent.com/92600785/205265402-412bfae1-a60f-4d8f-9813-7e4b748aa09c.png)
