<!-- badges: start -->
[![CircleCI build status](https://circleci.com/gh/JohnCoene/coronavirus.svg?style=svg)](https://circleci.com/gh/JohnCoene/coronavirus)
[![Travis build status](https://travis-ci.org/JohnCoene/coronavirus.svg?branch=master)](https://travis-ci.org/JohnCoene/coronavirus)
[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/JohnCoene/coronavirus?branch=master&svg=true)](https://ci.appveyor.com/project/JohnCoene/coronavirus)
![](https://img.shields.io/badge/license-MIT-blue)
[![Lifecycle: maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
<!-- badges: end -->

Dashboard to track the spread of the coronavirus, based on three data sources, built with [shinyMobile](https://rinterface.github.io/shinyMobile/) and [echarts4r](https://echarts4r.john-coene.com/). I have [blog post](https://blog.john-coene.com/posts/2020-02-08-ncov-2019/) detailing the reason behind this project and some technical details of the application.

![](_media/banner.png)

## Get it

You can view the [dashboard](https://shiny.john-coene.com/coronavirus) online or download the package to run it locally or deploy it.

``` r
install.packages("remotes")
remotes::install_github("JohnCoene/coronavirus")
```

## Credits

- UI: [shinyMobile](https://github.com/RinteRface/shinyMobile) framework
- Data: [John Hopkins](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6), the [nCov2019](https://github.com/GuangchuangYu/nCov2019) package by Guangchuang Yu, and [DingXiangYing](https://ncov.dxy.cn/ncovh5/view/pneumonia)
- Visualisations: [echarts4r](https://echarts4r.john-coene.com)

## Contribute

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By contributing to this project, you agree to abide by its terms.
