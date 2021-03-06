
<!-- README.md is generated from README.Rmd. Please edit that file -->
dataLiteracyTutorial
====================

The goal of `dataLiteracyTutorial` is to provide a basic tutorial showing how to understand visualizations in a non-technical and interactive fashion. The interactive visualizations help students to explore various visualization concepts and understand how data is represented in visualizations.

`dataLiteracyTutorial` is implemented as a [LearnR package](https://rstudio.github.io/learnr/). It can be set up on a Shiny server such as shinyapps.io or can be installed and run on a computer with the instructions below.

View the actual tutorial here: <https://tladeras.shinyapps.io/dataLiteracyTutorial>

Installation
------------

You can install the development version from [GitHub](https://github.com/) with:

``` r
install.packages("devtools")
devtools::install_github("laderast/dataLiteracyTutorial")
```

You can then run the tutorial with

``` r
learnr::run_tutorial("dataLiteracy", package = "dataLiteracyTutorial")
```

Binder
------

To run the tutorial in a binder version of rstudio, click the following below:

https://mybinder.org/v2/gh/laderast/dataLiteracyTutorial/master?urlpath=shiny/dataLiteracy/

Make sure you allow the popup to see the tutorial!

Acknowledgements
----------------

Portions of this tutorial were adapted from Mikhail Popov's excellent data literacy workshop from Wikipedia: <https://github.com/bearloga/wmf-allhands18> and a previous LearnR tutorial called `DSIexplore` that Jessica Minnier and I did for the OHSU Data Science Institute: <https://github.com/laderast/dsiexplore>
