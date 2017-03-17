# Google Map Layers for Leafletjs
Google map layers for Leaflet without api token.


Basic idea is to enable google map without using api token or key.
--------------------------------------------------------------------

A simple js file which helps you to create map with google map layers using leafletjs.

This library contains 4 types of google map layers listed below,

1. gStreets for googlemap street;
2. gHybrid for googlemap Hybrid (having satellite and street view together);
3. gSatellite for googlemap Satellite view;
4. gTerrain for googlemap having terrain view;

Still more to come... 

Usage:
-------
A very simple way to use,

create a map using leaflet map and layer to that map as below;

var map = L.map('yourDivIdForMap').setview(['lat,lang'],'zoomlevel');

map.addLayer(gStreets);

sample links will be shared shortly.
