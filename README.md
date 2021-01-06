**The COVID-19 Dashboard**

This dashboard provides an overview of the Novel Coronavirus (COVID-19 / SARS-CoV-2) epidemic for Bulgaria and its surrounding countries. This dashboard is built with R using the R Makrdown and flexdashboard framework and was adapted from the [dashboard](https://ramikrispin.github.io) of Rami Krispin, courtesy of [Antoine Soetewey](https://github.com/AntoineSoetewey).

**Code**

The code for the dashboard is available on [GitHub](https://github.com/Met0o/COVID).

**Packages**

* Dashboard interface - [flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/)
* Visualization - [plotly](https://plot.ly/r/)
* Data manipulation - [dplyr](https://dplyr.tidyverse.org/), [tidyr](https://tidyr.tidyverse.org/), and [purrr](https://purrr.tidyverse.org/)
* Mapping - [leaflet](https://rstudio.github.io/leaflet/) and [leafpop](https://github.com/r-spatial/leafpop)

**Data**

The input data for this dashboard is the dataset available from the [`{coronavirus}`](https://github.com/RamiKrispin/coronavirus) R package.

The raw data is pulled from the Johns Hopkins University Center for Systems Science and Engineering (JHU CCSE) Coronavirus [repository](https://github.com/RamiKrispin/coronavirus-csv).
