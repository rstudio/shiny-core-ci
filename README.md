<!-- README.md is generated from README.Rmd. Please edit that file -->

# shinycoreci

<!-- badges: start -->

[![R CMD check](https://github.com/rstudio/shinycoreci/workflows/R-CMD-check/badge.svg)](https://github.com/rstudio/shinycoreci/actions?query=workflow%3AR-CMD-check)
[![shinytest](https://github.com/rstudio/shinycoreci-apps/workflows/shinytest/badge.svg?branch=master)](https://github.com/rstudio/shinycoreci-apps/actions?query=workflow%3Ashinytest)
[![shinyjster](https://github.com/rstudio/shinycoreci-apps/workflows/shinyjster/badge.svg?branch=master)](https://github.com/rstudio/shinycoreci-apps/actions?query=workflow%3Ashinyjster)
[![testthat](https://github.com/rstudio/shinycoreci-apps/workflows/testthat/badge.svg?branch=master)](https://github.com/rstudio/shinycoreci-apps/actions?query=workflow%3Atestthat)
<!-- badges: end -->

This is an R package to install all dependencies to test the bleeding edge of all relevant packages to the Shiny team.

For more direct usage examples, see [`rstudio/shinycoreci-apps`](https://github.com/rstudio/shinycoreci-apps).

## Installation

Install the development version from [GitHub](https://github.com/) with:

``` r
remotes::install_github("rstudio/shinycoreci")
```

These `Remotes` will be installed to make sure the latest package development is working as expected:

  - [r-lib/fastmap](http://github.com/r-lib/fastmap)
  - [r-lib/later](http://github.com/r-lib/later)
  - [ramnathv/htmlwidgets](http://github.com/ramnathv/htmlwidgets)
  - [ropensci/plotly](http://github.com/ropensci/plotly)
  - [rstudio/crosstalk](http://github.com/rstudio/crosstalk)
  - [rstudio/flexdashboard](http://github.com/rstudio/flexdashboard)
  - [rstudio/htmltools](http://github.com/rstudio/htmltools)
  - [rstudio/httpuv](http://github.com/rstudio/httpuv)
  - [rstudio/leaflet](http://github.com/rstudio/leaflet)
  - [rstudio/leaflet.providers](http://github.com/rstudio/leaflet.providers)
  - [rstudio/pool](http://github.com/rstudio/pool)
  - [rstudio/promises](http://github.com/rstudio/promises)
  - [rstudio/reactlog](http://github.com/rstudio/reactlog)
  - [rstudio/shiny](http://github.com/rstudio/shiny)
  - [rstudio/shinymeta](http://github.com/rstudio/shinymeta)
  - [rstudio/shinytest](http://github.com/rstudio/shinytest)
  - [rstudio/websocket](http://github.com/rstudio/websocket)
  - [schloerke/shinyjster](http://github.com/schloerke/shinyjster)
