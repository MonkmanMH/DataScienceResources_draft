# Welcome to the tidyverse

## The tidyverse

All too often, data are messy. 

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


### tidyverse R packages

[The tidyverse R packages](https://github.com/hadley/tidyverse)


## Tidy Data

* Hadley Wickham & Garrett Grolemund, [_R for Data Science_](http://r4ds.had.co.nz/)

* Hadley Wickham, ["Tidy data", _The Journal of Statistical Software_, vol. 59, 2014.](https://www.jstatsoft.org/article/view/v059i10)
  + [alternate link:](http://vita.had.co.nz/papers/tidy-data.html)
  + [informal and code-heavy version](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html)
 
* Hadley Wickham
  + [Tidy data and tidy tools (video of presentation, December 2011)](https://vimeo.com/33727555)

* Garrett Grolemund
  + [Data Tidying](http://garrettgman.github.io/tidying/) (part of [Data Science with R](http://garrettgman.github.io/))


## Tidy Text

If  you're going to undertake text mining and natural language processing, your text (i.e. your data) needs to be tidy.  Fortunately, there's an R package for that: `tidytext`.

* Julia Silge, [Term Frequency and tf-idf Using Tidy Data Principles](http://juliasilge.com/blog/Term-Frequency-tf-idf/), 2016-06-27
