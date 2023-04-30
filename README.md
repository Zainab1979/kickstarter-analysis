# kickstarter-analysis
## Overview of Project:
This project involved utilizing various functions and principles in Excel to manipulate, aggregate and visualize campaign data. We utilized countifs, sum, pivot tables as well as charting. 
The main purpose of this project was to use our skills in Excel to analyze campaign data based on launch date. We were primarily interested in understanding various aspects of the campaign outcomes against their associated dates and goal. 

## Analysis and Challenges: 


	1. Raw Data Cleanse and Manipulation

	2. Pivot Table Creation

	![Outcame based on Goal](https://github.com/Zainab1979/kickstarter-analysis/blob/58cf0df9556704befbfadd95e06d385202182a14/outcames.png) 
	
	Pulled Month Name into rows, Outcomes into columns, Outcomes into values and Category and Year were pulled into filters.
	We then applied the proper filters and generated a 2D line graph with markers to visualize the data.
   
  
3.	Data Aggregation and Visualization
a.	The 3rd step in the process was to create a new sheet and add the 8 required columns to hold our goal and aggregated data.
b.	Countifs was used to get the count of successful, failed and canceled campaigns based on the goal amount. 
c.	Sum function was used to get the total projects by goal amount.
d.	Simple division was used to calculate the percentage of successful, failed and canceled campaigns. 
e.	A 2D line chart with markers was then created to visualize our outcomes versus goals.

4.	Challenges
a.	The main challenge in this project would have been getting the 10-digit serial number in our raw data converted into a usable data for Excel.

        ## Results
![Theater outcame]([https://github.com/Zainab1979/kickstarter-analysis/blob/58cf0df9556704befbfadd95e06d385202182a14/outcames.png)
1.	Theatre outcomes by launch date 
a.	The month that yielded the greatest number of successful campaigns was May. We had 111 successful campaigns that month. 
b.	The month that yielded the highest number of failed campaigns was also May. There were 52 failed campaigns that month. 
c.	This makes May our busiest time of the year for campaigns overall.
      
   ![Outcame based on Goal](https://github.com/Zainab1979/kickstarter-analysis/blob/336afde9d85ffbcce46b160555a1fbde57db806c/Outcomes%20Based%20on%20Goal.png) 

2.	Outcomes based on goals
a.	The number of successful campiagns trend downward as the goal increases up until you hit the 50,000 marker then total projects jumps up to a higher number. 
b.	Despite total projects spiking up at 50,000 the percentage successful is at its lowest at that goal amount. 


   ## Summary of Limitations
   One limitation of this data is that we do not have a code or reason for the failed and canceled campaigns. Having this data, we would be able to spot trends in        the reasoning in hopes of getting corrective measures in place to minimize our failed and canceled campaigns. 
   It would also be nice to have a “country” column based on the type of currency. We could then see where our opportunities and strengths lie for receiving            pledges based on geographical location.

