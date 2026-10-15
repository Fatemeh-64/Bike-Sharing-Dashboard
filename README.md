# Bike Sharing Dashboard

Interactive dashboard created in **R** using **Flexdashboard** and **Shiny** to explore daily bike rental demand.

## Overview
Uses the [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset), specifically `day.csv` (731 daily observations). Explores rentals by season, month, date, weather, and casual versus registered users.

## Tools
R, Shiny, Flexdashboard, ggplot2, Plotly, DT, dygraphs, tidyverse, lubridate, scales, xts, and tidyr.

## Features
- Searchable, filterable data table
- Season selector with summary gauges and value boxes
- Interactive daily time-series, seasonal bar chart, and monthly trends
- Storyboard charts: histogram, boxplot, and density comparison

## How to run
1. Install R and RStudio.
2. Download the UCI Bike Sharing Dataset and put `day.csv` beside `bikesharing_dashboard.Rmd`.
3. Install dependencies:
```r
install.packages(c("shiny", "flexdashboard", "tidyverse", "plotly", "DT", "lubridate", "scales", "dygraphs", "xts", "ggplot2", "tidyr"))
```
4. Open `bikesharing_dashboard.Rmd` in RStudio and choose **Run Document**.

## Data source
UCI Machine Learning Repository: [Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset), Fanaee-T and Gama (2013).

## Status
Academic project. Dataset and screenshots are not yet included; add them to complete the reproducible portfolio.
