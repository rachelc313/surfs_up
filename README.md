# Surfs-Up Analysis

## Overview of the Analysis

"While on vacation in Hawaii last year, you discovered a newfound passion for surfing. You've been trying to create a plan that will let you not just return to Hawaii, but live there forever. You finally come up with an idea that you think is foolproof, a Surf and Shake shop serving surfboards and ice cream to locals, tourists, and of course, yourself.

You have some savings you're willing to invest, but we'll need some real investor backing to get this off the ground. So after putting together a strong business plan, you reach out to an investor, W. Avy, who is famous for his love of surfing. Your first meeting with him goes extremely well, but he has one concern, what about the weather?

He's extremely serious about this. He invested in a surf shop early in his career. However, he didn't ask for any weather analysis and that early venture was rained out of existence. W. Avy knows you've been learning how to properly analyze data and asks if you can run some analytics on a weather data set he has from the very island where you'd like to open your shop, the beautiful Awahoo."

An analysis was completed of the "hawaii.sqllite" file. The purpose of this analysis is the following:

1. Determine the number of temperatures measured for June and December.
2. Determine the average temperatures for June and December.
3. Determine the minimum and temperatures for June and December.

## Resources
 - Data Sources: hawaii.sqlite
 - Software: Jupyter Notebook, Python 3.7.13, Postgres SQL 11, pgAdmin4

## Results:
The analysis of the hawaii.sqllite data show that: 

 - The number of temperatures measured:
    - June: 1700
    - December: 1517
 - The average temperatures:
    - June: 74.94
    - December: 71.04
 - The minimum temperatures:
    - June: 64.00
    - December: 56.00

## Summary

There are 183 more temperatures measured in June than December. This variance should be looked into. The summary of each data set may be skewed. With that being said, the data shows that on average June is about three degrees warmer than December. If we assume that this data is accurate, it can be deduced that the temperatures in this location are typically "mild." The minimum temperature in June is twelve degrees warmer than the minimum temperature in December. Even so, the minimum temperature is still "mild" relative to other colder areas. Research could be done on what temperature is too cold for surfing and at what temperature do ice cream sales drop.

To further answer W. Avy's concerns, I would write a query that retrieves the precipitation data from the measurement table. I would use this and get the summary statistics for a brief analysis of the rain data. I would then create a table then subsequent DataFrame by writing a query to filter the precipitation data by month. I would then create a line graph to visualize the data. Since his earlier venture was rained out, he will want to know what the precipitation trends are for this location.

