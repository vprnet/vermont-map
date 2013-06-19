#Vermont Choropleth

This repository contains the VPR Choropleth of the state of Vermont, with each town represented by it's own polygon.
The included csv maps population data to towns, though any CSV given the same list of towns could be used.

[Click here to see demo map](http://bl.ocks.org/mattparrilla/5724610)


##A Note on Political Boundaries

Vermont is a state with complex political boundaries due to it's small size. The basic unit of this map is the town.
In addition to towns (and cities, of which there are 9), there are also villages, gores, and grants. Villages are
treated as sublocalities by both the US Census Bureau and Google Maps, while gores and grants are considered full-fledged
localities, despite their small populations. To keep the map simple, sublocalities were rolled up into localities. This
means that **villages are not represented as separate entities on this map**, but instead have been absorbed by the town in
which they are physically located.

The one exception to this rule is the distinction in certain Vermont localities to differentiate between "town" and "city"
(i.e. Barre Town and Barre City). With simplicity again in mind, these "town" and "city" units have been combined into
one locality.

##Sources
[Vermont Center For Geographic Information](http://vcgi.vermont.gov/warehouse/search_tools)

- [Town Boundaries](http://maps.vcgi.org/gisdata/vcgi/packaged_zips/BoundaryTown_TWNBNDS.zip)
- [Lake Champlain](http://maps.vcgi.org/gisdata/vcgi/packaged_zips/WaterHydro_LKCH5K.zip)

[US Census Bureau](http://www.census.gov)

- [Vermont Population by City](http://www.census.gov/popest/data/cities/totals/2012/files/SUB-EST2012_50.csv)

(Click on links to download file)

##Author

Matt Parrilla, Web Developer, Vermont Public Radio
- http://twitter.com/mattparrilla
- http://github.com/mattparrilla

##Copyright and License

Copyright 2013 Vermont Public Radio

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language
governing permissions under the License.
