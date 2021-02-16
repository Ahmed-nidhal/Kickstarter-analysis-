
# Kickstarting with Excel

## Overview of Project

### Purpose : this analysis will show different campaigns fared in relation to launch dates and funding goals.

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date : created a pivot table from the Kickstarter worksheet , The Pivot Table Can be found in [Theater Outcomes by Launch Date](https://github.com/Ahmed-nidhal/Kickstarter-analysis-/blob/main/Resources/pivot%20table%20(theater%20outcomes%20by%20launch%20date).PNG) sheet ,filtered the pivot table based on the Parent Category,the column in the Pivot filtered to show only the (Successful,failed and Canceled ) ,the ( Years ) column will show the (Data Ctreated Conversion) , added filters on the pivot table for the (parent category) and (years). the Parent Category felterd to show up only (Theater). added a row lables column that show the months of the year and the campaign outcomes are sorted from largest to smallest so the (shuccessful) column is become the first, the line chart Was created For the pivot table to show the relationship between the outcomes and launch month,  the line chart called (Theater Outcomes Based on Launch Date).

### Analysis of Outcomes Based on Goals: a new sheet Named (Outcomes Based on Goals) was created , that including the following columns (Goal,Number Successful,Number Failed,Number Canceled,Total Projects,Percentage Successful,Percentage Failed,Percentage Canceled) , the twelve Rows are showing the following (less than 1000,1000 to 4999,5000 to 9999,10000 to 14999,15000 to 19999,20000 to 24999,25000 to 29999,30000 to 34999,35000 to 39999,40000 to 44999,45000 to 49999,Greater than 50000)then used the (countifs) to populate the "Number Successful," "Number Failed," and "Number Canceled" columns, based on the project "outcome.and used the (sum) function on each row to add "Number Successful," "Number Failed," and "Number Canceled" columns to get the "Total Projects" column and get the (percentages of successful, failed, and canceled) by calculating the data from the "Total Projects" "Number Successful" "Number Failed" and "Number Canceled" columns and created a line chart that showing the goal amount ranges one the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.

### Challenges and Difficulties Encountered :the challenges in this project was with the line chart for (Outcomes Based on Goals) , found out that the line chart didn't match with the results for (Outcomes Based on Goals), had to make sure all the columns are listed correctly from (less than 1000 to greater than 50000) that way will get the graph matching with (Outcomes Based on Goals) sheet.

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date? 1.showing the number of successful , failed and canceled projects by month. 2. display the months of the years and campaign outcomes. 

### What can you conclude about the Outcomes based on Goals? got the percentage of successful, failed, and canceled projects for each row.

### What are some limitations of this dataset? none

### What are some other possible tables and/or graphs that we could create? could use the column graph.
