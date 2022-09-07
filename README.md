# (Dataset Exploration 201902-fordgobike-tripdata)
## by (Peter Lemule)


## Dataset

> The dataset, 201902-fordgobike-tripdata.csv, is downloaded from Ford GoBike and licensed by Ford GoBike. This dataset includes 519,700 trips with 15 features such as locations, time, and user attributes. There are start and end stations. I noticed that most trips happen on the same stations, so I subset the datasetby choosing top 8 trips start stations with the most trips



## Summary of Findings

> Plotting the duration of trips using histogram shows that we need to scale. I apply log scaling to show to the plot which now shos that the duration of most trips are between 6 - 15 mins


> The rides across the week clearly shows that Thursday has the highest number of trips. Weekdays semms to be the most significant counts, while weekends (Saturday and Sunday) have the least counts

> The start stations and end stations have similar top records which is why it was added together and it was plotted in the graph to show the most top 10 most frequest places in San francisco

>The Bikers were splitted generations using their bith year after plotting it was observed that the millenials generation has the highest number i.e Bikers that are born between 1981 and 1996. The generation was gotten using birth_year

>Majority of the Bikers are subscribers, which can be seen from the  pie chart

>The hour of the day and the day of the week were extracted from the timestamp.

>From the boxplot for duration in Minutes in regards to Generation and User Type shows that it's the post customer usertype that has the least duration minutes and the post war subscribers have the Highest duration in Minutes

## Key Insights for Presentation

> From the data set, 8am and 9pm have the highest number of trips

> Customers have the lowest duration minutes while subscribers are the highest

> Majority of the Bikers are subscribers, which can be seen from the  pie chart

> Most bikers falls within the Millenials Generation that is they are born between 1981 and 1996