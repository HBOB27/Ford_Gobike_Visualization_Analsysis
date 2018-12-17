# Ford GoBike
## by Hassan Ibrahim


## Dataset
> The data consists of information regarding 1,538,086 bike ride from Jun 2017 until July 2018. It contains some data that describes the rider  (date of birth, gender, and type) and others describing the ride (duration, bike ID, time, station..)
Data can be found on Gobike website https://www.fordgobike.com/system-data.

## Summary of Findings

> First i start with univariate exploration to see how the data looks like, and i found that most of the riders are male, and the age 30-35 states the highest number of riders as well as the rides were more during the weekdays comparing with the weekends with 2 peek times 8am and 5pm. Also subscribers were around 80% while customers 20%. I used the log transformation to get a clear view about the duration and it looks like normally distributed. Then i go deeper to see the relation between these variables, i found that the subscriber have more rides during the weekdays than weekends while customers have more rides over the weekend than the weekdays. The weekend rides tends to have higher duration than the weekday rides. Then i used the multivariate visuals to see deeper relations, and i found that customers have higher duration rides than the subscriber all over the week, and from those who stated their gender i found that females have higher duration rides than males through the week.


## Key Insights for Presentation

> First I start introducing the distribution of member gender and the member age that was skewed right were the riders start decreasing after age 35.
Then using the bivariate visualization i used a countplot to show the relation between the user type and day of the ride, where subscriber have higher rides during the weekdays than the weekends, while the customers have the opposite.
Finally I used the FacetGrid boxplot to show the relation between the ride duration and gender with user type the result was very clear that the customers have higher ride duration regardless the gender.