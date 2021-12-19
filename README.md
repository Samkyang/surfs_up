# surfs_up

## Overview of the statistical analysis:

##### The purpose of this analysis was to look into the historical data for temperature data for the months of June and December to find out if it is possible to have a surf shop that serves ice cream.

## Results:
##### After using SQLAlchemy, SQLite, Pandas and Python to analyze the data in the hawaii.sqlite files that stores historical data. We see the following for the months of June and December:

![June_Temps](https://user-images.githubusercontent.com/92561003/146688842-80f9d71e-2603-4c53-8f76-1a778cd2f5a1.png)
![Dec_Temps](https://user-images.githubusercontent.com/92561003/146688851-7a1a5332-9b40-4258-bbe8-14a9f16bb5f4.png)


##### Main differences:
* December had an almost 10 degree difference from June when it came to lowest temperature for the month.
* December had less data points than June did. 1517 compared to 1700 respectively.
* Only 25% of the days in June that are below 73 degrees while 75% of the days in December are below 74 degrees.

## Summary:
### There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)

#####
Even though the weather is really ince in Oahu and generally above 70 degrees year round, June has still warmer weather most days of the month versus December. When looking at the standard deviation for both months we see that there is only a .5 difference making the weather differences very neglible.

Other queries that I would run are giving a visual breakdown by providing a historgram so people can visually see the distribution of days based on the weather.

![Dec_Hist](https://user-images.githubusercontent.com/92561003/146689395-bd54f549-8df0-41ad-a3f2-73ae099924aa.png)
![Jun_Hist](https://user-images.githubusercontent.com/92561003/146689399-6b12fd3b-c88f-4233-8ca8-71e12def1ff9.png)

