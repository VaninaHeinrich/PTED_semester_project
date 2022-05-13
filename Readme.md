# Proposal for Semester Project

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS22                              |
|----------------|---------------------------------- |
| **Data:**      | 1 Wild Boar Movement Data in Fribourg           |
| **Title:**     | Vertical movement analysis of a wild boar in the canton Fribourg        |
| **Student 1:** | Vanina Heinrich                 |
| **Student 2:** |                 |

## Abstract 
In the canton of Fribourg, a wild boar could be followed for 2 years. This wild boar was located in the pre-Alps. 

## Research Questions
Is there a seasonal migration to lower and higher elevations? 
Hotspots of presence could be noticed. Are they linked to particular agricultural crops? 

## Results / products
We believe that migration to lower elevations occurs in winter due to snow and that movement to higher elevations occurs as soon as the snow melts (April/May). 
Having been to one of the spots on site, we believe that the hotspots are related to crops typically enjoyed by wild boar such as corn. 

## Data
For this project, confidential data from the forest and nature service of the canton of Fribourg will be used.The altitudes are available in the base data. 
For agricultural crops, data will have to be requested from the agricultural service of the canton of Fribourg. 

## Analytical concepts
Vertical movement
Superposition of movement and map
statistical analysis of relation between movement/altitude and movement/crops (or movement/roads as plan B)

## R concepts
library(readr)        # to import tabular data (e.g. csv)
library(dplyr)        # to manipulate (tabular) data
library(ggplot2)      # to visualize data
library(sf)           # to handle spatial vector data
library(terra)        # To handle raster data
library(lubridate)    # To handle dates and times
packages for statistical analysis

## Risk analysis
That the agriculture department does not provide data for agricultural crops. Plan B would be an analysis related to the presence of roads (are there more limiting roads? where would wildlife corridors make sense given wild boar movements?)

## Questions? 
In addition to visualization, how can we statistically verify that there is a relationship between the different elements? 
