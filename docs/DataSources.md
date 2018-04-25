# Data Sources & How to Read Them

### Introduction

What is data science without _data_?  Links to tools to import data from a variety of sources, along with a few indexes and compendiums of data sources.

---
### Sources

University of Alberta Libraries, Economics: [List of databases](http://guides.library.ualberta.ca/c.php?g=329741&p=2334221)

Simon Fraser University Library: [Gender, Sexuality & Women's Studies Information Resources: Facts & Data](http://www.lib.sfu.ca/help/research-assistance/subject/gsws/factsdata)

#### R packages


##### `cancensus`

[Census of Canada (including the National Household Survey)](https://github.com/mountainMath/cancensus)


##### `gapminder`

[gapminder: Data from Gapminder](https://cran.r-project.org/web/packages/gapminder/index.html) An excerpt of the data available at [Gapminder.org]. For each of 142 countries, the package provides values for life expectancy, GDP per capita, and population, every five years, from 1952 to 2007. 


##### `Lahman`

[Lahman: Sean 'Lahman' Baseball Database](https://cran.r-project.org/web/packages/Lahman/)  Provides the tables from the 'Sean Lahman Baseball Database' as a set of R data.frames. It uses the data on pitching, hitting and fielding performance and other tables from 1871 through 2015, as recorded in the 2016 version of the database.


---
### R readers

**articles**

[R database interfaces](http://www.burns-stat.com/r-database-interfaces/)


#### `googledrive`

**package**

CRAN page: _currently only development version_, see tidyverse link below 

tidyverse page: [`googledrive`](https://tidyverse.github.io/googledrive/)



#### `foreign`

**package**

CRAN page: [foreign: Read Data Stored by Minitab, S, SAS, SPSS, Stata, Systat, Weka, dBase, ...]( https://CRAN.R-project.org/package=foreign)

**articles**

* [How to open an SPSS file into R](http://www.milanor.net/blog/how-to-open-an-spss-file-into-r/), by Davide Massidda (2014-03-26)


#### `TSdbi` and related packages

**package**

CRAN page: [TSdbi: Time Series Database Interface]( https://CRAN.R-project.org/package=TSdbi)

Note: `TSdbi` has some related extension packages:

* CRAN page: [TSdata: 'TSdbi' Illustration](https://cran.r-project.org/web/packages/TSdata/index.html)
*  This package gives an overview and usage examples for all the `TSdbi` family of packages

* CRAN page: [TSPostgreSQL: 'TSdbi' Extensions for 'PostgreSQL'](https://cran.r-project.org/web/packages/TSPostgreSQL/index.html)

* CRAN page: [TSsdmx: 'TSdbi' Extension to Connect with 'SDMX'](https://cran.r-project.org/web/packages/TSsdmx/index.html)


