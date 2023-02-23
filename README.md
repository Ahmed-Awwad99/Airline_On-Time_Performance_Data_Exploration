# Airline On-Time Performance Data Exploration


## Dataset

The dataset containing attributes for approximately 21,000,000 flight report.This dataset reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from 2005 to 2007 The dataset can be found in the repository  [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7#),


## Summary of Findings

There are 21,706,733 flight report in the dataset with 11 features (cDate,Cancelled,CancelReason,TotalDelay,ArrDelay	DepDelay,ActualElapsedTime,OriginCity,DestCity,Diverted,Distance). some variables are numeric in nature like TotalDely Distance,... , and  the variables  DestCity, OriginCity,CancelReason are categorical ,also the variables cancelled and Diverted is boolean variables and finally the Date is datetime variable

the DestCity variable shows that Chiago has the most number of delyed flights, cancelled flights and also have the most vistied during all the cities

the data is almost nature maybe there are some weird outliers in some variable but it's still acceptable values, but for the countruction of the dataframe we did some cleaning process in order to be able to reduce the number of columns and that will will save more memory in it's turn.

the weather played a big role in cancelled flights as we saw the month january ,December, and febraury have the highest number of cancelled flights due to the bad weather also we found that the largest number of flights between two cities was between Chicago and New York also we see that the number on-ward flights is almost equal to the number of  return flights

Chicago is almost the highest of everything has the most number of flights to/from aslo have the highest number of cancelled and delayed flights also the long distances surprisingly tend to  be less cancelled or delayed also although Chicago has the highest number of cancelled flights it doesn't have the hightest cancellation ratio 


## Key Insights for Presentation

For the presentation, I focus on the top cities with the highest number of dealyed and cancelled flights also I tried to figure out the most common reason for most of delayed and cancelled flights also foucs on the distriubtion of the delay time 
also the distribution of the distance and total elapsed time finally I foucs on the change of the variables along that period from 2005 to 2007

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the violin plots of distance cancllation status. I'm only looking at
the top cities and the flights between them using a heatmap .I used the counter plot between the monthes and the number of cancelltaion to the effect of the weather in the flights cancellations also I used scatter plot to the the realation between the distance and elapsed time also the the effect of both arrival delay and deprature delay on the total elapsed time
