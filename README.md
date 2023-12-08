# mycoursera

## Introduction
The repository houses the **`mycoursera`** R packag for a basic analysis pipeline for FARS data.

This is also the homework of the coursera course: Building R Packages, but with some innovative extensions.

## Features
The package contains a set of R functions related to working with Fatality Analysis Reporting System (FARS) data, including reading data, summarizing, and visualizing accident information.

## Dependencies
`mycoursera` requires the following `R` package:
```r
library(devtools)
library(dplyr)
library(readr)
library(maps)
library(tidyr)
library(graphics)
```

## Installation
Once the dependencies are installed, **`mycoursera`** can be loaded using the following command:
```r
devtools::install_github("lanshui98/mycoursera")
library(mycoursera)
```

## Basic Usage
* Reads FARS data for multiple years and returns a list of tibbles
```
fars_read_years(years)
```
* 
