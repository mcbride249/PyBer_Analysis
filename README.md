# PyBer_Analysis

**##Project Overview**

Analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO

**Goals**

Determine the mean, median, and mode for the total number of rides for each city type
  
The average fares for each city type
  
The average number of drivers for each city type
  
**##Resources**

Data Source: city_data.csv, ride_data.csv, 
Software: Python 3.7.10, Anaconda Navigator, Visual Studio Code, 1.38.1
References: pandas documentation 1.3.4  https://pandas.pydata.org/docs/index.html

**##Summary**

 **The total number of rides for each city type**
  
  Urban: Mean: 24.62  Median: 24.0 Mode: 22 & 25
  
  Suburban: Mean:17.36 Median: 17.0 Mode: 17
  
  Rural: Mean:6.94 Median: 6.0 Mode: 6
  
  **The average fares for each city type**
  
  Urban: $24.53
  
  Suburban: $30.97
  
  Rural: $34.62
  
  **The average number of drivers for each city type**
  
  Urban: 36.68
  
  Suburban: 13.71
  
  Rural: 4.30
  
**##Module 5 Challenge - Written Analysis**

**##Challenge Overview**

The purpose of this analysis was to use pandas to create a visual summary of the ride sharing data by city type (urban, suburban, and rural) against several metrics. The key metrics that were examined were the total ride count, the total drivers for each city type, the average fare per rider for each city type, and the average fare per driver for each city type. This data was to be presented in visually with a pivot table as well as a graphically using a multiple-line graph. Using pandas in this analysis, allowed us to determine the above metrics for a large data set that elsewise would have been too large to produce meaningful results in a timely manner, and the purpose of presenting the data via a visual means was to clearly demonstrate the trends in the cost between the cost and ridership between the city types. This data would then be presented to V. Isualize and the other decision-makers at PyBer to inform their understanding of possible trends and allow them to make strategic decisions regarding PyBer going forward.


**##Results**

**##General**

Image 1 – PyBer Data Summary

![Image 1 - PyBer Data Summary](https://user-images.githubusercontent.com/92111396/143509091-26c7f5fd-33a4-449e-b966-0122dc45224c.PNG)
https://github.com/mcbride249/PyBer_Analysis/blob/main/Analysis/Image%201%20-%20PyBer%20Data%20Summary.PNG


Image 2 - PyBer Fare Summary

![PyBer_fare_summary](https://user-images.githubusercontent.com/92111396/143509097-b7c23cb9-4199-450a-81de-42a9f51874ba.png)
https://github.com/mcbride249/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png


From the data that was analysed we were able to make a number of statements regarding the differences in ride-sharing trends between the different city-type. The total number of rides, total number of drivers, and overall fare brought in tended to be higher in the urban areas and decreased as one moved out to the suburbs and rural city types. However, the average fare per ride and average fare per driver followed the opposite trend and both were lower in the urban city type and trended upwards and as one moved from the urban area to suburban and rural areas. 

These trends, as illustrated in Image 2 (PyBer Fare Summary) show that the urban area is the main point of business for PyBer as the majority of it’s rides and income are generated here. Furthermore, we can extrapolate from the low average fare per ride, that these trips are usually short in duration, although there are more of them.  

The rides to driver ratio for each city type are urban: 0.67, suburban: 1.2, and rural: 1.6, which shows that while there may not be more demand in terms of the number of rides for the suburban and rural areas, they are underserviced by drivers by over fifty percent when compared to the urban areas. 

**##Total Rides**

As mentioned previously, the number of total rides were higher in the urban area and decreased as one moved to the suburbs and rural areas, accounting for thirteen times more rides in the urban areas than the rural areas. This makes sense as urban areas tend to a have larger population and would account for a larger share of rides.

**##Total Drivers**

Similar to the total ride count, the number or total drivers were higher in the urban area and decreased as one moved to the suburbs and rural areas. Again, this makes sense as urban areas tend to a have larger population and would account for a larger share of drivers. Based on the total fares being collected in urban areas and the number of riders, drivers may think that this is the best place to earn money, particularly if they did not look at the average fare per driver.

**##Total Fares**

As can be seen in Image 1 (PyBer Data Summary), it is clear that the urban city type brought in the majority of fares for PyBer with $39,854.38 worth of fares, compared to the rural area which had a total of $4,327.93 worth of fares. The total fares earned overall in the urban city type are approximately nine times higher than those in the rural area and just over double those of the suburban area which had a total fare count of $19, 356.33. 

**##Average Fare per Ride**

As mentioned previously, the rides to driver ratio for each city type were urban: 0.67, suburban: 1.2, and rural: 1.6, demonstrating that the rural areas tended to be underserviced when compared to the urban ones. However, the more rural the area, the more they collected per ride. Again, this makes sense, as the distances one travels in rural areas tend to be larger than those in urban areas.

**##Average Fare per Driver**

The average fare per driver was similarly higher in the rural areas compared to the urban ones. This makes sense considering the fact that there is a high ride to driver ratio, which would allow them to collect more in fares overall due to the lack of competition from other drivers. 


**##Summary**

From the analysis of the data, we can conclude that the main business area for the PyBer is the urban city type and that on average the more rural city types are not as well serviced as the urban ones. With that said, there are several business recommendations that can be put forward.

  1. PyBer should remain focussed on the urban areas as this is where it makes 62% percent of its revenue, more than the other two areas combined. While the number of drivers is   already higher in these areas, and the average fare per ride and driver are lower when compared to the other city types, this has not yet had an impact on PyBer’s performance.   There is clearly a strong demand in urban areas for PyBer’s services based on the number of rides, with coupled with the income generated should remain PyBer’s focus. 

  2. Driver’s who are looking to gain a higher far per ride should be encouraged to conduct business activities in the suburban and rural city types where the average fare per     ride and average fare per driver are higher and is currently suffering form a lack of available drivers.

  3. PyBer should look to expand its services in the suburban and rural areas. Currently there is a lack of drivers compared to the number of rides. Encouraging more drivers to   this area may cause the ridership to increase due to the easier availability of PyBer but does run the risk of decreasing the fares drivers earn in per ride. Further data       would be needed to determine if an increased presence in these areas would encourage more ridership and should be explored before any large scale tasking of resources.      








