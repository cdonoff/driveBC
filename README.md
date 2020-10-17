
# driveBC

<!-- badges: start -->
<!-- badges: end -->

The Drive BC webpage is used extensively throughout the year as travellers plan routes to destinations throughout BC.  While the official webpage has an interactive map, it is quite slow and hard to customize.  Fortunately, the government supports the **Open511-DriveBC API** which allows members of the public to pull information and customize as desired.  

With this in mind, we created a driveBC API wrapper that takes inputs from the user in various functions and produces interactive maps that allow further exploration.  The description of these functions is below.

## Installation

You can install the released version of driveBC from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("driveBC")
```

## Example


``` r
library(driveBC)
query <- driveBC_map_route("Kelowna", "Summerland")
query$map
```

[![Build Status](https://travis-ci.com/chluchy/driveBC.svg?branch=master)](https://travis-ci.com/chluchy/driveBC)
