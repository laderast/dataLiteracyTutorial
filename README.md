
<!-- README.md is generated from README.Rmd. Please edit that file -->
dataLiteracyTutorial
====================

The goal of dataLiteracyTutorial is to provide a basic tutorial showing how to understand visualizations in a non-technical and exploratory fashion. Shiny visualizations help students to explore various visualization concepts and understand how data is represented in visualizations.

dataLiteracyTutorial is implemented as a [LearnR package](https://rstudio.github.io/learnr/). It can be set up on a Shiny server such as shinyapps.io or can be installed and run on a computer with the instructions below.

Installation
------------

You can install the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("laderast/dataLiteracyTutorial")
```

You can then run the tutorial with

``` r
learnr::run_tutorial("dataLiteracyTutorial", package = "dataLiteracyTutorial")
```

Acknowledgements
----------------

Portions of this tutorial were adapted from Mikhail Popov's excellent data literacy workshop from Wikipedia: <https://github.com/bearloga/wmf-allhands18> and a previous LearnR tutorial called `DSIexplore` that Jessica Minnier and I did: <https://github.com/laderast/dsiexplore>
