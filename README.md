<!-- badges: start -->
[![Travis build status](https://travis-ci.org/iferres/simurg.svg?branch=master)](https://travis-ci.org/iferres/simurg)
<!-- badges: end -->

# simurg: Simulate a Bacterial Pangenome in R

This R package is intended to produce simulated pangenomes using reference sequences as starting point (MRCA), and both Neutral and Infinitely Many Genes (IMG) models to produce changes along branches of a simulated coalescent tree.

## Installation

The simplest way of installing `simurg` is using `devtools` package:

```r
if (!require(devtools)) {
    install.packages('devtools')
    library(devtools)
}
 
install_github('iferres/simurg')
```

## Help

The main function of `simurg` is well documented. Once the package is loaded, please refer to:
```r
help('simpg')
```

## Vignettes

A [vignette](https://github.com/iferres/simurg/wiki) is also provided to learn more about this package. If you want to see it locally, you have to build it first when installing `simurg`:


```r
library(devtools)
install_github('iferres/simurg', build_vignettes = TRUE)
vignette('Simulate_a_bacterial_pangenome')
```
Also, visit the [Wiki](https://github.com/iferres/simurg/wiki) page to see the vignette example.

