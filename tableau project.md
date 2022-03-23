# Insight 1:
### Links :
[problem of delayed and cancelled air flight | Tableau Public](https://public.tableau.com/app/profile/ismail.mohamed3378/viz/problemofdelayedandcancelledairflight/problemofdelayedandcancelledairflight?publish=yes)
### Summary:
 This dashboard introduces the problem of flight delays and 
cancellations, through 3 chart that give us impression about the volume of 
the problem.
One pie chart represents percentage of flights which has delayed minutes 
That give us insight to how much the problem is.
Second pie chart represents number of cancelled flights across US 
Which is large number cause big loses.
Third chart is a side bi side chart to compare the average minutes of delay 
arrival vs those of early arrival for each airline company , here appear the 
large difference that help focus on the problem
### Design: 
 in the this dashboard I use 2 types of charts , pie and side bi side 
charts , with color away from red-green palate , removing all junks and 
unneeded data from the charts to increase the data-ink ratio ,highlighting 
only helpful data that deliver the idea and hide the data I don’t focus on 
specially in pie charts , and I put some extra data in the tooltip that help , use 
aliases , use a calculated field to filter on the data I want to work with as I
separate the delayed flights from the non-delayed ones by if-condition , and I 
use absolute value to bring delay and early minutes to the same axis in the 
bar chart also use nested sorting to sort depending on the minutes of delay
I don’t remove the minutes axis , I see that it’s better to leave it
### Resources: N/A




# Insight 2:
### Links : 
[cancellation reasons | Tableau Public](https://public.tableau.com/app/profile/ismail.mohamed3378/viz/cancellationreasons_16471612920210/cancellationreasonsnumbers?publish=yes)
### Summary:
In this dashboard I show the most common reasons that cause 
airflights cancellation vs the number of cancelled flights due to each reason ,
I use a dynamic charts that show the total and individual numbers of 
different cancellation reasons related to each airline company.
First bar chart shows the total number of cancellation as well as the 
numbers related to each airline vs the reason of cancellation, 
On the map I show the distribution of these cancellation numbers across 
different states ,
The last bar chart shows the cancelled flights number related to each airline 
company 
Weather is main reason for flights cancellation
### Design: 
 in the this dashboard I use 2 types of charts , 
two bar charts and 1 map
I use the second bar chart as a filter by adding filter action so wen we select 
any bar related to specific airline company the , the map and the top bar 
chart show only the number related to this airline ,
I add the no. of delayed flight in the tooltip, use appropriate color ,use labels 
instead of axis and I put a text note for the reviewers to use the bars as a 
filter 
### Resources: N/A


# Insight 3:
### Links : 
[cancellation vs delayed flights | Tableau Public](https://public.tableau.com/app/profile/ismail.mohamed3378/viz/cancellationvsdelayedflights/Sheet3?publish=yes)
### Summary:
 This is a scatter plot show the no. of cancelled flights vs no. of 
delayed flights in each origin airport.
There is a clear strong correlation that tell us that the airports having larger 
no. of delayed flights has the larger no. of cancelled flights 
### Design: 
I use a simple scatter plot with clear axis showing the trend line that 
show the correlation
### Resources: N/A