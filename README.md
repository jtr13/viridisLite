# viridisLite - Colorblind-Friendly Color Maps for R <img src="man/figures/logo.png" align="right" alt="" width="120" />

<!-- badges: start -->
[![DOI](https://zenodo.org/badge/44360137.svg)](https://zenodo.org/badge/latestdoi/44360137)
[![R-CMD-check](https://github.com/sjmgarnier/viridisLite/workflows/R-CMD-check/badge.svg)](https://github.com/sjmgarnier/viridisLite/actions)
[![Codecov test coverage](https://codecov.io/gh/sjmgarnier/viridisLite/branch/master/graph/badge.svg)](https://app.codecov.io/gh/sjmgarnier/viridisLite?branch=master)
[![cran version](http://www.r-pkg.org/badges/version/viridisLite)](https://cran.r-project.org/package=viridisLite)
[![rstudio mirror per-month downloads](http://cranlogs.r-pkg.org/badges/viridisLite)](https://github.com/metacran/cranlogs.app)
[![rstudio mirror total downloads](http://cranlogs.r-pkg.org/badges/grand-total/viridisLite?color=yellowgreen)](https://github.com/metacran/cranlogs.app)
<!-- badges: end -->

## Description

`viridisLite`, and its companion package [`viridis`](https://cran.r-project.org/package=viridis) 
provide a series of color maps that are designed to improve graph readability 
for readers with common forms of color blindness and/or color vision deficiency. 
The color maps are also perceptually-uniform, both in regular form and also when 
converted to black-and-white for printing. 

`viridisLite` provides the base functions for generating the color maps in base 
`R`. The package is meant to be as lightweight and dependency-free as possible 
for maximum compatibility with all the `R` ecosystem. [`viridis`](https://cran.r-project.org/package=viridis)
provides additional functionalities, in particular bindings for `ggplot2`.

---

## The color maps

The latest version of `viridisLite` comes with 8 different color maps, and they 
are all very pretty!!!

![Sample image](man/figures/maps.png)

---

## Installation

You can install `viridisLite` from `CRAN` by typing the following line in your R 
console:

```{r}
install.packages("viridisLite")
library(viridisLite)
```

If you prefer to install the development version from this GitHub repository,
simply copy the following lines of code in your R terminal and it should install 
everything you need to use `viridisLite` on your computer: 

```{r}
if (!require("devtools")) 
  install.packages("devtools")

devtools::install_github("sjmgarnier/viridisLite")
library(viridisLite)
```

---


