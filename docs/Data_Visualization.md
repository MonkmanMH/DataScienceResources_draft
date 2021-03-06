# Data Visualization

### Introduction

This is an _enormous_ topic. 

But start here: 

* Alan Smith, ["Data visualisation: it is not all about technology"](https://www.ft.com/content/aba6c58e-5a8e-11e7-9bc8-8055f264aa8b?accessToken=zwAAAVz0i_FYkdOrpsWOWo4R59ObyIBV8mSqiw.MEQCIFBdm394GSC6W-YIMME93SN8BgAuLEfyK8nFshbAiyu-AiBx6Qx4Ivd3qh-VSfIlwrf5tYKdnbGId1n0pzxZFUwDsQ&sharetype=gift), _Financial Times_, 2017-06-28

* Cole Nussbaumer Knaflic, [_Storytelling with Data_] (Wiley). A great introduction to the fundamentals of good visualization. The [companion blog](https://www.storytellingwithdata.com/) has is an on-going series of further dives into the topic.

* Elijah Meeks, ["What Charts Do"](https://medium.com/@Elijah_Meeks/what-charts-do-48ed96f70a74), 2018-05-21


#### General resources

* Kieran Healy (2018, work in progress) [_Data Visualization: A practical introduction_](http://socviz.co/)

* Claus O. Wilke (2019, full draft) [_Fundamentals of Data Visualization_](http://serialmentor.com/dataviz/)

  - Note that Wilke notes that this is a platform-agnostic book, but it was written in R's `bookdown` and uses `ggplot2` for all of the figures.

  - [the github repo for the book](https://github.com/clauswilke/dataviz) (in case you want to plagiarize the code for a specific figure)


* Tamara Munzer, [list and links to talks](http://www.cs.ubc.ca/~tmm/talks.html?utm_content=bufferd5cd8&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer#cj16)


* Kate Moran, 2017-08-06, ["How to Present Scientific Findings Online"](https://www.nngroup.com/articles/scientific-findings-online/) (file under: Know Your Audience)

* Richard Brath & Ebad Banissi, 2016, ["Using Typography to Expand the
Design Space of Data Visualization"](https://www.sciencedirect.com/science/article/pii/S2405872616300107), _She Ji: The Journal of Design, Economics, and Innovation_, Vol. 2, Issue 1, Spring 2016

* Steve Franconeri, [Chart Chooser](http://experception.net/)

* PolicyViz, [DataViz Cheatsheet](https://policyviz.com/2018/08/07/dataviz-cheatsheet/) (2018-08-07)

* [Enrico Bertini's homepage](http://enrico.bertini.io/) -- a plethora of articles and resources on data visualization

* [Data Visualization Inventors, Founders, and Developers](https://policyviz.com/2019/01/09/data-visualization-inventors-founders-and-developers/) -- credit where credit is due



**Theory**

* Kennedy Elliot (2016-05-02) [39 studies about human perception in 30 minutes](https://medium.com/@kennelliott/39-studies-about-human-perception-in-30-minutes-4728f9e31a73)


**"Visualization literacy"

* Michael Correll (2018-11-20) [What Does “Visualization Literacy” Mean, Anyway?](https://medium.com/multiple-views-visualization-research-explained/what-does-visualization-literacy-mean-anyway-22f3b3badc0) 

---

### R Resources

#### general

* [R Graph Catalog](http://shiny.stat.ubc.ca/r-graph-catalog/) -- an unbeatable resource for making good graphs in R, described by the creators as "a complement to _Creating More Effective Graphs_ by Naomi Robbins." 

* [Shiny apps for statistics](https://statistics.calpoly.edu/shiny) -- by the Statistics Department at CalPoly

* Kieran Healy, [_Data Visualization for Social Science_](http://socviz.co/)



#### ggplot2 -- the pre-eminent way to create charts and graphs in R

* [ggplot2: part of the tidyverse](http://ggplot2.tidyverse.org/index.html) -- reference materials, examples, etc etc. Start here.

* [Top 50 ggplot2 Visualizations - The Master List (With Full R Code)](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html)

* [A Compendium of Clean Graphs in R](http://shinyapps.org/apps/RGraphCompendium/index.php), by Eric-Jan Wagenmakers and Quentin F. Gronau

* [BBC Visual and Data Journalism cookbook for R graphics](https://bbc.github.io/rcookbook/)

   - [`bbplot`](https://github.com/bbc/bbplot), a package with their templates etc.
   
   - ["How the BBC Visual and Data Journalism team works with graphics in R"](https://medium.com/bbc-visual-and-data-journalism/how-the-bbc-visual-and-data-journalism-team-works-with-graphics-in-r-ed0b35693535)



** ggplot2 tips and tricks **

* Simon Jackson, 2016-08-11, [Plotting background data for groups with ggplot2](https://drsimonj.svbtle.com/plotting-background-data-for-groups-with-ggplot2)

* Laura Ellis, 2018-08-01, [Highlighting with ggplot2: The Old School and New School Way](https://www.littlemissdata.com/blog/highlight)


** _Note:_**

There are many extension packages that allow you to make other visualizaitons in `ggplot2`; they are referenced below.


#### Plotly

Plotly for R allows you to "Create interactive, D3 and WebGL charts in R" (their words, not mine). A great resource for upping the content of online visualizations.

* Carson Sievert, [_Plotly for R_](http://plotly-book.cpsievert.me/)

---

### Chart types: theory and methods



#### Box plots (a way to visualize distributions)

R package [`boxplot`](https://stat.ethz.ch/R-manual/R-devel/library/graphics/html/boxplot.html)

Laura DeCicco, 2018-08-10, [Exploring ggplot2 boxplots - Defining limits and adjusting style](https://owi.usgs.gov/blog/boxplots/)

Ron Pearson, 2011-01-29, [Boxplots and Beyond – Part I](https://www.r-bloggers.com/boxplots-and-beyond-part-i/) (first in a multi-part series on various distribution plots)


<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">More papers should use this plot type!! <a href="https://t.co/iEglulaMyM">pic.twitter.com/iEglulaMyM</a></p>&mdash; Johanna Rickne (@johannarickne) <a href="https://twitter.com/johannarickne/status/1028174230146478080?ref_src=twsrc%5Etfw">August 11, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


#### Density plot

* Jodie Burchell, 2016-03-16, [Creating plots in R using ggplot2 - part 8: density plots](http://t-redactyl.io/blog/2016/03/creating-plots-in-r-using-ggplot2-part-8-density-plots.html)


#### Dot plot (Cleveland dot plot, lollipop plot)

* UC Business Analytics R Programming Guide, [Cleveland Dot Plots](https://uc-r.github.io/cleveland-dot-plots)

* Nina Zumel (2013-02-18) [Revisiting Cleveland’s The Elements of Graphing Data in ggplot2](http://www.win-vector.com/blog/2013/02/revisiting-clevelands-the-elements-of-graphing-data-in-ggplot2/)

* [Datavis with R: Drawing a Cleveland dot plot with ggplot2](http://www.joyce-robbins.com/blog/2016/06/02/datavis-with-rdrawing-a-cleveland-dot-plot-with-ggplot2/)


#### Eikosograms

> an eikosogram is a picture of probability. It visually partitions a unit square into rectangular regions whose areas give the numerical values of various probabilities. The construction is such that each rectangular region is identified with the value of one or more categorical variates. 
> _R.W. Oldford_

* R.W. Oldford (2018-08-16) [Introduction to eikosograms](https://cran.r-project.org/web/packages/eikosograms/vignettes/introduction.html)


#### Flow visualizations

**1. Circle plots**

* a.k.a. [Circos plot](http://circos.ca/)

* David Smith, [Global Migration, animated with R](http://blog.revolutionanalytics.com/2018/06/global-migration-animated-with-r.html), 2018-06-29

**2. Sankey plots**

[Interactive flow visualization in R](http://personal.tcu.edu/kylewalker/interactive-flow-visualization-in-r.html); Kyle Walker, 2016-06-26

[How to Make a D3 Sankey diagram in R](http://emapr.ceoas.oregonstate.edu/pages/education/how_to/sankey_diagram/sankey_diagram_to_visualize_landcover_change.html)



#### Heatmaps

[The Heatmap function](https://www.r-graph-gallery.com/215-the-heatmap-function/) in the [R Graph Gallery](https://www.r-graph-gallery.com/)

Rebecca L. Barter & Bin Yu, 2017-01-30, ["Superheat: An R package for creating beautiful and extendable heatmaps for visualizing complext data"](https://arxiv.org/pdf/1512.01524.pdf)



#### Histograms and their variants

[Variable width column charts](https://learnr.wordpress.com/2009/03/29/ggplot2_marimekko_mosaic_chart/) (in ggplot2)

[Mosaic or Marimekko charts](https://learnr.wordpress.com/2009/03/29/ggplot2_marimekko_mosaic_chart/) (in ggplot2)

Aran Lunzer and Amelia McNamara, [What's so hard about histograms?](http://tinlizzie.org/histograms/)


#### Lexis diagrams

Tim RiffeEmail author, Jonas Schöley and Francisco Villavicencio (2017) ["A unified framework of demographic time"](http://genus.springeropen.com/articles/10.1186/s41118-017-0024-4), _Genus: Journal of Population Sciences_, 2017 73:7


#### Network graphs

[DiagramR: Graph and network visualization using tabular data in R](DiagrammeR: Graph/Network Visualization)

* [github repo](https://github.com/rich-iannone/DiagrammeR)

* [DiagrammeRsvg: Export DiagrammeR Graphviz Graphs as SVG](https://cran.r-project.org/web/packages/DiagrammeRsvg/index.html)


[ggnet2: network visualization with ggplot2](https://briatte.github.io/ggnet/) -- part of the [`GGally`](https://www.rdocumentation.org/packages/GGally/versions/1.3.2) package



#### Population Pyramids

[Population pyramid plots get their own page](Data_Visualization_PopulationPyramids.md)



#### Ridgeline plot


** ridgeline plots in R **

[`ggridges` package by Claus Wilke](https://cran.r-project.org/web/packages/ggridges/index.html) -- CRAN page

Alex Whan, 2016-03-24, [ggplot2 and Joy Division](http://alexwhan.com/2016-03-24-joy-division-plot) - at Incrutable Errors

Mauricio Vargas S., 2016-11-08, [Joy Division’s Unknown PleasuRes](https://www.r-bloggers.com/joy-divisions-unknown-pleasures/) - at R-Bloggers

Henrik Lindberg, [Sports: Time of Day](https://github.com/halhen/viz-pub/tree/master/sports-time-of-day)

* [plot code](https://github.com/halhen/viz-pub/blob/master/sports-time-of-day/2_gen_chart.R)



** _Unknown Pleasures_ **

The over of Joy Division's debut album [_Unknown Pleasures_](https://en.wikipedia.org/wiki/Unknown_Pleasures) (1979) is perhaps the most famous ridgeline plot.

* Jen Christiansen, 2015-02-18, [Pop Culture Pulsar: Origin Story of Joy Division’s Unknown Pleasures Album Cover](https://blogs.scientificamerican.com/sa-visual/pop-culture-pulsar-origin-story-of-joy-division-s-unknown-pleasures-album-cover-video/) - _Scientific American_, [SA Visual](https://blogs.scientificamerican.com/sa-visual/) -- a great piece that traces the Joy Division album cover image directly back to the PhD dissertation of Harold D. Craft, Jr.

  - Adam Cap, 2011-05-19 - 2016-02-13, [The History of Joy Division’s “Unknown Pleasures” Album Art](https://adamcap.com/2011/05/19/history-of-joy-division-unknown-pleasures-album-art/)

  - [Data Visualization, Reinterpreted by VISUALIZED](https://vimeo.com/51365288): Peter Saville on the Design + Effect of Joy Division's "Unknown Pleasures" - ([from Visualized](https://vimeo.com/visualized))




#### Slopegraphs

[Slopegraphs get their own page](Data_Visualization_Slopegraphs.md)



#### Ternary plots

[`ggtern` - an extension to `ggplot2`](http://www.ggtern.com/) for plotting ternary diagrams.



#### Waffle plots

[Infographic-style charts using the R waffle package](https://nsaunders.wordpress.com/2017/09/08/infographic-style-charts-using-the-r-waffle-package/amp/)


---

### Further Reading

Naomi Robbins (2013), _Creating More Effective Graphs_, Chart House.

-30-
