# Surfs Up 

## Overview

Provide analysis of temperature trends for the months of June and December in the Hawaiian island of O'ahu to gauge the potential year-round sustainability of a surf and ice cream shop.

> **Resources:** ***SQLite, hawaii.sqlite, SQLAlchemy, Jupyter Notebbok, Pandas, Python3***

## Results

* With 1700 measurements, the average temperature during June is nearly 75°F (74.9) and 71°F for December with 1517 measurements.
* There is a 27° range for December (Highest 83°F vs Lowest 56°F) and a 21° range for June (Highest 85°F vs Lowest 64°F)
* Lower Quartile(25%) of 69°F for December and 73°F for June.

![june_temps](https://user-images.githubusercontent.com/108758105/191837258-53c5890e-42e5-4ef8-b541-02e330f291ba.png)  ![dec_temps](https://user-images.githubusercontent.com/108758105/191837267-d855e2be-9915-4684-8b27-65b407d89481.png)


## Summary

&ensp;&ensp;&ensp; With averages in the low to mid 70's year-round and standard deviations of less than ±4° from the average, it is safe to say that a surf and ice cream shop is a smart business venture based on tempuratures alone.  While there is a range of 21° and 27° for June and Decembre, respectively, as can be seen in the second bullet point of the results, given that the Lower Quartile is 69°F for December and 73°F for June, the majority of the temperatures are 70°F and above throughout the year.  The days below 70 can still be marketable as surfers can come in for board servicing and supplies, the colder days can be time for decompressing from a busy season and shopping for supplies/ prepping the shop for the next season, and it is never really too cold for ice cream.

&ensp;&ensp;&ensp; Additional queries that can further inform this analysis would be a breakdown by station to see where on the island may be an optimal location and an overall statistical summary of precipitation to see how many days of rain affect the island and then by station for location optimization.

&ensp;&ensp;&ensp; Also, even though the data isn't present on the file and given Hawaii being in the middle of the ring of fire, wind speeds and tsunami trend data can be extremely helpful. And given that O'ahu is where the state capital is located, peak tourism data may further inform this analysis.
