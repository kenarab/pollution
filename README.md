# pollution

 <!-- A Package for interactive visualizing pollution information on a 3D model of the earth . -->

 

| Release | Usage | Development |
|:--------|:------|:------------|
| | [![minimal R version](https://img.shields.io/badge/R%3E%3D-3.4.0-blue.svg)](https://cran.r-project.org/) | [![Travis](https://travis-ci.org/kenarab/pollution.svg?branch=master)](https://travis-ci.org/kenarab/pollution) |
| [![CRAN](http://www.r-pkg.org/badges/version/pollution)](https://cran.r-project.org/package=pollution) | | [![codecov](https://codecov.io/gh/kenarab/pollution/branch/master/graph/badge.svg)](https://codecov.io/gh/kenarab/pollution) |
|||[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)|

# How to get started (NOT in CRAN yet!)
```R
install.packages("pollution")
```

# How to get started (Development version)

Install the R package using the following commands on the R console:

```R
devtools::install_github("kenarab/pollution", build_opts = NULL)
library(pollution)
```

# First example


```R
library(pollution)
showWebglobeQuakes()
```R

