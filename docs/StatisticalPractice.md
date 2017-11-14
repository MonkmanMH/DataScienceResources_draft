# Statistical & Data Science Practice

First, an excellent list of data science resources:

* [Practical Data Science for Stats - a PeerJ Collection](https://peerj.com/collections/50-practicaldatascistats/)


### Introduction

How does one approach a statistics or data science project?

#### The function of data science: solving business problems

Emily Robinson, 2017-09-27, [Managing Business Challenges In Data Science](https://robinsones.github.io/Managing-Business-Challenges-in-Data-Science/)


#### Opinionated Analysis Development

An over-arching structure of what a project could (or should?) look like can be boiled down into three features: it is

1. Reproducible and auditable

2. Accurate

3. Collaborative


* Hilary Parker, 2017-08-30, [Opinionated Analysis Development](https://peerj.com/preprints/3210/)

  - some of Hilary Parker's earlier / supporting thoughts on this topic can be found in [her talk "Opinionated Analysis Development" from rstudio::conf2017 (2017-01-14)](https://www.rstudio.com/resources/videos/opinionated-analysis-development/) ([slides alone at slideshare](https://www.slideshare.net/hilaryparker/opinionated-analysis-development)), as well as the slides from her [keynote at EARL SF (2017-06-15)](https://www.slideshare.net/hilaryparker/opinionated-analysis-development-earl-sf-keynote)



#### General practice and workflow

* Kass RE, Caffo BS, Davidian M, Meng X-L, Yu B, Reid N (2016) ["Ten Simple Rules for Effective Statistical Practice"](http://journals.plos.org/ploscompbiol/article?id=10.1371%2Fjournal.pcbi.1004961). PLoS Comput Biol 12(6): e1004961. doi:10.1371/journal.pcbi.1004961

* Ray Li (2016) ["7 habits of highly effective data analysis"](http://dataconomy.com/2016/02/7-habits-of-highly-effective-data-analysis/). [Dataconomy.com](Dataconomy.com), 2016-02-16.

* Wilson G, Bryan J, Cranston K, Kitzes J, Nederbragt L, Teal TK (2017) Good enough practices in scientific computing. PLoS Comput Biol 13(6): e1005510. https://doi.org/10.1371/journal.pcbi.1005510

  - Jenny Bryan (2017) [Workflow: you should have one](https://speakerdeck.com/jennybc/workflow-you-should-have-one), Keynote talk at EARL London 2017.  [Supporting documentation: earl-london-2017-bryan](https://github.com/jennybc/earl-london-2017-bryan#readme)


* Gabe Becker (2017) [Enhancing reproducibility, comparability and discoverability of results in multi-analyst settings](https://www.slideshare.net/GabrielBecker11/enhancing-reproducibility-comparability-and-discoverability-of-results-in-multianalyst-settings), presentation at EARL (Enterprise Applications of R Language), San Francisco, June 5-7, 2017

  -- this came to my attention via the Not So Standard Deviations podcast, [episode 40 "It's the CDs All Over Again"](https://www.patreon.com/posts/episode-40-its-11713845) (2017-06-13). The discussion of Gabe Becker's presentation begins at ~13' 10".
  
  - some of Hilary Parker's observations: the topic doesn't get much air time, his talk takes wide view of issues in an organization, trade-offs in collaborative environment (not one analyst); in multi-analyst system (e.g. where both a researcher/biologist and a statistician are both working with the same data) have to reconcile results, there might be parallel studies where results need to be reconciled, >> this creates a need for the data to be created in similar environments. 
  
  - Concerns: reproducibity, comparability,  discoverability (finding the results), and empowerment. Data scientists skew to emppowerment!  But the concerns are in tension--you can increase reproducibility but at cost of empowerment, etc.
  
  - "Most organizations aren't making that judgement call ahead of time...any organization ... if data scientists were there early, you're going to be skewed to agility and high empowerment. Because that's like what we want! ... Data scientists are allergic to process...having any template for results, or ... even having to put things into a specific tool."
  
  - Different systems need different constraints.
  
  - Roger Peng: most organizations don't realize that they are explicitly making these trade-offs, can't maximize all. Have to make a choice, and that's very unsatisfactory for people.



---

### Data Informed or Data Driven?

Ricardo Bion, Robert Chang, and Jason Goodman (2017-08-23) [How R Helps Airbnb Make the Most of Its Data](https://peerj.com/preprints/3182.pdf)

[The Stitch Fix Algorithms Tour](http://algorithms-tour.stitchfix.com/)


---

### Agile practice

[Agile Scrum Guide](http://agile-guide.pathfinder.bcgov/), BC Government DevEx

---

### Data Quality

Jacob Harris (2014) (["Distrust your data"](https://source.opennews.org/en-US/learning/distrust-your-data/), 2014-05-24.

---

### File storage and naming conventions

* [Sustainability of Digital Formats: Planning for Library of Congress Collections](http://www.digitalpreservation.gov/formats/index.shtml)

* Jenny Bryan, [naming things](http://www2.stat.duke.edu/~rcs46/lectures_2015/01-markdown-git/slides/naming-slides/naming-slides.pdf),
Reproducible Science Workshop, 2015


---

### Reproducible research


* [reproducibleresearch.net](http://reproducibleresearch.net/)

* Roger Peng (2014-06-06) [The Real Reason Reproducible Research is Important](https://simplystatistics.org/2014/06/06/the-real-reason-reproducible-research-is-important/)

* Roger Peng, 2015-06-15, ["The reproducibility crisis in science: A statistical counterattack"](http://onlinelibrary.wiley.com/doi/10.1111/j.1740-9713.2015.00827.x/full), [_Significance_](http://rss.onlinelibrary.wiley.com/hub/journal/10.1111/(ISSN)1740-9713/)

* Rich FitzJohn, Matt Pennell, Amy Zanne, Will Cornwell (2014-06-09) [Reproducible research is still a challenge](https://ropensci.org/blog/2014/06/09/reproducibility/) (at [rOpenSci](https://ropensci.org/))


#### Reproducible research with R

* Jeremy Anglin, [Reproducible analysis with knitr, R Markdown, and RStudio](https://github.com/jeromyanglim/rmarkdown-rmeetup-2012)
 
* Ben Marwick, 20 July 2017, [Reproducible Research Compendia via R packages](https://rawgit.com/benmarwick/Marwick-Berlin-R-users-2017/master/Marwick-Berlin-R-users-2017.html#1), presentation at Berlin R Users



#### spreadsheets: the anti-reproducible research

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I read &quot;Data analysis without scripting&quot; as &quot;Dystopian moonscape of unrecorded user actions&quot;. I may not be Tableau&#39;s target market. <a href="https://twitter.com/hashtag/rstats?src=hash">#rstats</a></p>&mdash; Gordon Shotwell (@gshotwell) <a href="https://twitter.com/gshotwell/status/577485681146097664">March 16, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>


* Jenny Bryan's [spreadsheets](https://speakerdeck.com/jennybc/spreadsheets) talk given May & June 2016 reframes Shotwell as "Spreadsheets: a dystopian moonscape of unrecorded user actions."
  - live in-person (https://pbs.twimg.com/media/CmDykgRWAAE-_MP.jpg)
  
* Ignasi Bartomeus and F Rodriguez-Sanchez,  _Non-reproducible workflows: a horror movie_ :

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">That awesome video on reproducibility with <a href="https://twitter.com/hashtag/rstats?src=hash&amp;ref_src=twsrc%5Etfw">#rstats</a> by <a href="https://twitter.com/ibartomeus?ref_src=twsrc%5Etfw">@ibartomeus</a> and <a href="https://twitter.com/frod_san?ref_src=twsrc%5Etfw">@frod_san</a> you can find here: <a href="https://t.co/indBflvupv">https://t.co/indBflvupv</a> <a href="https://t.co/QcdonwVTk8">https://t.co/QcdonwVTk8</a></p>&mdash; David Smith (@revodavid) <a href="https://twitter.com/revodavid/status/917779772385656832?ref_src=twsrc%5Etfw">October 10, 2017</a></blockquote>

    - with more at [Reproducibilidad](http://ecoinfaeet.github.io/2016/07/06/reproducibilidad/)


* Gordon Shotwell, 2017-02-02, [R for Excel Users](http://blog.shotwell.ca/post/r_for_excel_users/)

* Luis A. Apiolaza, 2017-11-11, [Reducing friction in R to avoid Excel](http://www.quantumforest.com/2017/11/reducing-friction-to-avoid-excel/)



#### Versioned data

* Daniel Falster, Richard G FitzJohn, Matthew W. Pennell, William K. Cornwell (2017-11-10) [Versioned data: why it is needed and how it can be achieved (easily and cheaply)](https://peerj.com/preprints/3401/)


***

### Coding practice

Hadley Wickham, ["Style Guide"](http://adv-r.had.co.nz/Style.html) chapter from [_Advanced R_](http://adv-r.had.co.nz/)

[Coding etiquette](https://ourcodingclub.github.io/2017/04/25/etiquette.html), a guide to writing clear, informative and easy-to-use #RStats code by @CodingClub 


#### Literate programming

The practice of explaining the program logic in a natural language"; it goes beyond what might be called "documentation". In the world of R, the RMarkdown functionality within [RStudio](https://www.rstudio.com/products/rstudio/), including [R notebooks](http://rmarkdown.rstudio.com/r_notebooks.html), is a way to program in this manner.

The concept was introduced by Donald Knuth in 1984; the original article is
> Knuth, Donald E. (1984). ["Literate Programming"](http://www.literateprogramming.com/knuthweb.pdf) (PDF). _The Computer Journal_. British Computer Society. 27 (2): 97–111. 

* [literateprogramming.com](http://www.literateprogramming.com/)

* [Wikipedia entry](https://en.wikipedia.org/wiki/Literate_programming)


#### Functions in R

Colin Fay, [Playing with R, infix functions, and pizza ](http://colinfay.me/playing-r-infix-functions/)




#### Naming variables

"There are only two hard things in Computer Science: cache invalidation and naming things."
-- Phil Karlton

Andy Lester, ["The World's Two Worst Variable Names"](http://archive.oreilly.com/pub/post/the_worlds_two_worst_variable.html)


#### Clean coding 

Robert C. Martin, 2008, _Clean Code: A Handbook of Agile Software Development_, Prentice Hall.

Robert C. Martin, 2011, _The Clean Coder: A Code of Conduct for Professional Programmers_, Prentice Hall.


#### Further reading

Dani Marillas, 2017-01-25, ["Don’t document your code. Code your documentation."](https://dev.to/raddikx/dont-document-your-code-code-your-documentation)





-30-
