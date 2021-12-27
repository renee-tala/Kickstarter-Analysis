# Kickstarter-Analysis
Overview of Project

Performing analysis on kickstarter data to uncover trends

Purpose

  This analysis focused on Kickstarter funded plays. Looking at the outcome based on the launch date of the campaign and the outcome based on the fundraising goals, we can see if there is a difference in the success of the Kickstarter. With this information we can understand how Louise’s play Fever reached its goals. 
	
 Analysis and Challenges
 
  Analysis of Outcomes Based on Launch Data
	
	Using Excel, I created a pivot table with data from the Kickstarter file. I had to separate the data focusing on 'Years' and the 'Parent Category', being Theater. With that information, I further categorized it into Successful, Failed, and Canceled Kickstarters. Finally, I adjusted the pivot table to show the data by the months. Afterwards, I created a line chart to better show the outcome. 
	
	I had no challenges completing this part of the analysis. I did play around with the pivot table when I was categorizing the data by outcomes and counts. Determining which was the x- and y-axis. I'm sure if I had put the information in the wrong category the results would have been different. 
	
  Analysis of Outcomes Based on Goals
	
	
Using the COUNTIFS function, I created a chart based on the monetary goal of the campaign. It’s separated by $5000 increments. Just like the Launch Date data, it’s categorized    by Successful, Failed, and Canceled campaigns. The greatest challenge with this was the COUNTIFS function. The formula worked for the successful column and the canceled column, but would not return the results from the failed column. It showed most of them as zero. (Image attached)


		<img width="948" alt="countifs" src="https://user-images.githubusercontent.com/95507893/147435307-83f631ad-e30c-4aaa-a94f-c5b160a8c8a9.png">
	
		
I knew this had to be wrong for two reasons: The image of the line chart on the assignment page showed values for the Failed column, and I checked the values in the Kickstarter sheet for Failed Kickstarters.
		
  This was the longest part of my project. I looked at every excel forum online I could find. I tried retyping the formula. I knew that it had to be right because it was the same formula as the ‘Successful’ column. The only difference was the “Failed’ outcome. I stepped away for a day and revisited it. I had been using the “Pledged” column instead of the “Goal” column. Something so simple skewed the results of my whole analysis. 
	

	
Results


  What are two conclusions you can draw about the Outcomes based on Launch Date?
	
 The launch date of Theatre Kickstarter’s has an affected on how successful they will be. The most successful Kickstarter’s launched in May, June, and July. Although there was still a high number of cancellations during that time, it was roughly half of the number of successful Kickstarters. There are more successful Kickstarters than failed or canceled ones, which suggests that launch date isn’t the only factor in their success. We also see that approximately the same number of Kickstarters are canceled every        month, which leads us to conclude once again, that launch date doesn’t determine success. 
    
  What can you conclude about the Outcomes based on Goals?
	
	The most successful Kickstarters had fundraising goals of less than $10,000. That being said, there were far more projects with goals of less than $10,000 so that result is not surprising. We can conclude that projects that have a goal between $1,000 and $4,999 will be the most successful. 
    
  What are some limitations of this dataset?
	
The dataset only shows the years 2014-2016, so it’s outdated. We have a limited amount of information. We aren’t looking at the full dataset for the analysis. Did these    Kickstarters fail because of a small number of backers? Could cancellation have been prevented? There are several factors that determine outcome of fundraisers. Spreadsheets also  have quantitative data. How can we quantify the qualitative data, such as whether the play was relatable? Outside factors, like the US election in 2016 could have affected the success or failure of the plays. Were the screenplays controversial topics that no one wanted to support? Datasets are always going to be limited. There is bias in data collection, no matter how data analysts work to reduce it. 
      
  What are some other possible tables and/or graphs that we could create?
	
	We could use a stacked bar chart to get a better visual of the percentages of the Outcomes Based on Goals. Rather than looking at a line chart, we can view the ratio of failed to successful campaigns. 
	
	
	<img width="270" alt="Outcomes_Goals_Stacked" src="https://user-images.githubusercontent.com/95507893/147435286-7b0c4d62-f081-4e08-bff7-caf23db725b9.png">
	
	
