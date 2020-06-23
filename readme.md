## Introduction

This Coronavirus dashboard, an extesion of dashboard developed by RamiKrispin [source](https://github.com/RamiKrispin/coronavirus_dashboard) provides an overview of the 2019 Novel Coronavirus COVID-19 (2019-nCoV) pandemic. This dashboard is built with R using the Rmakrdown framework and can easily be reproduced by others.

## Data Source

* World: https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv
* India: https://api.covid19india.org/data.json

## Requirements
The following packages (libraries) are required 
**Packages**

* Dashboard interface - the [flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/) package. 
* Visualization - the [plotly](https://plot.ly/r/) package for the plots and [leaflet](https://rstudio.github.io/leaflet/) for the map
* Data manipulation - [dplyr](https://dplyr.tidyverse.org/), and [tidyr](https://tidyr.tidyverse.org/)
* Tables - the [DT](https://rstudio.github.io/DT/) package
* SEIR - [deSolve](http://desolve.r-forge.r-project.org/) deSolve package
* The packages used are as follows:
  1. Shiny
  2. flexdashboard
  3. leaflet
  4. leafpop
  5. purrr
  6. plotly
  7. jsonlite
  8. lubridate
  9. forecast
  10. zoo
  11. deSolve 
  
## Installation
After loading the packages open the Coronavirus.rmd and change the path in the source() function with the path where you have placed the files from this repo.  Once this is done you can press the **Run Document** in the breadcrump area where knitting option is present.  This will execute the programm.

