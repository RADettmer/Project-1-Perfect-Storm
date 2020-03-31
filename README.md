# RADettmer
Project 1 Perfect Storm
# Project1-Perfect-Storm
Project1- Group1 - Perfect Storm - CWRU Bootcamp

Working Problem Statement

Group 1
A Perfect Storm? Wildfires in the US

Are weather patterns and human activity correlated to forest fires in the US?
    How do natural and manmade factors interact to influence forest fires?
    Can we predict where wildfires will start and factors that help propagate them     
(topography etc)?

Rationale: Forest fires and wildfires have become a frequent part in our daily lives causing devastating losses to life, property and habitat. Recent examples include the California and Australia wildfires of 2019. 

What could we do to predict fires thus preventing loss of life and property?

Data Needs/Sources include: Weather data (rainfall, humidity, lightning strikes, wind), forest density, topography data, US Forest/Park Service (campfires), Google Maps(proximity to water, road density, etc.), Census data (population density), US Core Science for Geography (topography/hydrography)

First step in analysis:
    Explore data to determine time frame of analysis (expected to be 1992 to 2015) 
    Begin to map State/US wildfire data to obtain locations of interest and begin to plot     
    collect longitudinal data about those points
    Plot average temperature and # of wildfires to determine correlation
    
Some conclusions:
    Wild fire volumes vary by year but have increased between 1992 and 2015.
    Size of affected land has also increased during the same period.
    Lightning is the largest cause of wild fires for the larger fire type, F & G.
    Wind gust ranges have been increasing over this period.
    Wind speed has a weak but negative correlation to the length of burn.
    Housing density and population density do not have a significat correlation to the length of burn.

File list:

Camp.Fires.ipynb - API call for camp fires - not completely working
Combined_Data_Perfect_Storm.ipynb - python file to merge fire, census and weather data
Entire US Heatmap.JPG - heat map of entire US
FHM_State_County_codes.xls - county codes to determine locations in fire data to match to census data
FiredataWorking.ipynb - jupyter notebook code to generate scatter plots and regression lines on fire data and combined data
FiresAll.ipynb -
Hawaiian Heatmap.JPG - heat map
Mainland US Heatmap.JPG -
NOAA API.py -
Pesent_start.pptx - started presentation with some basic graphs
WeatherAPI_Data_All_11560_values.csv - file will all of the downloaded weather data
WeatherAPI_Data_first700.csv - file will only the first 700 locations of weather data
WeatherPull v3.py - python API pull for weather data
WeatherPull.py - python API pull for weather data
all_geocodes_v2016.xlsx - FIPS codes for weather data to link to fire data
final_data_set.all_combined.cat.xlsx -
final_data_set.all_combined.xlsx - final combined data of fire, census and weather


