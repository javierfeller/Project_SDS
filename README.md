# Project GEO 876 - Visualizing wildfires interactively around the globe
## Abstract
This project visualizes wildfires around the globe in (near) real-time, highlighting large wildfires regarding thermal intensity as well as temporal recentness and uncertainty. Added to this, large cities with more than 1 million inhabitants threatend by an approaching proximate wildfire are visualized. Using (near)-real-time data of NASA Fire Information for Resource Management System (FIRMS), this project provides an automated pipeline and interactive dashboard for an early warning system of wildfires around the globe.

## Main workflow steps
This workflow follows a clear step-wise approach: 
First, all datasets were loaded in and inspected. Second, the data was processed and made spatially explicit. Third, a spatial analysis of the threatend cities was conducted. Fourth, the data was visualized on a static map and then on an interactive map. The final output is an interactive map as html file, which can be opened in a browser such as Google Chrome.

## Data Sources
The wildfire data was obtained via API of the NASA Fire Information for Resource Management System (FIRMS) with the following link: 
https://firms.modaps.eosdis.nasa.gov/api/area/

Then, the sensor VIIRS_NOAA20_NRT(VIIRS NOAA-20 Near Real-Time, Real-Time and Ultra Real-Time) was selected.For accessing the data, requesting a map key is required. 

The cities data was obtained via public url from opengeos with the following link:
https://opengeos.org/data/world/world_cities.csv

## Setup Instructions
This project was developed with Python 3.12 using Visual Studio Code and requires a specific environment. For recreating the environment, please see the environment.yml file.

## Execution Order
Recreate environment using the provided environment.yml. Then, execute the Jupyter Notebook'wildfire_project.ipynb' from top to bottom.

