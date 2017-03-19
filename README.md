
<!-- README.md is generated from README.Rmd. Please edit that file -->
`stldata`
=========

The `stldata` package contains various datasets representing the City of St. Louis. These datasets are primary designed for teaching statistics, data science, and spatial data analysis using `R`.

### Install

Download and install latest release of `stldata` from CRAN:

``` r
install.packages("stldata")
```

or download the latest build with patches and test data from GitHub using the `devtools` package:

``` r
devtools::install_github("chris-prener/stldata")
```

### Current Data

The package currently contains two data tables:

-   `stlLead` - blood lead level test result datavi from 2010-2015 via [Reuters](http://www.reuters.com/investigates/special-report/usa-lead-testing/#interactive-lead) and 2015 5-year estimates for demographics (poverty and race) via the American Community Survey
-   `stlMurders` - all murders between 2008 and 2016 via the St. Louis Metropolitan Police Department

Opening data:

``` r
library("stldata")
lead <- stlLead
murders <- stlMurders
```

Additional examples are available in each table's help file:

``` r
?stlLead
```

### Future Data

I am currently working on a set of tables with educational outcomes by school for St. Louis City Public Schools.

If you have data about the City or the metro area that you would like to donate or variables you'd like to see added to a table, open up an issue on the package's [GitHub page](http://github.com/chris-prener/stldata/issues).
