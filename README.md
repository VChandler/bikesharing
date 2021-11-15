# Bike Sharing Proposal
## Overview
New York City is a bustling city known for business and tourism.  One successful business has found a way to capitalize on helping people with getting around- Citibike.  Besides renting bikes for millions of trips around town and encouraging tourism, this concept also has the added benefit of being ecologically beneficial by encouraging exercise and reducing pollution.  This project explores some of the trends in New York City for this business, and what might be expected if the business were brought to Des Moines, Iowa.

The analysis consists of a series of data visualizations using Tableau.  These visualizations are based on data in New York City from August 2019, and is examined in several ways such as:
* Locations where trips began
* Type of user (subscriber vs. non-subscriber)
* And gender, among others.

Detailed results may be found in the Tableau Public workbook of visualizations [link to dashboard](https://public.tableau.com/app/profile/vince.chandler/viz/Module14Challenge_16369474813820/Story1)  

## Results
### Station Popularity  
![1](https://user-images.githubusercontent.com/88070999/141722341-af8c3ed5-a966-4b82-baae-c74cd6b212de.png)  
As expected, some stations were much more popular than others, especially clustered around the center of New York City where, presumably, tourism hotspots are most prevalent.  Though clusters of stations around tourism locations is paramount, accessibility throughout the city is critical as well.  This enables users to have more flexibility in destinations, tailored around hotels, local sights, and less popular locations for tourists.  
In addition, bike usage isn't solely limited to tourists, and should not be the sole factor in placing stations.

### Trip Start Times  
![2](https://user-images.githubusercontent.com/88070999/141722349-774697e2-006d-4772-bcd4-18ad1b4d6c3b.png)  
* There is a repeated pattern of start time during weekdays- usage from 6-9 AM, and again around 4-8 PM.  
* On weekends, as expected, times do not follow weekday rush hour times.  Activity is steady through Saturdays and Sundays starting around 8 AM and running until 9 PM.

### Duration of Trips  
![3](https://user-images.githubusercontent.com/88070999/141722353-a8bd03b9-baaf-48bd-a9c3-8fee96c099bd.png)  
Trip duration peakedin usage at around 5 minutes and drop dramatically after that.  There are very few trips lasting more than 60 minutes.  Some takeaways for implementation in Des Moines:
* Users are renting bikes for very short trips- to get from point A to point B in under 15 minutes.
* What incentives can be in place for users to rent the bikes for longer period of times?
* What are the roadblocks to longer rent times in the minds of users?

### Subscriber Breakdown  
![4](https://user-images.githubusercontent.com/88070999/141722357-abb9ba7c-0409-4322-a1f6-22c724fdf57d.png)  
In New York City:
* 80% of the bike users are subscribers
* 20% are one-off customers

Subscribers are clearly the largest market, and therefore the most focus should be on developing a solid base of subscribers in Des Moines along with incentives and rewards to keep their business.


### Gender Breakdown  
![5](https://user-images.githubusercontent.com/88070999/141722362-d7e4a0f7-577d-4d7c-a338-79b134bd48ce.png)
In New York, the majority of users are male- at least 65%, though possibly more due to about 10% of the genders as 'unknown.'  Undoubtedly, there can be differences in views of bike sharing between genders that can be further researched.  For example:
* Does one gender use bike rentals for different reasons than the other?
* Does one gender tend towards business vs. tourist destinations?
* Do gender views shape perceptions of the value received with bike rentals?

### Duration of Trips by Gender
![6](https://user-images.githubusercontent.com/88070999/141722370-c70be62b-635a-4813-8184-f4a91200793b.png)  
As seen in the earlier graph, regardless of gender, most trips are brief (under 15-20 minutes), with males making up the majority of the rentals.  Females had a peak of 6 minutes vs. 5 minutes for males.  Very few trips, relatively speaking, lasted more than 40 minutes.

### Trip Start Times by Gender
![7](https://user-images.githubusercontent.com/88070999/141722376-579c3410-98a6-4c03-9d7d-4552da957d73.png)  
Men and women exhibited very similar patterns of trip start times- around rush hour in the morning and evening during weekdays, and sustained usage throughout the day on weekends.  Differences in color above reflect the gender disparity with males being the heaviest users of bike rentals.

### Rental Days by Gender  
![8](https://user-images.githubusercontent.com/88070999/141722384-0d995be9-b141-4048-ae92-65fae09f6609.png)  
As expected, usage was heaviest, regardless of gender during the week and lighter on weekends.  However, interestingly enough, this particular visualization showed very light usage for both genders on Wednesday.  Further research may be needed to discover the reason for that and ways to counteract similar trends in Des Moines.

## Summary
### Overall
In New York City, men were the heaviest users of bike sharing.  Regardless of gender, most trips were very brief- under 15 minutes, with very few lasting more than 40 minutes.  Bike usage followed a predictable pattern matching rush hour during weekdays and sustained, day-long usage on weekends.  It is reasonble to expect similar trends with implementing a similar business model in Des Moines.  However, with further research, additional insights may be gained to counteract some of the less favorable trends seen in New York.

### Future Analysis  
As noted above, future analysis may examine a couple addition ideas:
* How can business be improved on Wednesdays, the lightest of weekday business?  A visualization showing the starting and stopping locations for Wednesdays ONLY, overlayed with popular tourist or business destinations, might be compared to a similar analysis for other days of the week.  External trends in those locations might indicate reasons for this particular finding.
* A visualization showing the locations of male vs. female bike stations may also hint at motivations for bike rentals and how genders may be viewing it different.  This could be paired with market research to better understand opinions between the genders on the business idea.
