# Data-Collection-and-Curation-Assignment
A map visualization above represents the Male and Female percent of the total Latino population living below the poverty level for every county in Texas.
Obtain data from Census Reporter: https://censusreporter.org/data/table/?table=B17001I&geo_ids=04000US48,050|04000US48&primary_geo_id=04000US48#valueType|estimate
Contains Poverty Status in the Past 12 Months by Sex by Age (Hispanic or Latino) for all Texas Counties (2020 Census) 
Table B17001I
Data: I used the geojson file to download the data to be able to make spatial analysis on this data set since it include the geometry coordinates
Goal: My goal was to create a map that demonstrated the percent of Male/Female Latino/as living below the poverty rate for each county in Texas. 
Process: I used the geojson file to filter out all the columns I wanted. Which only included the adult data columns. I then ensured I updated the total for the male, female and overall total population living below the poverty level.
Once I cleaned the data set I normalized the data set by dividing the total female population living below poverty by the total population living below poverty and then multiplied it by 100 to get the percent. I did this for male and female in a new column. 
Visualization: In order to visualize both population percents I created subplots to see both populations side by side in a Choropleth style map to demonstrate the significant percent diffrences. 
