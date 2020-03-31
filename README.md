'Network Analysis CW2 - Data Prep.ipynb' shows how OpenStreetMap data was extracted and how bike share usage data was concatenated. Unfortunately, I did not manage to upload the original csv files containing usage data as they are too large, but I can send them over upon request, or they can be obtained here: https://cycling.data.tfl.gov.uk. The data used is the data corresponding to May 2019: 
 - 160JourneyDataExtract01May2019-07May2019.csv
 - 161JourneyDataExtract08May2019-14May2019.csv
 - 162JourneyDataExtract15May2019-21May2019.csv
 - 163JourneyDataExtract22May2019-28May2019.csv
 - 164JourneyDataExtract29May2019-04Jun2019.csv

The last csv file contains data including the start of June - that was manually edited to only include May values.

'visualizing and analysing network.ipynb' shows how the networks were visualized and how node degrees were calculated. Unfortunaly, I kept getting an AttributeError when trying to calculate other centrality measures and did not manage to fix it.
