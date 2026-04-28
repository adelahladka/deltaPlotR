---
editor_options: 
  markdown: 
    wrap: 72
---

# deltaPlotR

Identification of Dichotomous Differential Item Functioning (DIF) using Angoff's 
Delta Plot Method

[![CRAN
version](https://www.r-pkg.org/badges/version/deltaPlotR?color=#F0E442)](https://cran.r-project.org/package=deltaPlotR)
[![CRAN
downloads](https://cranlogs.r-pkg.org/badges/deltaPlotR)](https://cran.r-project.org/package=badger)
[![Last
commit](https://img.shields.io/github/last-commit/adelahladka/deltaPlotR.svg)](https://github.com/adelahladka/deltaPlotR/commits/master)

## Description

Angoff's Delta plot (Angoff & Ford, 1973) is a straightforward
test-score method to detect differential item functioning (DIF) among
dichotomously scored items based on proportions of correct responses.
The **deltaPlotR** package provides this method via the `deltaPlot()` function 
and visualisation of the results using the `diagPlot()` function. 

## Installation

The easiest way to get **deltaPlotR** package is to install it from CRAN:

```         
install.packages("deltaPlotR")
```

Or you can get the newest development version from GitHub:

```         
# install.packages("devtools")
devtools::install_github("adelahladka/deltaPlotR")
```

## Version

Current version on [**CRAN**](https://CRAN.R-project.org/package=deltaPlotR)
is 1.9. The newest development version available on
[**GitHub**](https://github.com/adelahladka/deltaPlotR) is 1.9.

## Reference

To cite the **deltaPlotR** package in publications, please, use:

<ul>Magis, D. & Facon, B. (2014). deltaPlotR: An R Package for differential item 
functioning analysis with Angoff's delta plot 
<i>Journal of Statistical Software, Code Snippets, 59</i>(1), 1--19, 
<https://doi.org/10.18637/jss.v059.c01></ul>

Further related publications on Angoff's delta plot method:

<ul>Angoff, W. H. & Ford, S. F. (1973). Item-race interaction on a test of 
scholastic aptitude. 
<i>Journal of Educational Measurement, 10</i>(2), 95--106, 
<https://doi.org/10.1111/j.1745-3984.1973.tb00787.x></ul>

<ul>Magis, D. & Facon, B. (2012). Angoff's Delta method revisited: improving the 
DIF detection under small samples. 
<i>British Journal of Mathematical and Statistical Psychology, 65</i>(2), 302--321, 
<https://doi.org/10.1111/j.2044-8317.2011.02025.x></ul>


## Try online

You can try some functionalities of the **deltaPlotR** package
[online](https://shiny.cs.cas.cz/ShinyItemAnalysis/) using the
[**ShinyItemAnalysis**](https://github.com/patriciamar/ShinyItemAnalysis)
application and package and its DIF/Fairness section.

## Getting help

In case you find any bug or just need help with the **deltaPlotR** package,
you can leave your message as an issue here or directly contact us at
[hladka\@cs.cas.cz](mailto:hladka@cs.cas.cz){.email}
