# Anonymity and Confidentiality

### Introduction

Many data that are ripe for analysis are covered under some form of legal, ethical, and moral privacy and confidentiality constraints. How do we as researchers ensure that the data we work with--whether it's in aggregated form or released as a micro (individual) record that is stripped of personal identifiers such as name--remains anonymous?


Some definitions: ["What is the difference between "de-identified", "anonymous", and "coded" data?"](https://kb.wisc.edu/hsirbs/page.php?id=25351)

---
### Theory and methods

Statistics Canada, 2011: [A New Approach for the Development of a Public Use Microdata File for Canada's 2011 National Household Survey](https://www12.statcan.gc.ca/nhs-enm/2011/ref/pumf-fmgd/index-eng.cfm), Catalogue no. 99-137-XWE2015001.

[Wikipedia: Data anonymization](https://en.wikipedia.org/wiki/Data_anonymization)

#### k-anonymity

["wikipedia: _k_-anonymity"](https://en.wikipedia.org/wiki/K-anonymity)

Latanya Sweeney, ["k-Anonymity: A Model for Protecting Privacy"](http://dataprivacylab.org/dataprivacy/projects/kanonymity/kanonymity.pdf), International Journal on Uncertainty,
Fuzziness and Knowledge-based Systems, 10 (5), 2002; 557-570. 2002

Arvind Narayanan and Vitaly Shmatikov, ["Robust De-anonymization of Large Sparse Datasets"](https://www.cs.utexas.edu/~shmat/shmat_oak08netflix.pdf) 

Roberto J. Bayardo and Rakesh Agrawal, ["Data Privacy Through Optimal k-Anonymization"](http://www.bayardo.org/ps/icde05.pdf)

Khaled El Emam and Fida Kamal Dankar, ["Protecting Privacy Using k-Anonymity"](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2528029/), J Am Med Inform Assoc. 2008 Sep-Oct; 15(5): 627–637.


#### Discussion

Benjamin Bengfort, ["A Practical Guide to Anonymizing Datasets with Python & Faker: How Not to Lose Friends and Alienate People"](http://blog.districtdatalabs.com/a-practical-guide-to-anonymizing-datasets-with-python-faker), 2016

Justin Brickell and Vitaly Shmatikov, "The Cost of Privacy: Destruction of Data-Mining Utility in Anonymized Data Publishing"

Dary Hsu, ["Techniques to Anonymize Human Data"](http://blog.datasift.com/2015/04/09/techniques-to-anonymize-human-data/), 2015

Bruce Schneier, ["Why 'Anonymous' Data Sometimes Isn't"](http://archive.wired.com/politics/security/commentary/securitymatters/2007/12/securitymatters_1213)

#### But anonymized data can be re-identified:

[Wikipedia: De-anonymization](https://en.wikipedia.org/wiki/De-anonymization)

Children’s Hospital of Eastern Ontario Research Institute, 2007: [Pan-Canadian De-Identification Guidelines for Personal Health Information](https://www.priv.gc.ca/resource/cp/2006-2007/p_200607_04_e.asp)

* [Full report](http://www.ehealthinformation.ca/wp-content/uploads/2014/07/2007-Pan-Canadian-De-Identification-Guidelines.pdf)

Pete Warden, ["Why you can't really anonymize your data"](https://www.oreilly.com/ideas/anonymize-data-limits), 2011


---

---
### R

#### `sdcMicro`

**package**

CRAN page: [sdcMicro: Statistical Disclosure Control Methods for Anonymization of Microdata and Risk Estimation](https://cran.r-project.org/web/packages/sdcMicro/index.html)

**articles**

[Statistical Disclosure Control (SDCMicro)](http://www.ihsn.org/home/software/disclosure-control-toolbox) at International Household Survey Network.

Matthias Templ, Bernhard Meindl and Alexander Kowarik, [Introduction to Statistical Disclosure Control (SDC)](https://cran.r-project.org/web/packages/sdcMicro/vignettes/sdc_guidelines.pdf), 2015

Alexander Kowarik and Matthias Templ, ["Make Your Data Confidential with the sdcMicro and sdcMicroGUI packages"](https://www.researchgate.net/publication/261507879_Make_Your_Data_Confidential_with_the_sdcMicro_and_sdcMicroGUI_packages), 2012

#### `sdcMicroGUI`

**package**

CRAN page: [sdcMicroGUI: Graphical User Interface for Package 'sdcMicro'](https://cran.r-project.org/web/packages/sdcMicroGUI/index.html)

**articles**

Matthias Templ, Bernhard Meindl and Alexander Kowarik, [Tutorial for sdcMicroGUI (and sdcMicro)](https://cran.r-project.org/web/packages/sdcMicroGUI/vignettes/gui_tutorial.pdf), 2015



