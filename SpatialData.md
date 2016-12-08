# Spatial Data (a.k.a. mapping)

### Introduction

Cartographic design principles
 
* U.K. Ordnance Survey, ["Cartographic design principles"](https://www.ordnancesurvey.co.uk/resources/carto-design/carto-design-principles.html)

Choropleth maps

* vis4net, ["Why we didn’t use a cartogram in the Brexit map"](http://vis4.net/blog/posts/to-cartogram-or-not-to-cartogram-the-brexit/) (2016)

---
### Theory and methods


#### Canadian geography: shapefiles

**Statistics Canada** has made available a variety of boundary files.

* [Boundary files](https://www12.statcan.gc.ca/census-recensement/2011/geo/bound-limit/bound-limit-eng.cfm)

* [2011 Census - Boundary files](https://www12.statcan.gc.ca/census-recensement/2011/geo/bound-limit/bound-limit-2011-eng.cfm)

**DataBC** has a number of of geographic boundary files available

* [Boundaries](https://catalogue.data.gov.bc.ca/dataset?q=iso_topic_string%3A%2Aboundaries%2A)

* [Provincial Electoral Districts - Electoral Boundaries Redistribution, 2008](https://catalogue.data.gov.bc.ca/dataset/provincial-electoral-districts-electoral-boundaries-redistribution-2008)

#### Geographic references

[Spatial Reference](http://www.spatialreference.org/) -- URL/URI-based references to spatial reference systems, including EPSG and ESRI.

---
### R

#### Mapping in R: tutorials, etc.

Roger S. Bivand, Edzer J. Pebesma, and Virgilio Gómez-Rubio (2008) [_Applied Spatial Data Analysis with R_](http://gis.humboldt.edu/OLM/r/Spatial%20Analysis%20With%20R.pdf) {PDF version of text book}

Frank Davenport (2012) ["Notes from A Recent Spatial R Class I Gave"](http://davenportspatialanalytics.squarespace.com/blog/2012/6/19/notes-from-a-recent-spatial-r-class-i-gave.html)

Nick Eubank, [Merging Spatial Data](http://www.nickeubank.com/wp-content/uploads/2015/10/RGIS2_MergingSpatialData_part1_Joins.html)

Tomislav Hengl, [_A Practical Guide to Geostatistical Mapping_](http://spatial-analyst.net/book/) {PDF ebook available via Lulu}

Robin Lovelace (2014) ["R, an Integrated Statistical Programming Environment and GIS"](http://robinlovelace.net/r/2014/11/28/r-as-a-gis-geoinformatics.html) {blog post}

Robin Lovelace, James Cheshire and others, 2015-, [_Introduction to visualising spatial data in R_](https://cran.r-project.org/doc/contrib/intro-spatial-rl.pdf) {or up-to-date version on github, [Robinlovelace/Creating-maps-in-R](https://github.com/Robinlovelace/Creating-maps-in-R)}

Sharon Machlis, 2016-03-01, [Create maps in R in 10 (fairly) easy steps](http://www.computerworld.com/article/3038270/data-analytics/create-maps-in-r-in-10-fairly-easy-steps.html), Computerworld.

Francisco Rodriguez-Sanchez, 2013-12-18, [Spatial data in R: Using R as a GIS](https://pakillo.github.io/R-GIS-tutorial/) {github version at [Pakillo/R-GIS-tutorial](https://github.com/Pakillo/R-GIS-tutorial/blob/master/R-GIS_tutorial.md)}

[R Spatial Cheatsheet](http://www.maths.lancs.ac.uk/~rowlings/Teaching/UseR2012/cheatsheet.html) {from Barry Rowlingson's [Geosppatial Data in R and Beyond](http://www.maths.lancs.ac.uk/~rowlings/Teaching/UseR2012/index.html) tutorial site}


**tips and tricks**


[creating a spatial object](http://stackoverflow.com/questions/29736577/how-to-convert-data-frame-to-spatial-coordinates)

[Mapping (historic) tracks in ggplot2](http://spatial.ly/2016/10/mapping-historic-tracks-ggplot2/)

[geostat-course.org](http://geostat-course.org/aggregator/sources/2?page=24&ui=default)


[Making Maps with R](http://www.molecularecologist.com/2012/09/making-maps-with-r/)


#### Canadian examples: maps in R

[Canadian census map division in R](http://www.scriptscoop2.com/t/9bec270a9183/canadian-census-map-division-in-r.html)

[Choropleth Maps with R and ggplot2](http://unconj.ca/blog/choropleth-maps-with-r-and-ggplot2.html)


---

# R Packages

#### `choroplethr`

**package**

CRAN page: [choroplethr: Simplify the Creation of Choropleth Maps in R](https://cran.r-project.org/web/packages/choroplethr/index.html)

**articles**

[Ari Lamstein's blog](http://www.arilamstein.com/blog/)

[Combining Choropleth Maps and Reference Maps in R](http://www.arilamstein.com/blog/2015/09/30/combining-choropleth-maps-and-reference-maps-in-r/)

[Creating Administrative Choropleth Maps Using R](https://www.gislounge.com/creating-administrative-maps-using-r/)

[Easy data maps with R: the choroplethr package](http://blog.revolutionanalytics.com/2014/01/easy-data-maps-with-r-the-choroplethr-package-.html)

[How to Change the Reference Map in Choroplethr](http://www.arilamstein.com/blog/2015/10/08/how-to-change-the-reference-map-in-choroplethr/)

#### `ggmap`

**package**

CRAN page: [ggmap: Spatial Visualization with ggplot2]
(https://cran.r-project.org/web/packages/ggmap/index.html)

**articles**

[Creating a custom soil attribute plot using ggmap](http://blog.revolutionanalytics.com/2015/01/creating-a-custom-soil-attribute-plot-using-ggmap.html)

[ggmap: Spatial Visualization with ggplot2](https://journal.r-project.org/archive/2013-1/kahle-wickham.pdf) by David Kahle and Hadley Wickham, _The R Journal_ Vol. 5/1, June 2013, pp.144-161.

[Plotting Choropleths from Shapefiles in R with ggmap – Toronto Neighbourhoods by Population](http://www.r-bloggers.com/plotting-choropleths-from-shapefiles-in-r-with-ggmap-toronto-neighbourhoods-by-population/)

[R & GGMap Visualization Case Study](http://www.r-bloggers.com/r-ggmap-visualization-case-study/)

[Visualising Crime Hotspots in England and Wales using {ggmap}](http://www.r-bloggers.com/visualising-crime-hotspots-in-england-and-wales-using-ggmap-2/)


#### `GISTools`

**package**

CRAN page: [GISTools: Some further GIS capabilities for R]
(https://cran.r-project.org/web/packages/GISTools/index.html)

**articles**

#### `idbr`

**package**

CRAN page: [idbr: R Interface to the US Census Bureau International Data Base API](https://cran.r-project.org/web/packages/idbr/)

github page: [idbr](https://github.com/walkerke/idbr)

**articles**

Kyle Walker, [Visualizing international demographic indicators with idbr and Plotly](http://walkerke.github.io/2016/01/idbr/)


#### `leaflet`

**package**

CRAN: [leaflet: Create Interactive Web Maps with the JavaScript 'Leaflet' Library](https://cran.r-project.org/web/packages/leaflet/index.html)

RStudio on github: [rstudio/leaflet](https://github.com/rstudio/leaflet)

**articles**

[Leaflet for R](http://rstudio.github.io/leaflet/)

Robin Lovelace, [The leaflet package for online mapping in R](https://www.r-bloggers.com/the-leaflet-package-for-online-mapping-in-r/)



#### `sp`

**package**

CRAN: [sp: Classes and Methods for Spatial Data](https://cran.r-project.org/web/packages/sp/index.html)

vignettes: Edzer Pebesma and Roger S. Bivand (2005): [Classes and Methods for Spatial Data: the sp Package](https://cran.r-project.org/web/packages/sp/vignettes/intro_sp.pdf)


**articles**

Edzer Pebesma (2008) [Introduction to R and package sp](http://pebesma.staff.ifgi.de/Aufbaukurs/R/slides_R.pdf)


-30-
