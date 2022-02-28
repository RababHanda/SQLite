# Surf's Up 

## Overview of Project
The project studies the temperatures on the island of Oahu.

### Purpose

**Analytical:** In this project I analyze the temperature and precipitation on an island of Hawaii to determine the sustainability of opening a business (ice-cream/surf shop) which would inherently do well in higher temperatures.

**Technical:** I employ the pandas, sqlalchemy and numpy libraries within python, to extract data from dataframes without having to load the entire data.

## Results

All islands of Hawaii fall in the northern hemishpere, however they're extremely close to the equator (19.9° N) therefore they lie in the Torrid[^1] zone. 

[^1]: https://www.nationalgeographic.org/encyclopedia/zone/#:~:text=The%20tropical%2C%20or%20Torrid%20Zone,north%20and%20south%20temperate%20zones.

The weather in Torrid zones is warm throughout the year, instead of summers and winters, these regions have a wet and dry season[^2]. June being the peak dry month and December being the peak wet month. Precipitation and temperature data from these two months can be analyzed to create a business model (as they'll represent the extreme cases of the 2 possible weather scenarios affecting a ice-cream/surfing business)

[^2]: https://www.toppr.com/guides/chemistry/environmental-chemistry/torrid-zone/#:~:text=The%20torrid%20zone%20is%20generally,weather%2C%20ecosystems%20and%20geographic%20features.

Comparing the temperature statistics in both months:
<p align="center">
<img src="/Resources/temp.png" width="40%" height="30%">
</p>

Comparing the precipitation statistics in both months:
<p align="center">
<img src="/Resources/prcp.png" width="40%" height="30%">
</p>

#### Conclusion

 1. December receives higher precipitation than June 
 2. June has higher temperatures than December
 3. 

 Additionaly, from common knowledge, it can drawn that hotter (and drier) months are more favourable for an ice-cream and a surfing busines.




![Old Math percent results](/Resources/bygrade_reading_new.png) 

## Summary

The temperatures and the amount of precipitation varies over months, which is likely to affect the business. From common knowledge, it can drawn that hotter months are more favourable for an ice-cream business and drier months are more favourable for surfing busines. June is both, hotter and drier, compared to December. This makes the dry weather season a lot more beneficial for both business

However, the temperatures between December and June aren't all that different. Looking at the graph below, there is significant overlap, therefore there will be temperatures in December that are good for the business
<p align="center">
<img src="/Resources/temp_graph.png" width="60%" height="40%">
</p>

![Old Math percent results](/Resources/temp_graph.png) 