# Ford GoBike

## by Mohamed Gouda

## data source
[Ford GoBike Boston] (https://s3.amazonaws.com/hubway-data/index.html)

## Introduction

> In this project we will try to look at data from Ford GoBike system.
>- At first, let's introduce the main features of our data. The data contains information about Boston, US from 2017 to 2020.
>- We made this data by collecting the data of each month from 2017 to 2020, and made them in a one data frame, in order to get some useful insights.
> The data contains the following columns, and these are their description according to their [website](https://www.bluebikes.com/system-data):
>>- Trip Duration (seconds) : the data has been processed to remove trips that are taken by staff as they service and inspect the system; and any trips that were below 60 seconds in length (potentially false starts or users trying to re-dock a bike to ensure it was secure).
>>- Start Time and Date
>>- Stop Time and Date
>>- Start Station Name & ID
>>- End Station Name & ID
>>- Bike ID
>>- User Type (Casual = Single Trip or Day Pass user; Member = Annual or Monthly Member)
>>- Birth Year
>>- Gender, self-reported by member (Zero=unknown; 1=male; 2=female)

> We are going to explore the data features through six sections. Each section contains one or more variable that we think it would be useful for our analysis, and these sections are:

>> Sec 1: Start Time
>>>- In this section, we are going to look through variables associated with the start time of the trip as days of the week and months. 
>>>- We will look through the distribution of trips along days and months, and then compare their average trip duration in minutes. 

>> Sec 2: Start & End Stations
>>>- In this section, we will go through start and end stations to know the top 5 start and end stations, and compare the average trip duration associated with these stations.

>> Sec 3: Gender
>>>- In this section, we will go through gender variable to see gender distribution, and what percentage of each gender there are.
>>>- We will also look through the average trip duration associated with each gender and different days of the week.

>> Sec 4: User Type
>>>- In this section, we will go through user type variable to see users distribution, and what percentage of customers and subscribers there are.
>>>- We will also look through the average trip duration associated with each user type and different days of the week.

>> Sec 5: Birth Year
>>>- In this section, we will go through birth year variable, and try to figure out the top 10 birth years associated with users that use Ford GoBike, and the average trip duration associated with each.
>>>- We will also compare those top 10 birth years with gender and user type, and see their average trip duration to try to get some useful insights.

>> Sec 6: Business Development
>>>- In this section, we will try to see how the business of Ford GoBike was doing from 2017 to 2020, and how was it affected by (COVID-19) during 2020.

## Conclusions

> To summarize the whole story, we looked at data of Ford GoBike for Boston, US from 2017 to 2020, and we studied our data through six main sections:

>> Sec 1: Start Time
>>>- In this section, we looked at data variables associated with the start time of the trip, and this provided us with some useful insights such as most trips were done in weekdays not weekends, but the average trip duration in weekends were higher.
>>>- We also found that most trips were done in summer and the first half of fall, and the average trip duration is also higher in summer.

>> Sec 2: Start & End Stations
>>> In this section, we looked at the top 5 start and end stations, and the average trip duration associated with them, and we found that the top 3 start and end stations were the same, and many of the top 5 were in 'MIT'.

>> Sec 3: Gender
>>> In this section, we found that the majority of the users were males with about 75% while females tend to have higher average trip duration.

>> Sec 4: User Type 
>>>- In this section, we looked through user type variable to see the percentage of subscribers and customers, and we found that about 92% of the users were subscribers which is a really high percentage. 
>>>- We also found that customers tend too have much higher average trip duration rate than subscribers.

>> Sec 5: Birth Year
>>> In this section, we looked at the different birth years of users and got the top 10 of them, and we found that all of these years range from 1987 to 1996 with users who were born in 1992 were the most ones to use Ford GoBike while those who weer born in 1988 have the highest average trip duration.

>> Sec 6: Business Development
>>> In this section, we looked at the growth of the business of Ford GoBike at Boston from 2017 to 2020, and how it was affected by (COVID-19) during 2020, and we found that the business was growing quickly year after year, but it was deeply affected by (COVID-19) during 2020 that it achieved much lower trips rate.

> Concerning the limitations that we have faced during our analysis, and things that could go in a better way 
>>- We could compare data from other cities and compare these different variables together for each different city.
>>- We could go more with our analysis to go more with things like the percentage of subscribers and customers over years, the most popular start and end stations over years and much more.
>>- We could also look deeper into outliers like trip duration outliers, and to inspect it with more detail, but for such large amount of data, and for the purposes of our analysis, we thought it would be better if we don't.

> At this stage, we came to the end of this analysis. We could go more and more, but for me and for today, I will call it a day, and wait till another day.