
<!-- README.md is generated from README.Rmd. Please edit that file -->
RavenR
======

RavenR is an R package for handling Raven hydrologic modelling framework inputs, outputs, and diagnostics. Please contact Robert Chlumsky (<rchlumsk@uwaterloo.ca>) for any troubleshooting, bug fixes, or recommendations on future releases.

This is a forked version by Joel Trubilowicz, contacted at (<jwtrubil@gmail.com>)

Installation
------------

You can install RavenR from github with:

``` r
# install.packages("devtools")
# library(devtools)
#for this forked version:
devtools::install_github("jwtrubil/RavenR")

#for real version:
devtools::install_github("rchlumsk/RavenR")
```

Tutorials and Quick Start Guide
-------------------------------

Please see the vignettes or pdf folder for RavenR Tutorials and Quick Start Guides. Sample data is included in the package, so you need only to install the RavenR library and follow along in the guide documents to get started.

\*\*Note that as of v1.2, the vignettes are out of date and will be updated in the next update.

RavenR Wishlist
---------------

Any issues or feature requests can be submitted on Github via the Issues tab. You may also submit feature requests directly to Robert Chlumsky (<rchlumsk@uwaterloo.ca>) via email.

Dependency Installs
-------------------

Note that some of the package dependencies may require the installation of programs outside of R, particularly for Linux users. Refer to specific function helps on how to install various package materials, such as [ImageMagick](https://www.imagemagick.org/script/download.php).

Version Update Notes
--------------------

### 1.2

*Currently in Beta mode for v1.2, please test and submit comments to <rchlumsk@uwaterloo.ca>*

Updated functionality and test data sets for use. New functions include: \* subbasin and HRU plotting from shapefile from custom data or tabular input \* animation of subbasin plots for custom data \* watershed network plotting from HRU file \* RVH file handling \* time series infilling \* creation of observation rvt files

New sample data sets, including raw data for testing read-type functions.

Updated examples for each function and improved documentation.
