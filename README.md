
<!-- README.md is generated from README.Rmd. Please edit that file -->

<!-- badges: start -->

![Lifecycle:stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)

![Travis-CI:
build-status](https://travis-ci.com/saiemgilani/cfbscrapR.svg?token=BxsozfUD3VCvCzzJpdFf&branch=master)
<!-- badges: end -->

# cfbscrapR

A scraping and aggregating package using the CollegeFootballData API

<a href="https://imgur.com/jBcXRgw"><img src="https://i.imgur.com/jBcXRgw.png" title="Figure: @SaiemGilani" /></a>

`cfbscrapR` is an R package for working with CFB data. It is an R API
wrapper around <https://collegefootballdata.com/>. It provides users the
capability to retrieve data from a plethora of endpoints and supplement
that data with additional information (Expected Points Added/Win
Probability added).

**Note:** The API ingests data from ESPN as well as other sources. For
details on those source, please go the website linked above. Sometimes
there are inconsistencies in the underlying data itself. Please report
issues here or to <https://collegefootballdata.com/>.

## Installation

You can install `cfbscrapR` from
[GitHub](https://github.com/saiemgilani/cfbscrapR) with:

``` r
# install.packages("devtools")
devtools::install_github("meysubb/cfbscrapR")
```

For more information on the package and models, please see the
`cfbscrapR` [documentation](https://saiemgilani.github.io/cfbscrapR/).
