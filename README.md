## Project GEO 876 - Visualizing wildfires interactively around the globe
This project visualizes wildfires around the globe in near real-time, highlighting large wildfires regarding thermal intensity, temporal recentness and uncertainty. Added to this, large cities with more than 1 million inhabitants threatend by an approaching proximate wildfire are depicted. Using (near)-real-time data of NASA Fire Information for Resource Management System (FIRMS), this project provides an automated pipeline and interactive dashboard for an early warning system of wildfires around the globe.

## Main workflow steps
This workflow followed a clear step-wise approach: 
First, all datasets were loaded in and inspected. Second, the data was processed and made spatially explicit. Third, a spatial analysis of the threatend cities was conducted. Fourth, the data was visualized on a static map and then on an interactive map. The final map is a html file, which can be opened in a browser such as Google Chrome.

## Data Sources: 
The wildfire data was obtained via API of the NASA Fire Information for Resource Management System (FIRMS) with the following link: 
https://firms.modaps.eosdis.nasa.gov/api/area/
Then, the sensor VIIRS_NOAA20_NRT(VIIRS NOAA-20 Near Real-Time, Real-Time and Ultra Real-Time) was selected.
For access, requesting a map key is required. 

The cities data was obtained via public url from opengeos with the following link:
https://opengeos.org/data/world/world_cities.csv

## Setup Instructions: 
# Exactly what software and libraries are required to run the code (e.g., pointing to an environment.yml or requirements.txt file). 
This project requires a specific spatial software stack. To recreate the environment:
1. Ensure you have Conda installed.
# 2. Run: `conda env create -f environment.yml`
# 3. Activate: `conda activate zurich-heat-env`

## Execution Order: 
Recreate environment by running the provided environment.yml. Then, execute 'wildfire_project.ipynb' from top to bottom.

