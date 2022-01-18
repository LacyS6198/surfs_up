# Overview
The goal of this project is to analyze weather data in Oahu to determine if opening a surf shop is sustainable thoughout the year. 

The profitability of surf shops are highly dependent on the weather. The shop needs to be located in an area that has enough rain to keep the area tropical and vegetation lush, but not too much that it deters surfers. The temperature must also be warmer to encourage surfing and people at the beach. If the location has too many rainy days, or too many colder-weather days, there will not be enough customers to sustain the Surf Shop. 

Throughout this module, the precipitation in Oahu was analyzed. The analysis done in the Module 9 Challenge is specifically to compare the temperature in June against those in December to determine whether there are enough warm-weather days throughout the year to keep the shop open year-round.

# Results
This section details the key results from the analysis.

## Summary Statistics
Below are the summary statistics for the months of June and December. Data includes all values for the given month, including all days and all years, that were available in the data set. 

|**June Statistics**|**December Statistics**|
| ------------- | ------------- |
|![June Stats](/Images/June_Stats.png)|![December Stats](/Images/December_Stats.png)|
<br/>

## Key Observations/Differences
From the summary statistics, we can see three main differences between the temperatures for June and December. 

 - The average temperature for December is only 3 degrees lower than in June
 - The minimum temperature in December is 56 while the minimum in June is 64
 - The quartile temperatures (25%, 50%, 75%) are only 3 - 4 degrees different between June and December

# Summary
Overall, the average temperature in June and December are similar with only an approximately 3 degree difference. December, as could be expected, is lower than June's average. Not only are the averages similar, but the quartile ranges are as well. For each quartile, December is only 3 - 4 degrees colder than June. 

However, December does have a lower minmum temperature meaning that the cooler days may be too cold for surfers and ice cream. In addition, the standard deviation is higher meaning that temperatures throughout the month can be cooler. If we look at +/- 1 standard deviation from the average, December is between 67.3 - 74.8 degrees, while June is between 71.7 - 78.2 degrees. With a lower average temperature and higher standard deviation value, there is a risk of more cold days in December than in June. 

While average temperature is one variable to consider during the analysis, there are others that could affect the ability to be profitable year-round. The below queries could be used to expand upon the current June/December analysis. 
 
 - Determine the percentage of days during each month that temperatures were below 70 degrees. Determining the percentage of days below 70 degrees would allow us to compare the expected decline in business during the month of December. If the June profitability estimates were known, or profits based on temperature, the analysis could be refined to determine whether the winter month(s) sales would be able to sustain operations. 
 - Compare the precipitation for the two months to determine the average number of rainy days. While December temperatures are cooler overall, there may be more sunny days during the month making it comparable to June's profitability. There could also be fewer sunny days that when coupled with the temperature make December a bad month for Surf Shops.
