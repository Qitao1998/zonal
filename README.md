
<!-- README.md is generated from README.Rmd. Please edit that file -->

# zonal

<!-- badges: start -->

[![R CMD
Check](https://github.com/mikejohnson51/zonal/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/mikejohnson51/zonal/actions/workflows/R-CMD-check.yaml)
[![Project Status:
Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
<!-- badges: end -->

`zonal` is an active package for intersecting vector aggregation units
with large gridded data. While there are many libraries that seek to
tackle this problem (see credits) we needed a library that could handle
large gridded extents with multiple time layers with both many small
vector units and few large units.

We also seek to segment the creation of grid weights from the zonal
execution so that the same weight map can be applied across different
products with the same structure (e.g. MODIS ET and MODIS LAI)

## Installation

You can install the development version of `zonal` from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("mikejohnson51/zonal")
```

## Example

This is a basic example:

``` r
library(zonal)
## basic example code
```

------------------------------------------------------------------------

## Getting involved

1.  Code style should attempt to follow the tidyverse style guide.
2.  Please avoid adding significant new dependencies without a
    documented reason why.
3.  Please attempt to describe what you want to do prior to contributing
    by submitting an issue.
4.  Please follow the typical github fork - pull-request workflow.
5.  Make sure you use roxygen and run Check before contributing.

------------------------------------------------------------------------

## Open source licensing info

1.  [TERMS](TERMS.md)
2.  [LICENSE](LICENSE)

------------------------------------------------------------------------

## Credits and references

Similar R packages: 1.
[exactexactr](https://github.com/isciences/exactextractr) 2.
[intersectr](https://github.com/USGS-R/intersectr) 3.
[areal](https://github.com/slu-openGIS/areal) 4.
[sf](https://github.com/r-spatial/sf) 5.
[raster](https://github.com/rspatial/raster)
