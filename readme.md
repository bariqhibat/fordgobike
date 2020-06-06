# 2018 Ford GoBike Data Exploration and Visualization
## by Bariq Hibatullah Nurlis

## Dataset

[Bay Wheels](https://en.wikipedia.org/wiki/Bay_Wheels) (previously known as Ford GoBike) is a regional public bike sharing system in the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset I used is on [monthly basis](https://www.lyft.com/bikes/bay-wheels/system-data) from January 2018 to December 2018, it is already given in CSV format.

##### Data wrangling process:
- fix colums that are not in the correct data type, like start_time is an object, should've been a datetime
- filter out outliers in duration_sec from visual examination of the histogram
- add new columns of day of week in order to make more engaging graph


## Summary of Findings

The trips is at peak on 8-9am or 5-6pm everyday. We also find that the trips is mostly started on the weekday than weekends. Next, we find that the most trips started in September. Furthermore, we find that the average duration trips is affected by the user types. 


## Key Insights for Presentation

From this data, we find that the rider of our bike is mainly use the bike at 8-9am and 5-6pm, by that time, we find that this is used mainly for commuting to work. This statement is also supported by the graph that shows the decreasing use of the system from weekday to weekend. We also find that the most trips started in September, this might be because the weather feels nice on September, it is between Summer and Autumn. Furthermore, we find that the average duration trips is affected by the user types. Generally, the customer is using the bike longer than the subscriber. We speculate that this might be because the customer is the people who really need to use the bike everyday.