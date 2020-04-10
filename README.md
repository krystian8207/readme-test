R Notebook
================

Tests of semantic Rmd.

``` r
library(shiny)
library(shiny.semantic)
```

``` r
shiny.semantic::uirender(
  shiny::actionButton("a", "This is button", icon("car"))
)
```

![](docs_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

``` r
shiny.semantic::uirender(
  shiny.semantic::uibutton("a", "This is button", icon("car"))
)
```

![](docs_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->
