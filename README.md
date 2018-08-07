README

Author: Evan Fraser


INTRODUCTION 

The code uses OpenLayer to present a map of the area west of DC that calculates geospatial distance between points. To do this, the user should click multiple consecutive points to set (lat,lon) positions on the map. Once a double click is made the application gathers all the points and calculates geospatial distances between each. The (lat,lon) and distances between each are presented below the map as html tables after the double click event.

OBJECTIVE 

The objective is to present a baseline for implementing nearest neighbor and traveling salesmen algorithms (TODO).  All based on line-of-sight as viewed from the visible map.

DEVELOPER NOTES 

The Javascript code is standalone and doesn’t require a web server. Simply extract to your machine, then double click the index.html file. Since its specifically for development purposes, you may benefit from viewing and interacting with the code via the developer console of your preferred web browser.

REFERENCE

OpenLayers
https://openlayers.org/en/latest/examples/

Stamen Maps
http://maps.stamen.com/
