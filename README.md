# kickstarter-analysis
## Overview of Project:
This project involved utilizing various functions and principles in Excel to manipulate, aggregate and visualize campaign data. We utilized countifs, sum, pivot tables as well as charting. 
The main purpose of this project was to use our skills in Excel to analyze campaign data based on launch date. We were primarily interested in understanding various aspects of the campaign outcomes against their associated dates and goal. 

## Analysis and Challenges: 

=YEAR(O2),=MONTH(O2) and =TEXT(S2*29;"mmm")
1.	Raw Data Cleanse and Manipulation

 
2.	Pivot Table Creation
b.	Pulled Month Name into rows, Outcomes into columns, Outcomes into values and Category and Year were pulled into filters.
c.	We then applied the proper filters and generated a 2D line graph with markers to visualize the data.

3.	Data Aggregation and Visualization
a.	The 3rd step in the process was to create a new sheet and add the 8 required columns to hold our goal and aggregated data.
b.	Countifs was used to get the count of successful, failed and canceled campaigns based on the goal amount. 
c.	Sum function was used to get the total projects by goal amount.
d.	Simple division was used to calculate the percentage of successful, failed and canceled campaigns. 
e.	A 2D line chart with markers was then created to visualize our outcomes versus goals.

4.	Challenges
a.	The main challenge in this project would have been getting the 10-digit serial number in our raw data converted into a usable data for Excel.

![Outcame based on Goal](https://github.com/Zainab1979/kickstarter-analysis/blob/336afde9d85ffbcce46b160555a1fbde57db806c/Outcomes%20Based%20on%20Goal.png) 
![Theater outcame based on launch date](https://github.com/Zainab1979/kickstarter-analysis/blob/3d6ec4dd625d65100ca805f40ff0d6ab204f1a6f/Theater_outcames_vs_lunched.png) 
