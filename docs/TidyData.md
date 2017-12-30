# Welcome to the tidyverse

## The tidyverse

All too often, data are messy. There are rows with no contents, colour-coded cells, and inconsistent values.

One important way that data can be cleaned is to ensure that the structure is tidy. What do we mean by tidy data?

> There are three interrelated rules which make a dataset tidy:
> * Each variable must have its own column.
> * Each observation must have its own row.
> * Each value must have its own cell.

And 

> Why ensure that your data is tidy? There are two main advantages:
> 
> 1. There’s a general advantage to picking one consistent way of storing data. If you have a consistent data structure, it’s easier to learn the tools that work with it because they have an underlying uniformity.
>
> 2. There’s a specific advantage to placing variables in columns because it allows R’s vectorised nature to shine. As you learned in mutate and summary functions, most built-in R functions work with vectors of values. That makes transforming tidy data feel particularly natural.

(from Hadley Wickham & Garrett Grolemund, [_R for Data Science_](http://r4ds.had.co.nz/))

This won't solve things like inconsistent values and colour-coded cells, but it will solve some other messiness.

For more about the principles of tidy data, see:

* Hadley Wickham, ["Tidy data", _The Journal of Statistical Software_, vol. 59, 2014.](https://www.jstatsoft.org/article/view/v059i10)
  + [alternate link:](http://vita.had.co.nz/papers/tidy-data.html)
  + [informal and code-heavy version](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html)
 

### Other references

Karl Broman and Kara Woo, ["Data organization in spreadsheets"](https://github.com/kbroman/Paper_DataOrg) (github page with source manuscript) -- application of tidy principles to spreadsheets.

* see also Karl Broman's tutorial, ["Data organization: organizing data in spreadsheets)


Jesse Sadler, [Excel vs R: A Brief Introduction to R  (With examples using dplyr and ggplot](http://kbroman.org/dataorg/](https://www.jessesadler.com/post/excel-vs-r/) (2017-10-02)

---

## Tidy Tools

### tidyverse R packages

[The tidyverse: ](http://tidyverse.org/)

[The tidyverse R packages on github](https://github.com/hadley/tidyverse)

#### `broom`


#### `dplyr`

CRAN: [dplyr: A Grammar of Data Manipulation](https://CRAN.R-project.org/package=dplyr)

github: [hadley/dplyr](https://github.com/hadley/dplyr)

**Articles**

* [Introduction to dplyr](http://stat545.com/block009_dplyr-intro.html), part of the UBC [STAT545: Data wrangling, exploration, and analysis with R](http://stat545.com/index.html) course materials


#### `purrr`

* [A purrr tutorial](https://github.com/Cascadia-R/purrr-tutorial) -- Cascadia-R, 2017-06-03

* Charlotte Wickham, [purr tutorial](https://github.com/cwickham/purrr-tutorial) -- github

### more about tidy data

* Hadley Wickham & Garrett Grolemund, [_R for Data Science_](http://r4ds.had.co.nz/)

* Hadley Wickham
  + [Tidy data and tidy tools (video of presentation, December 2011)](https://vimeo.com/33727555)

* Garrett Grolemund
  + [Data Tidying](http://garrettgman.github.io/tidying/) (part of [Data Science with R](http://garrettgman.github.io/))
  
* Chester Ismay and Ted Laderas, [A gRadual-intRoduction to the tidyverse](https://github.com/Cascadia-R/gRadual-intRoduction-tidyverse?utm_content=buffer98896&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)  
  


## Tidy Text

If  you're going to undertake text mining and natural language processing, your text (i.e. your data) needs to be tidy.  Fortunately, there's an R package for that: `tidytext`.

* Julia Silge, [Term Frequency and tf-idf Using Tidy Data Principles](http://juliasilge.com/blog/Term-Frequency-tf-idf/), 2016-06-27

(See the companion page on the topics of [text analysis and text mining](https://github.com/MonkmanMH/DataScienceResources/blob/master/TextAnalysis.md)).
