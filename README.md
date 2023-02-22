# bikeshare

## Overview
Our company is considering open a bike rental service in Des Moines, IA, similar to citibike in New York City. We are condunting an analysis of bike trips in New York during the month of August 2019 to help determine whether or not the service has potential for Des Moines.

[link to dashboard](https://public.tableau.com/app/profile/matthew.zabriskie/viz/bikeshare_challenge_16764313438410/CitibikeAnalysis?publish=yes "link to dashboard")


## Results

### Trip Duration

![](https://github.com/mzabrisk/bikeshare/blob/807fb6189d0af31075cc30bbc1ff56e4f9beccf1/images/checkout_duration.png)

Examining average trip duration, we saw that the vast majority of users use the bikes for <20 minutes at a time. This holds true for males and females, however users of unknown gender use the bikes for a slightly longer duration - the likely difference here is due to them being non-subscribers.

### Use by Day and Hour

![](https://github.com/mzabrisk/bikeshare/blob/807fb6189d0af31075cc30bbc1ff56e4f9beccf1/images/peak_use.png)

Examining a heatmap showing peak use by day and hour, it appears that for Monday-Friday, use peaks during the commuting hours. Use is more consistent throughout the day (at least during daylight hours) on the weekends.

### Use by Day, Hour, and Gender

![](https://github.com/mzabrisk/bikeshare/blob/807fb6189d0af31075cc30bbc1ff56e4f9beccf1/images/peak_use_gender.png)

Examining the same heatmap, but broken out by gender, it shows that use pattern is similar between males and females. However, users of unknown gender use the service more on the weekends and in the evenings.

### User Type and Use Pattern

![](https://github.com/mzabrisk/bikeshare/blob/807fb6189d0af31075cc30bbc1ff56e4f9beccf1/images/use_by_weekday_gender_user.png)

Examining another heatmap showing use by gender by day of the week, the main take away is that essentially all users with unknown gender are non-subscribers.

### Top Ending and Starting Locations

![](https://github.com/mzabrisk/bikeshare/blob/807fb6189d0af31075cc30bbc1ff56e4f9beccf1/images/top_locations.png)

To campare the top starting and ending points the maps from the module, with point size and color indicating level of use, were placed side by side. Doing so does a fairly effective job, but the graphic takes a lot of back and forth to compare and you can never be certain the exact same stations are being compared. To make it easier to compare the same start and end locations, heatmaps sorted by the most used stations were generated:

![](https://github.com/mzabrisk/bikeshare/blob/18e0357bfda1e6d8e766e051b71d80284a9580a5/images/start_end_heatmap.png)

The top 6 starting and ending locations are identical, and there is little variation in the order past the top 6. This indicates that minimal infrastructure is needed for relocating bikes to popular start or end locations.


## Summary

Based on our analysis, there are a few key takeaways:
- the largest user group are males.
- peak use appears to be during commuting hours.
- most users are subscribers.
- non-subscribers appear to use the bikes for a longer duration and predominantly on weekends.
- the most popular start and end locations are the same.

Some useful additional analyses would be: 
- A use duration graphic showing the use by user type (i.e. subscriber vs. non-subscriber). There is evidence that users of unknown gender are synonymous with non-subscribers, but more concrete evidence would be useful.
- A more indepth look at the non-subscriber use, particularly a heat map showing use by day and hour, but without subscribers included in the analysis since in NYC, they greatly outnumber the non-subscribers and the data as hard to see.
- More information about pricing structure would be needed, but an analysis showing revenue by user type per use would be helpful to determine whether moving into to Des Moines makes sense. It's highly likely that users in the midwest are less likely to commute via bicycle than New Yorkers, so there will likely be a higher percentage of non-subscribers, with less routine use. Knowing how user type effects revenue is necessary information.




Further analysis of Des Moines would be required before setting up a comparable bikeshare program. Key information would be knowledge about dense starting and ending areas:
    - are there locations where many people work within a small radius and thus a few stations could serve many?
    - are there locations where many people live, or would otherwise start a bike commute within a small radius? In NYC, these could be close to appartment buildings, or even subway stations. Are there similar places in Des Moines? Are Iowans likely to commute via bicycle, or will we be depending on non-commuter use?