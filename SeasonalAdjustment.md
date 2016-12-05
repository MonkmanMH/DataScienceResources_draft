# Seasonal Adjustment

### Introduction

From the wikipedia entry:

>Seasonal adjustment is a statistical method for removing the seasonal component of a time series that exhibits a seasonal pattern. It is usually done when wanting to analyse the trend of a time series independently of the seasonal components. It is normal to report seasonally adjusted data for unemployment rates to reveal the underlying trends in labor markets. Many economic phenomena have seasonal cycles, such as agricultural production and consumer consumption, e.g. greater consumption leading up to Christmas. It is necessary to adjust for this component in order to understand what underlying trends are in the economy and so official statistics are often adjusted to remove seasonal components.

[Seasonal adjustment: wikipedia entry](https://en.wikipedia.org/wiki/Seasonal_adjustment), 2016-05-07


Statistics Canada, ["Seasonal adjustment and trend-cycle estimation"](http://www.statcan.gc.ca/pub/12-539-x/2009001/seasonal-saisonnal-eng.htm)  (part of Statistics Canada [Quality Guidelines](http://www.statcan.gc.ca/pub/12-539-x/12-539-x2009001-eng.htm), Catalogue 12-539-X)


---
### R

#### `ggsdc`

**package**

CRAN page: [ggseas: 'stats' for Seasonal Adjustment on the Fly with 'ggplot2'](https://cran.r-project.org/web/packages/ggseas/index.html)

[Vignette](https://cran.r-project.org/web/packages/ggseas/vignettes/ggsdc.html)


#### `ggseas`

**package**

CRAN page: [ggseas: 'stats' for Seasonal Adjustment on the Fly with 'ggplot2'](https://cran.r-project.org/web/packages/ggseas/)

[Vignette](https://cran.r-project.org/web/packages/ggseas/vignettes/ggsdc.html)

**articles**

Ellis, Peter. 2016-10-12. ["Update of `ggseas` for seasonal decomposition on the fly"](http://ellisp.github.io/blog/2016/10/12/ggsdc-rents), blog entry

Ellis, Peter. 2016-03-28. ["Seasonal decomposition in the ggplot2 universe with ggseas"](http://ellisp.github.io/blog/2016/03/28/ggseas-update/), blog entry.

Ellis, Peter. 2016-02-08. ["ggseas package for seasonal adjustment on the fly with ggplot2"](http://ellisp.github.io/blog/2016/02/08/ggseas/), blog entry.


#### `seasonal`

**[seasonal: R-interface to X-13ARIMA-SEATS](http://www.seasonal.website/seasonal.html)**

"...the best interface on the planet to the X13-SEATS-ARIMA time series analysis application from the US Census Department, which is the industry standard particularly for official statistics agencies doing seasonal adjustment." (Peter Ellis, [vignette for `ggsdc`](https://cran.r-project.org/web/packages/ggseas/vignettes/ggsdc.html.))

**package**

CRAN page: [seasonal: R Interface to X-13-ARIMA-SEATS'](https://cran.r-project.org/web/packages/seasonal/index.html)

github page: [christophsax/seasonal](https://github.com/christophsax/seasonal)


#### `x13binary`

(US Census Bureau X-13, packaged for easy loading. Loads as a dependency for most of the other seasonal adjustment packages.)

**package**

CRAN page: [x13binary: Provide the 'x13ashtml' Seasonal Adjustment Binary](https://cran.r-project.org/web/packages/x13binary/index.html)





