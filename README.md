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
* Summarize FARS Data for Multiple Years by counting the number of accidents for each month in each year
```
fars_summarize_years(years)
```
* Map FARS Data for a Specific State and Year
```
fars_map_state(state.num, year)
```

## Getting Started
The package vignette demonstrates how to use the **`mycoursera`** workflow to perform a basic analysis pipeline for FARS data. This vignette can be viewed online [here]([https:///Users/shuilan/Documents/GitHub/Coursera/mycoursera/vignettes/model_details.html](https://htmlpreview.github.io/?https://github.com/lanshui98/mycoursera/blob/master/vignettes/model_details.html)https://htmlpreview.github.io/?https://github.com/lanshui98/mycoursera/blob/master/vignettes/model_details.html).
