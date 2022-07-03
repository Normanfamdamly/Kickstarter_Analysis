# Module 1 Challenge - Kickstarter Analysis for Louise
## Overview of Project
The project was to analyze the Kickstarter fundraising campaign Louise had been running, with an emphasis on the Theater and further focus on the Plays put on in the theater. Louise wanted to determine what the best time was to raise funds for the Theater and if there was a fundraiser goal amount that was more successful.  She could then use this information to be more directional in her future fundraising efforts in the future.
### Purpose
The purpose of this project was to learn how to analyze the data utilizing Excel techniques that include, but are not limited to:

	- Database Creation
	- Formula Creation
	- Conditional Formatting
	- Pivot Table Creation
	- Chart Creation
 ## Analysis and Challenges
  The analysis was completed through the data Louise kept on all of the Kickstarters ran from 2009 – 2017. The data had to be placed in to a usable format by decoding the Unix timestamp `=(((J2/60)/60)/24)+DATE(1970,1,1)`for both the launch date and deadline.  We added a few columns of calculated data that could be useful to our analysis, like percentage funded and subcategory. Then for ease of use we added some conditional formatting for a quick glance look at which projects were successful, live, canceled and failed and to highlight the more successfully funded projects by adding color to the sheet. The conditional formatting while technically easy for me can be difficult for me to see. I am partially color-blind and using the shaded heatmap for the percentage funded column, is a nightmare since I have trouble discerning the difference between shades. In the exercise we were to use a blue to a red heatmap and this is how it turned out. https://github.com/Normanfamdamly/Kickstarter_Analysis/blob/main/Conditional%20Formatting%20Example.png  I have learned due to my unique colorblindness and my teammate who has traditional red/green blindness my team works to show data without heatmaps and conditionally formatting as much as we can so has to no alienate other visually impaired people.  
   The remaining analysis of the challenge was not bad. I found most of the pivot table and calculations to be easy with the exception of the the COUNTIFS when you had a range of dollars. I did not want to use the hint in the Module Challenge either and tried searching for the answer in internet. The search was fruitless, since the term "Range" would pull in the range formula or everything but what I was looking for.  So when I finally watched the hint, I realized I was close by putting both range numbers in the formula, I was just not seperating them by the column range each time as the final code came out `=COUNTIFS(Kickstarter!D:D,">=1000",Kickstarter!F:F, "successful",Kickstarter!D:D,"<=4999",Kickstarter!R:R,"plays")`. 

### Analysis of Outcomes Based on Launch Date
The launch date analysis shows and overall success rate of about 65% and a 36% fail rate for theater fundraising. The most successful time frame for fundraising is spring and summer and then it falls off in the fall and winter. https://github.com/Normanfamdamly/Kickstarter_Analysis/blob/main/Theater_Outcomes_vs_Launch.png    
Except for a small blip in February, I think most fund raising for theater activities should be focused around the spring and summer seasons.  The least successful time for fundraising is the month of December, most likely due to the holidays and competition for other charitable donations.


### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
