# Udacity_Data-Analyst-Course-project-3

I worked on USA Airline Data for 2008 from the Harvard Dataverse. The dataset can be found [Here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7) 


## Dataset

> The data consists of flight arrival and departure details for all commercial flights within the USA in the year 2008. 
It consist of `2389217` rows and `29` columns. There are `16` columns **(CancellationCode, CarrierDelay, WeatherDelay, NASDelay, SecurityDelay, LateAircraftDelay, ArrTime, ActualElapsedTime, CRSElapsedTime, AirTime, ArrDelay, TaxiIn, TaxiOut)** with missing data, but i dropped only `6` columns. This is because **the values with missing data i dropped is not no value in  my analysis while they rest columns i didn't drop is of value in my analysis and has less missing data**. Also, if i drop them it **will disrupt my analysis and i will loose important features**. For eg, **Diverted columns** has only `two distinct values` with no missing data data. If i had dropped the columns with less missing data, i will loose one of the distinct values in **Diverted** column.
Here are the questions i want to find answers to in my data explanatory analysis:
* Are there certain destination or arrival cities that are home to more delays or cancellations?
* What are the preferred times for flights to occur? Are there any changes over multiple years?


## Summary of Findings

> I worked on Airline data 2008 only this is because of how large the data is compared with my PC capacity. I worked with the following with features **Dest, Time Taken, CancellationCode, DepDelay, Origin, Cancelled and Month**. My data shape is 1804634 rows and 25 columns. My data explanation tells story of top 10 origin and destination cities, time difference (Time Taken) from when the airline left to arrival, months these trips takes place and the Delay time (mins) for each carrier. The preferred time from flight to occur is between the 3rd nd 4th month of the year because they have the shortest time taken (161.227787 mins for 3 month and 161.821381 for the forth month) for a flight to reach it destination.


## Key Insights for Presentation

> I worked on top 10 origin and destination cities. All had no records of cancellation but they experience delays for Destinations like 
**ORD** and **DTW** experienced more delays out of the top 10 while for Origin cities like **LAS** and **PHX** experienced more delays. Also the months when these trips takes place.
