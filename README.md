# mytracks

Collection of my Geo data.

Useful Software:
- [Google MyTracks](https://en.wikipedia.org/wiki/MyTracks)
- [GDAL - Geospatial Data Abstraction Library](http://www.gdal.org/index.html)

Useful Command:
``` bash
sudo apt-get install gdal-bin
unzip 2015-07-17\ 13-50.kmz
ogr2ogr -f GeoJSON track.json doc.kml
```
