# Surfs Up with Pandas, Python, and SQL Alchemy 
## Overview
We have pitched in an idea to open a "Surf 'n Shake" shop in Oahu, HI. This shop will serve surfboards and ice cream to tourists and locals, and will also be our ticket to move to Oahu permanently. As we don't have enough savings to fully establish this on our own, we have reached out to a potential investor. W. Avy, our investor, had previously invested in a surf shop which unfortunately went out of business as W. Avy didn't take the weather into account. Because of that, W. Avy would like to see some solid weather data to help him decide whether this investment is worth it. We provided him a weather analysis: he would like to see the temperature trends in June and December to determine if Surf 'n Shake can be profitable all year around.
## Results
### June Temperatures:
![Capturejun](https://user-images.githubusercontent.com/92230478/145693968-ba6056da-c64a-42b0-b839-9cdc2dda8cc1.PNG)
* There are 1,700 temperature observations for June between 2010 and 2017 with an average temperature of 74.9 degrees F. The standard deviation is only 3.25, making Oahu's weather in June consistent.
### December Temperatures:
![deccccc](https://user-images.githubusercontent.com/92230478/145693971-1d8f9b74-180b-43d9-9e73-da455ffc03f0.PNG)
* There are 1,517 temperature observations for December, which could indicate that some dates are missing their recordings. However, it is still a large sample size and should be representative of the data we are looking for. The average temperature for the month is 71 degrees F, which is 3.9 degress less than the average for June. The standard deviation is about 3.75, making it 0.5 higher than June's.
### Overall Temperatures: 
* June and December are close in the average, maximum, and minimum temperatures. Overall, there is very low fluctuation in temperature between those two periods.
## Summary
The temperature trends in Oahu are quite similar in June and December. With an average temperature of 74.9 in June and 71 in December, there is only a 3.9 degree difference between the two. With this information, we can conclude that Oahu's temperature patterns remain steady throughout the year. June and December are both great months for our Surf 'n Shake shop to serve ice cream and surfboards to all our guests.

Although the temperatures remain consistent throughout the whole year, precipitation may not fall into the same category. This would impact the Surf 'n Shake shop's sustainablility. I would recommend performing a query that will provide a statistics summary of precipitation trends in June and December.

In addition, I would also suggest a query that compares the weather data between the stations that recorded the temperature observations. This will help us narrow down the areas of Oahu that have the best weather pattern. We can use that data to create a list of potential locations for our Surf 'n Shake shop.
