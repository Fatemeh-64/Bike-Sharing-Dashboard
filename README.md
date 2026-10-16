# Bike Sharing Dashboard 🚲

**Interactive Data Analytics Dashboard | R · Shiny · Flexdashboard**

An interactive dashboard for exploring bike rental demand, seasonal patterns, weather conditions, and differences between casual and registered riders.

## Dashboard Preview

### Key Metrics

![Bike Sharing Dashboard — Key Metrics](bike_dashboard_images/key_metrics.png)

Overview of total rentals, average daily demand, and maximum rentals, with season-based filtering.

### Interactive Visualizations

![Bike Sharing Dashboard — Interactive Visualizations](bike_dashboard_images/interactive_visualizations.png)

Daily rental time series, average rentals by season, and monthly demand patterns.

### Storyboard and Distribution Analysis

![Bike Sharing Dashboard — Storyboard](bike_dashboard_images/storyboard.png)

Distribution of daily rentals, seasonal variation, and casual versus registered rider comparisons.

## Project Overview

This project uses the [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset) (`day.csv`, 731 daily records) to explore how rental activity changes over time and across seasons and weather conditions.

**Questions explored**
- How does bike rental demand change across seasons and months?
- How do casual and registered riders differ?
- What trends appear in daily rental activity?
- How can interactive visualizations help users explore demand?

## Tools & Technologies

- **R / RStudio** — data analysis and dashboard development
- **Shiny & Flexdashboard** — interactive dashboard layout and controls
- **ggplot2 & Plotly** — static and interactive visualizations
- **dygraphs & xts** — time-series exploration
- **DT** — searchable and filterable data tables
- **tidyverse, lubridate, scales, tidyr** — data preparation and presentation

## Dashboard Features

| Feature | Description |
| --- | --- |
| Seasonal analysis | Compare rentals across seasons |
| Time-series charts | Explore daily rental trends |
| Rider comparisons | Examine casual vs. registered riders |
| Interactive controls | Select seasons and explore charts |
| Summary metrics | View value boxes and gauges |
| Data table | Search and filter underlying records |
| Distribution plots | Explore histograms, boxplots, and density charts |

## Run the Project

1. Install **R** and **RStudio**.
2. Download `day.csv` from the [UCI dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset).
3. Place `day.csv` in the same folder as `bikesharing_dashboard.Rmd`.
4. Install the required packages:

```r
install.packages(c(
  "shiny", "flexdashboard", "tidyverse", "plotly",
  "DT", "lubridate", "scales", "dygraphs",
  "xts", "ggplot2", "tidyr"
))
```

5. Open `bikesharing_dashboard.Rmd` in RStudio and select **Run Document**.

## Dataset & Attribution

**Source:** [UCI Machine Learning Repository — Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset). Fanaee-T and Gama (2013).

## Project Context

Academic data visualization project showcasing exploratory data analysis, interactive reporting, and dashboard design.

---
*Portfolio project | Data Analytics & Visualization*
