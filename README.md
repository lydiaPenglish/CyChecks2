
<!-- README.md is generated from README.Rmd. Please edit that file -->

# CyChecks3 <img align="right" width="150" height="175" src="README_files/static-figures/hexsticker.png">

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

## FOIA anyone?

Iowa State University recently conducted an internal review of salaries
and possible discrepencies based on race and/or gender. The public is
not being offered access to the data nor the analyses, but rather a
[scant
summary](https://www.inside.iastate.edu/article/2020/11/12/facultysenate).
While the Freedom of Information Act (FOIA) probably covers this
information, requesting data is [not super
easy](https://www.foia.gov/how-to.html).

## Use what we’ve got

*Publicly available data*

The goal of CyChecks3 is to complement their findings using publicly
available data. Iowa state employee salaries are available at [this
site](https://data.iowa.gov/State-Finances/State-of-Iowa-Salary-Book/s3p7-wy6w).
You can access the data with or without an API token, but can sign up
for one [here](https://dev.socrata.com/foundry/data.iowa.gov/s3p7-wy6w).

This data only reports genders, and only does so in a binary fashion. We
therefore cannot analyze the data with respect to race.

*Less publicly available data*

Salaries are department specific, and without accounting for these
effects comparisons of salaries by gender could be misleading. We
received department affiliations from Human Resources, but this data is,
strangely, not public. Additionally, matching salary data names to
affiliation data names was troublesome on several accounts, and required
a fair amount of googling and hand edits. We have done what we think is
the best job we can for 2019 data.

*What you get*

This package contains:

1.  Raw salary data (**salaries**)
2.  Raw affiliation data (**affiliations**)
3.  An internally-created dataset with only tenure-track faculty data
    from 2019 (**professors**)

## Installation

You can install the developmental version CyChecks3 from
[github](https://github.com/vanichols/CyChecks3) with:

``` r
devtools::install_github("vanichols/CyChecks3")
```

## Examples

Shiny coming soon\!
