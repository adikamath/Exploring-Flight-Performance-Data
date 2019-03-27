{\rtf1\ansi\ansicpg1252\cocoartf1671\cocoasubrtf200
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 Title: Exploring US Flights Data\
Author: Aditya Kamath\
Data: US Domestic Flights Data 2008\
Link: http://stat-computing.org/dataexpo/2009/the-data.html\
\
Description: The aim of this exploratory data analysis is to use visualizations in order to understand the nature of the data and uncover any interesting observations/ trends in the data. The dataset in consideration contains data on all US domestic flights in the year 2008. The dataset is from the Bureau of Statistics Division of the U.S. Department Of Transportation. It contains data on some performance measures of every domestic flight operated by large airlines/ carriers. Below are the main findings from the analysis.\
\
Finding 1: Top US Airports By Volume- In the year 2008, Atlanta Hartsfield-Jackson(ATL), Chicago O\'92Hare (ORD) and Dallas Fort-Worth (DFW) airports were the busiest airports together handling a combined volume of over 2.1 million flights. Some feature engineering was used to create a new feature called Total Flights which was calculated using the Origin and Destination data for each flight and plotted as a Barplot.\
\
Finding 2: Carriers/ Airlines With Most Number Of Flights- Next, I wanted to understand which airlines contributed to the highest domestic US air traffic in 2008. I found that Southwest Airlines, American Airlines and  Skywest Airlines were the top 3 airlines with respect to US domestic flights and handled a combined air traffic volume of nearly 2.4 million flights. This was again plotted using a bar chart.\
\
Finding 3: Airports Serving Most Number Of Destinations- It should be no surprise that again, Atlanta Hartsfield-Jackson(ATL), Chicago O\'92Hare (ORD) and Dallas Fort-Worth (DFW) airports were the top 3 airports that served the most number of destinations within the US. Atlanta Hartsfield-Jackson(ATL) was leading the charts with a total of 175 unique domestic destinations served. This is also plotted on a bar chart.\
\
Finding 4: Flight Distances Histogram- The mean flight distance is 726 miles with a median flight distance of 581 minutes. This analysis is a combination of calculating basic statistics, a box plot and a histogram. It is confirmed that the distribution of flight times is right skewed with several flights having very large flight times in excess of 2500 miles. This skew is caused by direct flights between airports on opposite coasts and even to and from Hawaii. \
\
Finding 5: Weather and Carrier Delays- Using feature engineering, we created a new feature called percentage of delayed flights to measure the percent of all flights delayed due to weather for each month in 2008 and another feature called percentage of delayed flights by carrier in 2008. The first insight gained (using a line plot) is that weather delays spikes to >3% in the month of December. Possibly due to winter-weather activity. There is also a smaller spike in the percentage of delayed flights in the middle of the year possibly due to rainy season in many parts of the US. Second, we found out that  carriers with codes- Hawaiian Airlines (HA), 9 Air Co. (AQ) and Frontier Airlines (F9) had the worst track records in delays at > 60% of their flights taking off later than scheduled.\
\
Finding 6: Late Flight Arrival Isn\'92t Dependent On Flight Distance: Using a scatter plot and a linear regression line, it was concluded that there is no strong evidence to prove a relationship solely between late flight arrival and flight distance. This is supported by the nearly flat linear regression line plotted on the chart.\
\
Conclusion and Next Steps: We noticed some interesting patterns in the data especially with respect to which airports are the busiest in terms of domestic traffic, which airlines have the worst performance in terms of delays and so on. In terms of next steps, it would be great to take a deeper dive into the data to create performance metrics for airlines based on the airports and create visualizations based on that. Another lacking insight in this report is how are the airlines performance metrics changing over the years? We have only considered 2008 data here and it would be good to look into this. }