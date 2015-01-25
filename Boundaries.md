---
title: Boundaries
permalink: /Boundaries/
---

This page is meant to cover different types of geospatial jurisdiction boundaries and the basic metadata associated with them. There is a separate project called [DemocracyMap](http://democracymap.org) which aims to better wrangle jurisdiction boundary data along with some of the broader metadata itself. You might also be interested in [Address](/Address "wikilink") data

Common National Boundaries
--------------------------

In the United States, the [Census](http://www2.census.gov/cgi-bin/shapefiles2009/national-files) provides boundary data for most high level jurisdictions, but hyperlocal data is more difficult to find. In the UK, you should be able to find all the boundary data you need via Ordnance Survey. Here's a [direct link to a 243mb zip file with all UK boundaries](http://grant.dev.openstreetmap.org/tmp/osfree/bdline_gb.zip) (hosted by openstreetmap) and you can learn more about UK [Boundary Line data at Ordnance Survey](http://www.ordnancesurvey.co.uk/oswebsite/products/boundaryline/).

Some of the main boundary data from the US Census is:

-   [US congressional districts](http://www.census.gov/geo/www/cob/cd110.html)
-   [State legislative districts](http://www.census.gov/geo/www/cob/sl2006.html)
-   [Counties](http://www2.census.gov/geo/tiger/TIGER2009/tl_2009_us_county.zip)
-   [Metropolitan Divisions](http://www2.census.gov/geo/tiger/TIGER2009/tl_2009_us_metdiv.zip)
-   [Zip Codes](http://www2.census.gov/geo/tiger/TIGER2009/tl_2009_us_zcta5.zip)
-   [School Districts Unified (2000)](http://www.census.gov/geo/www/cob/sn2000.html) & [School Districts Current](http://www.census.gov/did/www/schooldistricts/data/boundaries.html)

See <http://www2.census.gov/cgi-bin/shapefiles2009/national-files> for a full list of datasets

Local Boundaries
----------------

Many of these can be synonyms:

-   Borough
-   Ward
-   Census Tract
-   [Neighborhood](/Neighborhood "wikilink")
-   Police Precinct
-   Voting Precinct
-   City Council District
-   Public Utility District
-   Port District
-   Parks & Recreation District
-   Public Hospital District
-   Fire District
-   Water District
-   Block
-   [Building Lot](/Building_Lot "wikilink")
-   [Address](/Address "wikilink")

### Other Areas

-   Airport
-   Beach
-   Campground
-   [Cemetery](/Cemetery "wikilink")
-   Park
-   Parking Facility
-   Playground
-   RV Park
-   Zoo

APIs
----

-   [OpenStreetMaps Administrative Boundaries](http://wiki.openstreetmap.org/wiki/Tag:boundary%3Dadministrative)
-   [NationalMap.gov govunits APIs](http://services.nationalmap.gov/ArcGIS/rest/services/govunits/MapServer) - available via [REST](http://services.arcgisonline.com/ArcGIS/SDK/REST/index.html?export.html), SOAP, WMS ([<http://services.nationalmap.gov/ArcGIS/rest/services/govunits/MapServer/6/query?text>=&geometry=-73.9436111%2C40.7941667&geometryType=esriGeometryPoint&inSR=4326&spatialRel=esriSpatialRelWithin&where=&returnGeometry=false&outSR=&outFields=PLACE_NAME%2CSTATE_NAME&f=html example REST query] and [<http://services.nationalmap.gov/ArcGIS/rest/services/govunits/MapServer/6/query?text>=&geometry=-73.9436111%2C40.7941667&geometryType=esriGeometryPoint&inSR=4326&spatialRel=esriSpatialRelWithin&where=&returnGeometry=false&outSR=&outFields=PLACE_NAME%2CSTATE_NAME&f=pjson in JSON])
-   [Business.gov U.S. City and County Web Data API](http://www.business.gov/about/features/api/geodata/)
-   [FCC Census Block Conversions API](http://reboot.fcc.gov/developer/census-block-conversions-api)
-   [UK Ordnance Survey OpenSpace API](http://openspace.ordnancesurvey.co.uk/openspace/)
-   [SimpleGeo Pushpin Querying](http://simplegeo.com/docs/api-endpoints/pushpin-querying)

Other Resources
---------------

-   [DemocracyMap Data](http://pages.e-democracy.org/DemocracyMap_Data)
-   [OpenBlock/EBcode Data](http://developer.openblockproject.org/wiki/Data)

[Data_Standards](/Category:Data_Standards "wikilink")
