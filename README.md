# surfs_up
## Overview of the analysis:
Using Python, SQLAlchemy, and Flask, to analyze and visualize climate data as we prepare to partner with an investor to open a Surf & Shake shop in Oahu, Hawaii.
### Purpose
The purpose of this analysis was to generate summary statisics pertaining to the temperature in Oahu to determine if the weather conditions are sustainable enough to successfully open and run a Surf & Shake shop. To accomplish this task, we created and ran two separate queries for June and December and then stored the data into each of its own list to further create a dataframe. After creating the dataframe, we used the .describe() method to generate the summary statistics of the temperatures for June and December. 
## Results
**June Summary Statistics**

![D50DDEEB-C8E3-4D26-9476-48FA31730CF7_4_5005_c](https://user-images.githubusercontent.com/92240407/153554798-216c8f26-fe20-45cd-a478-3a802b2e31a2.jpeg)

**December Summary Statistics**

![401782A6-7DBF-47C6-8EF1-C6C606E04458_4_5005_c](https://user-images.githubusercontent.com/92240407/153554904-9b93b966-7e7e-4370-b3b0-764fb59bf46c.jpeg)

- Both months of the summary statistics reveal that whether if you are in Oahu in the winter or the summer, the average temperature remains in between 71-74(Fahrenheit) degrees. This further reveals how there is little to no flucation in temperature regardless of what season we are!
- The 25th percentile for the month of December is 69 degrees(F), while the 25th percentile for the month of June is 73 degrees(F) meaning that 25% of the temperatures for these months all lie below their respective degrees. These results further reveal how even during the winter month of December, only 25% of the temperatures for the month lie at or below 69 degrees(F), which still promises enough business for this cold rainy month! 
- The maximum temperatues for both months with completely different seasons reveals to be quite similar as the maximum temperature for June was 85 degrees(F) and for December 83 degrees(F), further supporting our plan to open a promising Surf & Shake shop in Oahu. 
## Summary
Overall, the months of June and December throughout the years in Oahu seem to have relatively similar temperatures with the average being between 71 degrees(F) to 74 degrees(F). From the other descriptive results listed in the summary statisitcs for both months, we can see that the difference between most results only varies by a couple degrees. The only one minor difference depicted in the results is that for June there were 1,700 data recordings for the temperature and 1,517 recordings for December, revealing about a 200 difference in count. Regardless of the difference in count, the other results from the analysis provide evidence that we will be successful in opening a Surf & Shake shop in Oahu which will attract business at any time of the year and further supports the idea of being able to turn the Surf & Shake shops into a franchise all around the different islands of Hawaii. 
### Additional Queries 
Two additional queries that I would perform to gather more weather data for June and December would be to run queries that generate descriptive summary statisics  based on the precipitation for both of those months. By comparing the precipitation summary statistics for June and December, we would be able to receive clairification on the levels of rainfall during the different months that may affect business for the shop.
