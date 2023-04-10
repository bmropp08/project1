# RANKING COUNTIES IN THE US FOR QUALITY OF LIFE AND PRICE USING PANDAS

# Overview
In this project, we sought to find the county in the United States that had the best quality of life for the most affordable price. To discern our answer, we used data from various sources, such as the US Census Bureau and research institutes focused on tax policy, then ranked each county in the US based on both individual criteria and overall performance in all observed criteria. Specifically, we worked with data for median income, house price, ratio of income to house price, state property taxes, sales taxes, life expectancy, and educational attainment. These areas of measurement were chosen because they are each often driving factors in determining the quality of life for an area, as well as whether a person would like to move or live there. However, this is not an exhaustive list, as there are various other environmental factors and costs that can drive these measurements and costs. 
To come to our final answer, we added together the rankings our code ascribed for each area of measurement, then ranked each county once more based on that sum. Lower rankings were considered preferable, such as a ranking of 34 being preferable to 340, as they indicated being better ranked in each individual area of measurement. In our last step, we plotted our data, in order to find potential outliers in the distribution of the data and to find potential correlations between individual areas of measurement.

# Functionality
The notable functions of our code include its use of APIs to find location data for each county; a function to weigh state-level data for each county differently, depending on the number of counties in each state; and functions to rank each county based on its overall performance in each area of measurement.
The code also exports plots and merged .csv files for future manipulation and analysis.

#Authors
Bryan Ropp, Geoffrey Hoehn, and Daniel Adamson
