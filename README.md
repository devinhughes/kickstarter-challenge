#Kickstarter-analysis

##Understanding trends on Kickstarter Analysis data set

#Overview of Project
For this project we have been asked by Louise has asked us to help understand her play, Fever, outcomes. This project seeks to analyze how other campaigns have compared, in relation to their launch date, and fundraising goals. This will be used by Louise to understand her product better and give her the analytical data to help her succeed. We have been provided this data set that gives information about each campaign that Louise wants to study.

#Purpose
The purpose of this analysis is to create a visualization for Louis so that she can better understand various campaign trends. This will help Louise meet her fundraising goals. This project analyzes outcomes based on launch date and fundraising goals.

#Analysis and Challenges
Analysis of Outcomes Based on Launch Date
We conducted our analysis on the Kickstarter-Analysis dataset. This data was used to create a pivot table that, in turn, was used to create and display a line graph. As shown, we used theater outcomes based on launch date as a point of analysis. The pivot table was created from our data set and was filtered into the three values; categories, theater, and year. Each line represents the values of outcomes; successful, failed, and canceled. The rows represent each month that each campaign was launched. For our values we found the total counts the outcomes for each month. From the pivot table we were able to generate a line graph that gave us the results.
##Outcomes Based on Launch Date

#Analysis of Outcomes Based on Goals
We created a line chart to analyze each campaign outcome based on goals, which helps to visualize the trends. The first step was to filter through our data to differentiate different goal groups, each of which ranged between $5000. The function that we used was the CountIf() function, we found the total number of successful, failed, and canceled campaigns for each goal group. This data came from the original Kickstarter data set provided by Louise. The next step was to find the sum of the project for each goal group using the Sum() function. After those 2 steps were completed, we found the percentage of each campaign type for each goal group. We were then able to create our line graph with the results.  

##Outcomes Based on Goals

#Challenges and Difficulties Encountered
There were a lot of challenges that we could have been faced with. When creating this visualization it could be easy to make a mistake in formulas. Since the formulas are so particular a small error could be made causing an issue in the syntax. We would then need to find and fix this error. There is also the chance of missing some of the data which could render the whole project useless to Louise.

#Results
What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the line graphs, we can expect a more successful campaign if it is started towards the beginning of the year. We see a steady increase in the months between March and May. There is also a decline from June to December. This decline goes from June to September, picks up in October briefly, and then continues to decline through December. The conclusion is that September and November, do not have the best results for campaign launches. 
What can you conclude about the Outcomes based on Goals? 
The outcomes based on goals shows that campaigns that set lower goals are more likely to reach their goals. This is something that is fairly predictable as it is basically always easier to reach smaller goals than larger ones. The campaigns that had higher campaign goals were more likely to fail. These goals were likely too large to start which caused them to inevitably fail. Setting smaller budgets and goals for each campaign will provide a better chance of success.
#What are some limitations of this dataset? 
There are some limitations of this dataset. A large limitation is that only a small number of campaigns are represented. We don’t have much background information such as where these campaigns specifically took place. We cannot tell if these campaigns were run on a large scale, or small scale level. Were these campaigns national or only in a small area
#What are some other possible tables and/or graphs that we could create? 
We could also create a table that shows trends based on location if that was provided. A pivot table could be used to show us similar outcomes to our launch date or fundraising goals. If we were given geographical location we could see if there were different trends in different areas, or possibly even different demographics. Instead of showing both failed and successful campaigns, we could dive deeper into data and look at the trends within the failed campaigns and likewise with the successful campaigns. We could also analyze our outcomes based on length of campaign and how that would affect fundraising goals and donation amounts. 
