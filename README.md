# PyBer Analysis
## Challenge 5: Matplotlib
### Overview
#### Purpose
This challenge analysis was based on the results from merging two .csv files into one dataframe. The two files contained the following information:
1. City Data: this data included the names of cities, how many drivers are in each city, and the type of city: urban, suburban, and rural.
2. Rider Data: this data included a date and timestamp for each ride, the cost of each ride, a ride identification to distinguish each ride, and the city that the ride took place.
When merging this data together, we are able to analyze:
1. How many rides took place per city type
2. How many drivers there are per city type
3. How much fare is and the average fare per city type

Our merged data is below:                        
![Total Rides](Resources/Total_Rides.png)

#### Additional analysis
In addition, we took a look at a segment of data produced across 4 months: January 1, 2019 through April 29, 2019. This data was then plotted onto a multi-line chart with results per week.

Our multi-line chart is below:
![Plot](Resources/Plot.png)

#### Results
The different city types display very different data:
- While urban cities lead with the most amount of rides and the greatest fare collected overall, the cost of each ride and salary to the driver is far less.
- While rural cities have the least amount of rides and the lowest fare collected overall, the cost of each ride and salary to the driver is the highest.
- Suburban cities are right in the middle of all of the data: not the highest number of rides, nor lowest; not the highest number of drivers nor lowest; not the highest cost of fare and salary to the driver, nor lowest.

#### Business Recommendations
While it is evident that the cost of fares declines with the number of rides and drivers in the type of city, we may still be missing some measurements that may answer why this is the case. Why do urban cities collect more total fare while the cost of each ride is less and the salary to, why rural cities collect the least total fare while the cost of each ride is more, etc.. To do this, we can take a look at:
1. The number of cities per type
2. The length of each trip
3. The time of year when more trips take place
4. Whether certain cities skew the data by having very few and very many rides; very inexpensive or very expensive rides, etc.

In addition, it would be valuable to know what sort of information V. Isualize is looking for: does she want a proposal to increase ridership, one that lowers the cost of fare for customers, one th? 
