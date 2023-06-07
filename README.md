# Rainfall Comparison: Seattle, WA vs. St. Louis, MO
The project aims to determine whether it rains more in Seattle, WA or St. Louis, MO. The main stakeholders are an adult person and their set of parents.

## Data
The data used is daily precipitation measured in Seattle and St. Louis from January 1, 2017 to December 31, 2022.
Two data sets corresponding to Seattle and St. Louis were downloaded from the National Centers for Environmental Information — [NOAA Climate Data](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND).
The data sets can be accessed through the following links: 

For the Seattle data set: [seattle_rain.csv](https://raw.githubusercontent.com/brian-fischer/DATA-3320/main/weather/seattle_rain.csv)

For the St. Louis data set: [stl_rain.csv](https://raw.githubusercontent.com/brian-fischer/DATA-3320/main/weather/stl_rain.csv)

To know more about the data sources consult the [weather folder](https://github.com/brian-fischer/DATA-3320/tree/main/weather) in the [Github repository for DATA 3320](https://github.com/brian-fischer/DATA-3320).

## Analysis
Numerical summaries and plots were created to have an overview of the data. They were grouped by city to compare Seattle and St. Louis. In order to determine the city in which it rains more, 3 approaches were considered:

* Amount of precipitation in inches
* Number of rainy days
* Number of heavy rain days

### Amount of precipitation in inches
A numerical summary with the function `describe` grouped by city. For further analysis, the mean of the precipitation was calculated by city and year. Bar plots were made to visualize the means by city and month.

### Number of rainy days
The number of rainy days was counted overall and by year. To see more detailed trends, bar plots of the mean of rainy days per month and city were created.

### Number of heavy rain days
As there is no unique definition of "heavy precipitation", it was decided to use outliers to count days of heavy rain days. Outliers are outside the normal so they do align with the definition of heavy rain given by [EPA](https://www.epa.gov/climate-indicators/climate-change-indicators-heavy-precipitation).
