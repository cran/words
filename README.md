
<!-- README.md is generated from README.Rmd. Please edit that file -->

# words

<!-- badges: start -->
<!-- badges: end -->

The goal of words is to provide a list of english words certified for
use in Scrabble.

## Installation

You can install the released version of words from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("words")
```

or the development version from Github with

``` r
devtools::install_github("condwanaland/words")
```

## Example

`words` contains a single dataframe that can be loaded with `data`.

``` r
library(words)
data("words")
head(words)
#>   word word_length
#> 1   aa           2
#> 2   ab           2
#> 3   ad           2
#> 4   ae           2
#> 5   ag           2
#> 6   ah           2
```
