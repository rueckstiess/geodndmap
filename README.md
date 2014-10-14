geodndmap
=========

Drop GeoJSON file or selected text onto map to render it.

This is a modification of the example provided on the Google Maps API page, see
https://developers.google.com/maps/documentation/javascript/examples/layer-data-dragndrop

The GeoJSON strings are parsed and replaced with actual shapes, enabling `geodesic` mode to show mapping of great arcs for polygons and lines.

Supported GeoJSON objects are currently:

* Point
* LineString
* Polygon
* MultiPoint
* GeometryCollection

