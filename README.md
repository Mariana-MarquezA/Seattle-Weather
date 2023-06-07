# Rainfall Comparison: Seattle, WA vs. St. Louis, MO
The project aims to determine whether it rains more in Seattle, WA or St. Louis, MO. The main stakeholders are an adult person and their set of parents.

Numerical summaries and plots were created to have an overview of the data. They were grouped by city to compare Seattle and St. Louis. In order to determine the city in which it rains more, 2 approaches were considered: Amount of precipitation in inches and number of rainy days. Bar plots were made to visualize the means by city and month.

The project's findings reveal that St. Louis experiences higher annual precipitation in terms of quantity (in inches), while Seattle has more rainy days throughout the year. However, a closer examination of the monthly trends unveils a seasonal pattern where St. Louis receives less precipitation (in inches) than Seattle during a specific season, while Seattle has a dry season with more rainy days in St. Louis. This highlights the importance of considering monthly variations when analyzing rainfall patterns between the two cities.

## Requirements
Python 3.10

## Data
The data used is daily precipitation measured in Seattle and St. Louis from January 1, 2017 to December 31, 2022.
Two data sets corresponding to Seattle and St. Louis were downloaded from the National Centers for Environmental Information — [NOAA Climate Data](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND).
The data sets can be accessed through the following links: 

For the Seattle data set: [seattle_rain.csv](https://raw.githubusercontent.com/brian-fischer/DATA-3320/main/weather/seattle_rain.csv)

For the St. Louis data set: [stl_rain.csv](https://raw.githubusercontent.com/brian-fischer/DATA-3320/main/weather/stl_rain.csv)

To know more about the data sources consult the [weather folder](https://github.com/brian-fischer/DATA-3320/tree/main/weather) in the [Github repository for DATA 3320](https://github.com/brian-fischer/DATA-3320).

## Data Processing
The major steps in data processing were variable renaming, join of the Seattle and the St. Louis data sets, handling missing values and transforming the dataframe into tidy or long format. We replaced the missing with the mean precipitation on the same day of the other years.

## Author
Mariana Márquez

