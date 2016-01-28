This is the R script repository of the "[Tools for Analytics Lab - R-track](http://economics.ceu.edu/courses/1-tools-analytics-lab-r-track)" course, part of the [MSc in Business Analytics](http://business.ceu.edu/msc-in-business-analytics) at CEU.

### Jan 25 (90 min): Introduction to R and General Programming

* General overview of the R ecosystem: [slides](http://bit.ly/CEU-R-1)
* Introduction to R: [variables, functions and vectors](https://github.com/daroczig/CEU-R-lab/blob/master/1.R)

### Jan 26 (90 min): First Steps with Data Visualization

* Review of the most important R object types
* Quick overview of the missed `data.frame` examples from yesterday
* Exploratory data analysis with the most often used plots
* Plots outside of Excel: `dotchart` and `vioplot` examples
* The Grammar of Graphics in R with `ggplot2`

### Jan 27 (140 min): Data Preparation

* [GitHub registration](https://github.com/join)

* `ggplot2` exercises
    * number of carburetors
    * horsepower
    * barplot of number of carburetors per transmission
    * boxplot of horsepower by the number of carburetors
    * horsepower and weight by the number of carburetors
    * horsepower and weight by the number of carburetors with a trend line

* Filtering and summarizing data with base `R`
* Intro to `data.table`
* `data.table` exercises with `hflights`
    * the number of cancelled flights
    * the shortest flight on each weekday
    * the average delay to all destination
    * the average delay to all destination per destination
    * plot the departure and arrival delays
    * plot the average departure and arrival delays per destination
    * plot the average departure and arrival delays per flight + size
    * estimate the delay to Budapest

* Some quick examples on string and date manipulations
* Left joins

### Jan 28 (140 min): Models

* GitHub integration in RStudio
* Correlation, causality
* Linear regression
* Goodness of fit
* Polynomial regression
* Overfitting
* Confounders

Datasets and references for the model examples:
* [height & weight dataset](http://bit.ly/BudapestBI-R-csv)
* [OLS trend line distance from actual points](http://psycho.unideb.hu/statisztika/pages/interaktiv.html)
* [Shoe size & math](http://bit.ly/math_and_shoes)
* [Bickel et al 1975](http://bit.ly/bickel-1975)
