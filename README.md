# Surfs Up!

Using Python, Jupyter Notebook, Pandas, matplotlib, SQLLite, and SQLAlchemy to analyze weather data for potential business location planning.

## Overview of Project

An analysis of data collected from observation points to find key weather information across a period of time. This information will be used to scout potention locations for a business.

### Purpose

A partnership with W.Avy to open a Surf and Ice Cream shop on the island of Oahu, Hawaii. Due to past business experience, W.Avy wants to make sure there isn't too much precipitation in the area where we are planning to open the shop. Using data collected from observation points (or stations) across the island, this is an analysis of temperature and precipitation statistics across the island. Data is also added to a Flask webpage for easy access for the board of directors.

## Results

#### *Temperature Statistics for June*
![june_statistics](https://user-images.githubusercontent.com/108373151/188281518-d538c2ce-79dc-46cf-8d86-24b5a4a0658a.png)

#### *Temperature Statistics for December*
![december_statistics](https://user-images.githubusercontent.com/108373151/188281522-1fcff661-81e7-4c81-8548-020e949125e2.png)

Some data points to note from the above images:
- The average temperature is 75°F in June and 71°F in December. The difference of the temperatures is approximately -5%.
- Minimum temperature is 64°F in June and 56°F in December. 
- Maximum temperature is 85°F in June and 83°F in December. This suggests the potential high temperature is nearly the same as it is in June.

## Summary

#### *Temperature Histogram for June*
![june_histogram](https://user-images.githubusercontent.com/108373151/188282377-d84d5a6f-9605-4edc-9e7b-0e203467294b.png)

#### *Temperature Histogram for December*
![december_histogram](https://user-images.githubusercontent.com/108373151/188282389-3795b7ee-c13e-4ce5-87b1-ef5026ab0a79.png)

Looking at the station that recorded the most data points, USC00519281, the above graphs continue to support the moderate temperatures at Oahu. 
- The most frequent bin of recorded temperatures in June is approximately 71°F.
- The most frequent bin of recorded temperatures in December is approximately 69°F, followed by approximately 74°F.

There is not a big difference in the temperatures recorded in June and December. This data supports the theory that the surf and ice cream shop could be open year-round and get plenty of business no matter the time of year. With the high temperature of 83°F in December, customers would still be looking for a way to cool off in the winter months.

Would recommend to continue analysis of June and December with similar looks at precipitation, since the investor has major concerns about being "rained out".

#### *Precipitation Statistics for June*
![june_prcp](https://user-images.githubusercontent.com/108373151/188282770-092cfa9e-e5d2-43c6-8eeb-41cb961da795.png)

#### *Precipitation Histogram for June*
![june_prcp_histogram](https://user-images.githubusercontent.com/108373151/188283084-4c005960-9d46-43ad-8548-06c97549b9b2.png)

#### *Precipitation Statistics for December*
![december_prcp](https://user-images.githubusercontent.com/108373151/188282781-84ad618f-e04f-43c1-9777-5ceacc872bf2.png)

#### *Precipitation Histogram for December*
![december_prcp_histogram](https://user-images.githubusercontent.com/108373151/188283099-b9e90f0a-4782-4536-bd31-153949508bdf.png)

Some data points to note from the above images:
- The average amount of rainfall is 0.14 inches in June and 0.21 inches in December.
- Maximum amount of rainfall is 4.43 inches in June and 6.42 inches in December.
- Although there are some days in December that have significant rainfall, overall no precipitation is counted on the majority of days in both June and December.

Combining the data in all temperature and precipitation images, the data reflects that while June may have higher temperatures, it averages less rainfall than December.

## Further Recommendations

The data above mainly focuses on the temperature difference between June and December for the entire island of Oahu. Additional data needs to be considered, such as proximity of location to cities, tourist areas, and surfing conditions like wind speed and wave swells. I would recommend to narrow the search down to 3 possible locations for the surf and ice cream shop. Once those locations have been identified, I would find the GPS location of the 9 observation stations featured in the data. 
To further this business planning analysis, on the 3 identified stations, I would perform the following queries:
- Create a stacked line graph to show temperature reported at each station for the past 5 years. This type of analysis could help determine if there are any major temperature changes in different parts of the island. If the ice cream shop is in an area where it is cooler than normal, customers are less likely to buy ice cream.
- Create a stacked line graph to show precipation reported at each station for the past 5 years. This type of analysis could help determine if there are any major precipitation changes in different parts of the island. If an area is more rainy, it is less likely to draw customers for both the surf shop and the ice cream shop.