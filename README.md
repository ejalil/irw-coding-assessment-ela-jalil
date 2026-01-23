# DC 311 Service Requests Analysis - IRW Code Assessment

**Author:** Ela Jalil

## Project Description
This project analyzes Washington, DC 311 service request data across zip codes, service types and departments. This analysis inlcudes a 10-year analysis from 2015-2024, and two data visualizations. 

## How to Run the Code
1. Clone or download this repository.
2. Open the project in RStudio.
3. Ensure all required packages are installed (see below).
4. Run the data cleaning scripts before running the analysis scripts.
5. Execute the visualization scripts to reproduce figures.

All scripts are written in R and are intended to be run sequentially.

## Required Packages
The following R packages are required to run the analysis:
library(tidyverse)
library(janitor)
library(dplyr)
library(DT)
library(lubridate)
library(tidyr)
library(leaflet)
library(sf)
library(ggplot2)

- `tidyverse`
- `janitor`
- `dplyr`
- `DT`
- `lubridate`
- `ggplot2`
- `tidyr`
- `sf`

You can install them using:
```r
install.packages(c("tidyverse", "dplyr", "ggplot2", "tidyr","janitor","DT","lubridate","sf"))
