# A Practical Analysis of Kickstarter Campaigns

## Overview of Kickstarter Analysis

### Purpose
This analysis of the Kickstarter campaign is to dileniate patterns and discover positive correlations of Successful campaign performance.   Based on a variety of statistical and qualitative values, including Failed and Canceled outcomes or categorical data, we aim to design meaningful data-driven insights through visulations of the best performing segments of the crowdfunding campaign. The data segmentations in A Practical Analysis of Kickstarter Campaigns focuses on the following quantitative values: # of Backers, $ value of Pledged, and $ value of Goal. Furthermore, metrics such as Percent Funded & Average Donations are represented to further evaluate Successes within Categories and Subcategories. We can uilize the updated datasets with tables & charts to stand as crowdfunding benchmarks for future analysis.

## Analysis and Challenges

![Kickstarter Formatting](MacintoshHD/Users/moezkhan/Desktop/Kickstarter_format.png)
---

I used several Excel tools and functions to further segment and analyze the dataset and reveal some positive corelations.  

- Select Columns for Conditional Formatting: 

	-Outcomes column conditional format to fill each cell with a corresponding color for Successful, Failed, & Canceled, as well as Live fundraising.

	-Percentage Funded column conditional format with a Color gradient, Red for smaller values and Blue for larger values.

- ROUND formula is implemented in a new column index labeled Average Donation.

- Insert Column:Text to Columns Wizard tool is used for two new columns containing Parent Category and Subcategory values. 

## Insert:Pivot Table & Newly Created Sheets: 
	
	- Pivot Table and Stacked Bar Chart to analyze Category Statistics. The table and chart display the count of campaigns successful, failed, canceled or live with the Country filter set to "US", we can see which Parent Categories yielded values. 

	- Pivot Table and Line Graph to visualize Theater Outcomes By Launch Date. The table and chart is a visualization of the Theater Outcomes, so we set a Parent Category filter to show only Outcomes from theater by launch month. 

	- Additional Table created to specifically view successful, live, and failed outcomes in the Subcategory "plays", and can further be filtered by country. 
		- Additional Table created to =VLOOKUP blurbs about the top performing "plays" in the UK. (deleted from Kickstarter_challenge.xlsx for Zip file space for Push onto GitHub/MoKmo176/kickstarter_analysis repository).

	
### Analysis of Outcomes Based on Launch Date

	- Pivot Table and Line Graph to visualize Theater Outcomes By Launch Date. The table and chart is a visualization of the Theater Outcomes, so we set a Parent Category filter to show only Outcomes from theater by launch month. 

### Analysis of Outcomes Based on Goals

	-  Outcomes Based on Goals created for analysing a table with =COUNTIF and =IFERROR functions in Excel. The formula =COUNTIFS references data of Pledge Goal versus Outcomes and counts only if in the rows category(<1000, 1000-4999, 5000-9999,...). The Percentage of Success, Failed and Canceled campaigns is represented in the table and line graph. 



### Challenges and Difficulties Encountered

The first challenge I encountered was with IFERROR and VLOOKUP, because the part of the logic that sets a decimal to a round number. Also, including a ROUND function with other functions was a challenge. The COUNTIFS were easy when I clear the filters for the data set. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	1. The peak for successful outcomes is May with 111 successful outcomes and June is the 2nd highest successful outcomes at 100. 

	2. There are more succeesful Outcomes than there are Failed or Cancelled outcomes, therefore the Launch Date is not a useful derterminent for campaign success. 


- What can you conclude about the Outcomes based on Goals?
	
	The lines in the graph [Outcomes Based on Goals](path/to/Outcomes_vs_Goals.png) intersect 3 times, we can determine where the peaks for Percentage Successful and Failed are based on various Goal amounts.

- What are some limitations of this dataset?

	The limitations may include no further financial data associated with the donations to further improve campaign budget allocations.  

- What are some other possible tables and/or graphs that we could create?

	A Table and Graph I would create would include average donation values by subcateogries, and dilineate a budget allocation analysis reccomendation. The data will give me a better picture of the most successful Subcategorys', we can further determine on the best performing margin-wise and decide where to allocate resources. 