# `tidymodels`

[![Travis build status](https://travis-ci.org/tidymodels/tidymodels.svg?branch=master)](https://travis-ci.org/tidymodels/tidymodels)
[![Coverage status](https://codecov.io/gh/tidymodels/tidymodels/branch/master/graph/badge.svg)](https://codecov.io/github/tidymodels/tidymodels?branch=master)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/tidymodels)](http://cran.r-project.org/web/packages/tidymodels)
[![Downloads](http://cranlogs.r-pkg.org/badges/tidymodels)](http://cran.rstudio.com/package=tidymodels)
![](https://img.shields.io/badge/lifecycle-experimental-orange.svg)


`tidymodels` is a "meta-package" for modeling and statistical analysis that share the underlying design philosophy, grammar, and data structures of the tidyverse.

It includes a core set of packages that are loaded on startup:

* [`broom`](https://github.com/tidyverse/broom) takes the messy output of built-in functions in R, such as `lm`, `nls`, or `t.test`, and turns them into tidy data frames.

* [`dplyr`](http::/github.com/tidyverse/dplyr) contains a grammar for data manipulation. 

* [`ggplot2`](http::/github.com/tidyverse/ggplot2) implements a grammar of graphics. 

* [`purrr`](http::/github.com/tidyverse/purrr) is a functional programming toolkit.

* [`recipes`](https://tidymodels.github.io/recipes/) is a general data preprocessor with a modern interface. It can create model matrices that incorporate feature engineering, imputation, and other help tools.

* [`rsample`](https://tidymodels.github.io/rsample/) has infrastructure for _resampling_ data so that models can be assessed and empirically validated. 

* [`tibble`](http::/github.com/tidyverse/tibble) has a modern re-imagining of the data frame.
 
* [`yardstick`](https://tidymodels.github.io/yardstick/) contains tools for evaluating models (e.g. accuracy, RMSE, etc.)

There are a few modeling packages that are also installed along with `tidymodels` (but are not attached on startup): 

* [`infer`](http://infer.netlify.com/) is a modern approach to statistical inference.

* [`tidypredict`](http://tidypredict.netlify.com/) translates some model prediction equations to SQL for high-performance computing.

* [`tidyposterior`](https://tidymodels.github.io/tidyposterior/) can be used to compare models using resampling and Bayesian analysis.

* [`tidytext`](https://github.com/juliasilge/tidytext) contains tidy tools for quantitative text analysis, including basic text summarization, sentiment analysis, and text modeling.

To install:

```r
require(devtools)
devtools::install_github("tidymodels/tidymodels")
```

