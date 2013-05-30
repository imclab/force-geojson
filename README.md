# force-geojson

Marrying [d3js](http://d3js.org/)'s [force directed graph implementation](http://bl.ocks.org/mbostock/4062045)
with [GeoJSON](http://www.geojson.org/) so you can abuse map-making tools
like [TileMill](http://www.mapbox.com/tilemill/) to make big big force directed
graphs.

    npm install -g force-geojson

    force-geojson foo.json > foo.geojson

The input needs to be formatted like d3 wants it to be: [read the docs](https://github.com/mbostock/d3/wiki/Force-Layout).

Takes a few options:

* `times`: how many iterations to work on the graph position
* `padx`: how close points can get to -180 and 180 longitude
* `pady`: how close points can get to -90 and 90 latitude