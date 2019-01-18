# Internal dependencies for Carto Mobile SDK

This repository contains various libraries that are used by CARTO Mobile SDK.
These libraries have no dependencies with the rest of the SDK, so they
are kept as a separate project.

The libraries included in the project are:

* VT - low level vector tile rendering library using OpenGL
* MapnikVT - higher-level vector tile rendering library that uses Mapnik-like XML style definition language
* CartoCSS - an extended CartoCSS parser and translator to MapnikVT
* NML - simple library for loading and rendering 3D models converted from Collada DAE files
* Routing - a mobile-friendly routing library that uses routing graphs converted from OSRM data and provides optimized routing using Contraction Hierarchies.
* Geocoding - a mobile-friendly geocoding library that uses special sqlite geocoding databased converted from Pelias importer data
* MBVTBuilder - a simple library for building MapBox vector tiles from GeoJSON features
