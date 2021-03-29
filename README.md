## Coronavirus flexdashboard app

### Description

This is a coronavirus flexdashboard app that allows the user to display different types of COVID data after selecting the following inputs: 

+ Up to three of a few select countries in Europe (highlighted on map)
+ Type of COVID data to display (deaths, recoveries, or cases)
+ Smoothed or unsmoothed data

+ Raw data or a natural log transformation
+ Start date for time series 


### Data

Data for this dashboard come from the R package [coronavirus](https://github.com/RamiKrispin/coronavirus). Raw data were downloaded from the [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)


### R packages: 


+ **Interface:**  `flexdashboard`, `shiny`

+ **Data conversion & manipulation:** `dplyr`, `tidyr`

+ **Plotting:** `plotly`, `ggplot2`

+ **Mapping:** `leaflet`

+ **Data source:**`coronavirus`


