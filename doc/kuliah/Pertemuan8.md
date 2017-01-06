Map Proxy is an open source proxy for geospatial data. These caches accelerate and transform data from existing map services and serves any desktop or web GIS client.
How to pass MapProxy configuration, namely:
1. Create a folder MapData in / var on drektori create a new directory with the name shp, mapfile, tmp and common
2. Smpan vector file shapefile map didirektori / VAW / MapData / shp (sample province map file)
3. Edit the file /var/mymapproxy/mapproxy.yml adapted to record configuration
4. Then run the command mapproxy
# Mapproxy-util-develop mapproxy.yml serve -b 0.0.0.0

Fitriani M
1144001
D4 TI 3D
