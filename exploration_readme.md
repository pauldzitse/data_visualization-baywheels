# Dataset Exploration Dataset Exploration: Baywheels
## by Paul Dzitse


## Dataset

In this project focus centered on acquiring and developing the techniques for data visualization within data analysis process.

To this end, I used 2.506.983 bike trips of the 2019 baywheels dataset. After data collection, cleaning and construction of new variables, I plot visualizations of the given data starting with univariate and moving finally multivariate analysis.


## Summary of Findings

There are two user groups in the dataset namely Customers and Subscribers, with Subscribers amounting to 80% of the dataset. Some interesting findings: bike trip distribution has right skewed distribution and distribution of trip duration after outliers has been removed using the Z-score of 5 standard deviation is bimodal.

I found out that Customers on average have 5 minutes longer trip durations as Subscribers. Furthermore Customers turn to be active at weekdays and on weekends as well. While Subscribers are only active on weekdays. During weekdays Customers and Subscriber to turn to have the same trip distribution within the rush hours with high traffic for both groups being 8:00 and 17:00 hours GMT. At the weekends though, Subscribers are inactive.

Furthermore, i noticed that the variable the end station also plays a vital part in the trip duration. Using the ten most top end stations The Embarcadero at Sansome St has longest trip duration and this observed in Customers user-type, who have an outlying trip duration towards this location.

## Key Insights for Presentation

- user-types are customers and Subscribers
- more than 80% of the data comprise Subscribers
- customer have on average 5 minutes longer trip duration as Subscribers
- third quartile of the Subscribers trip duration is just a little above the median of the  Customers bike trip distribution
- distribution of Subscribers trip duration is more skewed to the right
- Customers tend to use the bike services mostly at weekdays from 07:00 to 09:00 and 16:00 to 19:00 with heavy traffic at 08.00 and 17:00
- Customers use make bike trips on weekends between 10:00 and 16:00 GMT
- Subscribers use bikes only on weekdays between 05:00 and 09:00 as well as 15:00 to 19:00 hours with heavy traffic at 08:00 and 17:00 hours accordingly
- End destination of a bike trip is important for predicting bike usage and trip duration.
- The Embarcadero at Sansome St has the longest trip duration (about 30-40% higher) as compared with other destinations.
- Station's near to great tourist/recreation centers might be a contributing factors
