# Hello


The `hello` package contains functionality for generating greetings.

## Installation

To install `hello`, install the `devtools` package and run the following
command in the R terminal:

``` r
devtools::install_github('BIFX545-25/hello')
```

## Examples

The main function in this package is `hello`. Here are a few examples of
how to use it.

``` r
library(hello)

hello('BIFX 545 students')
```

    [1] "Hello BIFX 545 students!"

``` r
hello('Dr Johnson')
```

    [1] "Hello Dr Johnson!"
