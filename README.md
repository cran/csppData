
<!-- README.md is generated from README.Rmd. Please edit that file -->

# csppData: The Correlates of State Policy Project Dataset <img src="figures/csppData.png" height="150" align="right"/>

<!-- badges: start -->

[![](https://www.r-pkg.org/badges/version/csppData?color=blue)](https://cran.r-project.org/package=csppData)
[![](http://cranlogs.r-pkg.org/badges/grand-total/csppData?color=blue)](https://cran.r-project.org/package=csppData)
<!-- badges: end -->

**csppData** is an R package that contains the Correlates of State
Policy data (version 2.5) assembled by Matt Grossmann, Marty P. Jordan,
and Josh McCrain. Use the associated
[cspp](https://github.com/correlatesstatepolicy/cspp) package to subset
the data by states and years, create map + panel visualizations, export
citations to common file formats (e.g., .bib), and more. An associated
[web application](https://cspp.ippsr.msu.edu/cspp/) that enables easy
visualization, manipulation, and exploration of the data is also
available.

## The Correlates of State Policy

[The Correlates of State Policy
Project](http://ippsr.msu.edu/public-policy/correlates-state-policy)
compiles more than 3,000 variables across 50 states (+ DC) from
1900-2020. The variables cover 16 broad categories:

-   Demographics and Population
-   Economic and Fiscal Policy
-   Government
-   Elections
-   Policy Scores and Public Opinion
-   Criminal Justice and the Legal System
-   Education
-   Healthcare and Health Insurance
-   Welfare Policy
-   Rights and Anti-Discrimination Protections
-   Environment
-   Drug and Alcohol Policy
-   Gun Control
-   Labor
-   Transportation
-   Regulatory Policy

## Downloading the Package

``` r
# Install from CRAN:
install.packages("csppData")

# Install from github (may contain more recent version than the CRAN package)
library(devtools)
install_github("correlatesstatepolicy/csppData")
```

## Loading the CSPP Data

Note that the `cspp` package imports the dataset automatically and
provides a number of helpful functions when working with it.

``` r
# CSPP codebook
data("codebook")

# CSPP data
data("correlates")
```

# Citation

CSPP Data

> Grossmann, M., Jordan, M. P. and McCrain, J. (2021) “The Correlates of
> State Policy and the Structure of State Panel Data,” State Politics &
> Policy Quarterly. Cambridge University Press, pp. 1-21. doi:
> 10.1017/spq.2021.17.

Package

> Caleb Lucas and Joshua McCrain (2020). csppData: The Correlates of
> State Policy Project Dataset. R package version 0.1.4

# Contact

[**Caleb Lucas**](https://caleblucas.com/) - Postdoc, IPPSR, Michigan
State University ([Twitter](https://twitter.com/caleblucas)) <br />
[**Josh McCrain**](http://joshuamccrain.com) - Assistant Professor,
University of Utah ([Twitter](https://twitter.com/joshmccrain))
