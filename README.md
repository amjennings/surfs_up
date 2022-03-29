# surfs_up

## Overview of Project

###### The purpose of this analysis was to evaluate the temperatures in Oahu to determine if the weather would be conducive to a surf and shake shop. This project involved querying a SQLite database table. The next step was retrieving all the temperatures for the months of June and December. These months were chosen to assess the sustainability of the shop year-round. Dataframes were created from the June and December temperature queries and summary statistics were generated.  

## **Results**

- The average temperature is a few degrees warmer in June, as indicated by the mean. 
- The maximum temperatures are very similar. 
- The minimum temperature is almost 10 degrees warmer in June.

*Summary Statistics for June*

<img width="117" alt="Screen Shot 2022-03-29 at 9 26 00 AM" src="https://user-images.githubusercontent.com/98051208/160621619-8c713cf4-8611-425c-9039-49bec95b6a3e.png">

*Summary Statistics for December*

<img width="117" alt="Screen Shot 2022-03-29 at 9 26 25 AM" src="https://user-images.githubusercontent.com/98051208/160621708-ab0e1161-9dcf-45e4-ac6a-8333b8ba66c2.png">


## **Summary**
###### Although the minimum temperature in December is lower than in June, the maximum temperature is very similar, which suggests a surf and shake shop would likely be successful year-round. Additionally queries could provide more information to help support whether a year-round shop would be successful. It would be helpful to compare the precipitation in June to December, as temperature is not the only factor that would impact business. It would also be helpful if hourly temperature data could be obtained, as it is likely the shop should have shorter hours during December. To determine whether there is sufficient data, a query to count the results from each station would also be useful. Ideally, we would see a roughly equal amount from each station, as opposed to data primarily coming from only one station. This query may also inform why there are almost 200 less data points for December.
