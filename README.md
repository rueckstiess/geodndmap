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

### Usage

You need to replace the string `<insert API key here>` with your actual Google Maps API key. Information about how to optain a key can be found here: https://developers.google.com/maps/documentation/javascript/tutorial#api_key

Then open the `index.html` with your browser (Chrome recommended), drag&drop a GeoJSON file or selected text onto the map, and see it rendered. As an example, you can select and drag this polygon definition below: 

```json
{
  "type": "Polygon",
  "coordinates": [
    [
      [
        -80.267831,
        42.050312
      ],
      [
        -80.267831,
        45.003652
      ],
      [
        -73.362579,
        45.003652
      ],
      [
        -73.362579,
        42.050312
      ],
      [
        -80.267831,
        42.050312
      ]
    ]
  ]
}
``` 