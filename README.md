# NYC_Citibike

## Purpose
The purpose of this analysis was to create visualizations using New York City Citibike data in order to better understand and illustrate key data points. 

## Results 

For this analysis we have 7 different visualizations:

### Trip Duration:

<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/checkout%20time.png)

</p>

We can see from our plot of trip duration that the most frequent duration is 5 minutes. We can also observe that almost all of the trips are less than an hour. 

### Trip Duration by Gender:

<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/checkout%20by%20gender.png)

</p>

When we break down trip duration by gender, we see much of the same. Male, Female, and Unknown genders all peak around the 5 minute duration mark. We can also see that there are far more males using Citibikes, denoted by the orange line.

It is clear from both of our trip duration graphs that the bulk of use for Citibikes in NYC is only for a short trip of usually around 5 minutes.

### Trips by Hour of the Week:

<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/Trips%20by%20Weekday%20hour.png)

</p>

This heatmap shows us the most popular usage times throughout the day, throughout the week. 

#### Monday-Friday: 
We can see that during the workweek, the most popular times are before 9am and after 5pm. This makes sense as most people are working 9am-5pm, thus only time before or after work to go for a bike ride, or they are using Citibike to commute to and from work.
We can also note that 5-6pm on wednesday has much less usage than the res of the week for that timeframe, and Thursday's seem to have much more usage during that timeframe.
#### Saturday - Sunday:

The weekend paints a much different picture than Monday-Friday. We see heavier usage from 10am-5pm during the weekend, and very sparce usage before 10am.

### Trips by Hour of the week (Gender):
<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/Trips%20by%20Weekday%20gender%20hour.png)

</p>

This heatmap is the result of splitting the last heatmap by gender. We see quite the same picture: heavy usage on workdays before 10am and after 5pm, and heavier usage on weekends after 10am and before 5/6pm. Another thing that stands out is once again the heavier usage from males.

### Usertypes:
<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/short%20term%20vs%20annual%20subs.png)

</p>

This simple pie graph shows us the proportion of users who have an annual subscription to Citibike and the short term users. We can see from the graph that about 80% of users are subscription holders.

### Average trip duration by Birth Year:
<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/average%20trip%20duration%20birth%20year.png)

</p>
This area graph shows the relationship between the average trip duration and birth year (age). As you can see, the data for users that are apparently born before 1940 is very volatile, and most liekly innacurate and shouldn't be considered in our analysis. It is likely some people entered their birth year incorrectly which gave us these values bfor birth years <1940. Looking past this, it is evident that as birth year increases so does theaverage trip duration. Meaning the younger the user the longer on average they ride for. 

### Trips by Gender by Day of the Week:
<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/user%20type%20trips%20by%20gender%20weekday.png)

</p>

This heatmap shows us the density of trips per day of the week, by gender and usertype. It is clear from first glance the heaviest usage comes from, firstly subscribers, and secondly males. 

## Summary:
In summation, we can gather a list of key points from our analysis and visualizations:

<li> The most frequent ride duration is 5 minutes </li>
<li> The most popular ride times from Mon-Fri are 6am-9am and 5pm-7pm</li>
<li> The most popular ride times for weekends are 11am-6pm</li>
<li> Citibike users are comprised of roughly 80% annual subscribers and 20% non subscribers</li>
<li> Thursdy and Friday are the busiest days for Citibike</li>

### Additional Visualizations:

An additional basic visualization that would helpful would be a simple bar chart showing the distribution of male and female Citibike users, for example:

<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/Gender%20Dist.png)

</p>


Another visualization hat would be helpful for future analysis would be a gender breakdown for usertype. This could be very useful in terms of advertising subscriptions.
for example: 
<p align="center"

![alttext](https://github.com/sd2wiebe/NYC_Citibike/blob/main/usertype%20by%20gender.png)
</p>

## [link to dashboard](https://public.tableau.com/app/profile/shawn.wiebe/viz/NYCCitibikeAnalysis_16230979095720/NYCCitibikeAnalysis)
