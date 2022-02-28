# kickstarter-analysis
An Analysis of Kickstarter Campaigns

## Overview
	   
This analysis will detail different Kickstarter campaigns and how they fared in relation to their launch dates and funding goals. Our purpose is to determine if Kickstarter campaign outcomes vary based on launch date or their funding goal. Specifically, we will look to see if “theater” categorized campaign outcomes vary based on their launch dates as well as if the subcategory “plays” campaign outcomes vary depending on the campaign’s goal. The data we used covers Kickstarter campaigns across different countries and numerous categories from 2009 to 2017.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In order to perform our outcomes based on launch date we used a pivot table to detail the number of theater campaigns which were successful, failed, and canceled across different months of the year. To get this date we applied a basic unix conversion formula to get the original date the campaign was launched on from the original dataset and listed this under the Data Created Conversion column.  Once we had this information, we created a PivotChart to visually show the differences between outcomes based on what month of the year the campaign began in. 
  
### Analysis of Outcomes Based on Goals

To complete our analysis of outcomes based on funding goals, we first had to group the funding targets in order to best analyze the data. To do this we manually created the 12 categories of funding goals and used a formula to determine how many outcomes were successful, failed or were canceled in each of these funding categories. We then created a line chart to better display these results by showing the percentage of outcomes for each funding subcategory.   
  
### Challenges and Difficulties Encountered
	
One challenge encountered is that our analysis has a very limited scope looking at only theater campaigns (for launch date) and plays (for funding goals). This can be a hinderence to being able to accurately determine outcomes outside of the limited scope we set for ourselves. A second challenge encountered was properly separating and identifying the qualifications for the subcategories we created for our "Outcomes Based on Goals" sheet. It took me a long time to understand what the best way to create the ranges (1000 to 4999, etc.) and needed some assistance to complete the formulas correctly.

## Results

### Conclusions about the Outcomes based on Launch Date

#### Conclusion 1

The first conclusion we drew about theater outcomes based on launch date is that generally, the amount of failed campaigns will change similarily with the change in the amount of successful campaigns. This conclusion is supported by our line graph which shows that during 11 months when successful campaigns increase, so do the amount of failed campaigns. The only month which this isn't true is in November when failed campaigns increase by 4 and successful campaigns decrease by 19. 

#### Conclusion 2

Secondly we determined that theater categorized campaign’s have a higher rate of success in the months of May through July when compared to the rest of the year. This differs from the amount of failed and canceled campaigns which stayed relatively stable throughout the year. 

### Conclusions about the Outcomes based on Goals

While looking at the campaign outcomes based on their original funding goal’s we can see that as the funding goal is increased the rate of success will generally decline while the rate of failure will increase.

### Limitations of this dataset

The primary limitation of this dataset is the variance in all categories and subcategories. The data could show something that is completely different given one set of parameters (for example theater campaigns vs movie campaigns). 

### Other possible tables and/or graphs we could create
	
There are numerous other visual representations we could have used although I think the best would have to do with better separating the category information. Perhaps creating a bar graph detailing the successes and failures of various categories instead of focusing on the theater category we worked in.
