# PyBer Analysis
## Challenge 5: Matplotlib
### Overview
#### Purpose
This challenge analysis was based on the results from merging two .csv files into one dataframe. The two files contained the following information:
1. City Data: this data included the names of cities, how many drivers are in each city, and the type of city: urban, suburban, and rural.
2. Rider Data: this data included a date and timestamp for each ride, the cost of each ride, a ride identification to distinguish each ride, and the city that the ride took place.
When merging this data together, we are able to analyze:
1. How many rides took place per city and the average amount of rides per city type
2. How many drivers there are per city and the average amount of drivers per city type
3. How much fare collected per city and the average fare per city type

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
While we are able to see averages by city type, we are missing some measurements that may produce even more accurate results, to inform us WHY urban cities collect more total fare while the cost of each ride is less, why rural cities collect the least total fare while the cost of each ride is more, etc. To do this, we can look at the following data points:
1. Number of cities per type. We are not looking at the data to see how many cities there are in 


