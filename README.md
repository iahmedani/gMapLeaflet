# Google Maps Layers for Leafletjs
Google map layers for Leaflet without api token.


Basic idea is to enable google map without using api token or key.
--------------------------------------------------------------------

A simple js file which helps you to create map with google map layers using leafletjs.

This library contains 4 types of google map layers listed below,

gStreets for googlemap street;
gHybrid for googlemap Hybrid (having satellite and street view together);
gSatellite for googlemap Satellite view;
gTerrain for googlemap havind terrain view;

Few more will shortly be added latter .......

Usage:
-------
A very simple way to use,

create a map using leaflet map and layer to that map as below;

var map = L.map('yourDivIdForMap').setview(['lat,lang'],'zoomlevel');

map.addLayer(gStreets);

sample links will be shared shortly.
