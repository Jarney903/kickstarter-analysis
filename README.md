# Kickstarting with Excel

## Overview of Project

### Purpose

####  The purpose of this project is to perform two independent analyses on the relationship between theater play Kickstarter campaign outcomes vs the launch date and campaign goal size. These analyses were performed to help provide insights for strategizing the campaign goal size and launch date for Louise’s play Fever.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### The analysis of Outcomes Based on Launch Date was performed by creating a pivot table of the number of successful, failed, and canceled campaigns for the theater category in the dataset available. This data was then visualized in a line graph to best determine the months with the most successful campaigns. See Figure 1 for results of the analysis graph

### Figure 1: Theater Outcomes Based on Launch Date
![Theater Outcomes Based on Launch Date](/assets/images/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

#### The analysis of Outcomes Based on Goals was performed by creating a data table with columns of successful, failed, and canceled theater campaigns organized by rows of the goal size. These rows were arranged by 10 increments of $4,999 from $1,000 to $49,999 respectively, with 2 additional rows capturing data from less than $1,000 to greater than $50,000. By organizing the data in this fashion, the incremental percentages of successful, failed, and canceled campaigns could be easily calculated and visualized in a line graph to determine the relationship between the goal size vs the percentages. See Figure 2 for results of the analysis graph. 

### Figure 2: Outcomes Based on Goals
![Outcomes Based on Goals](/assets/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

#### The main challenges encountered where in formatting Excel’s SUMIFS function to return values between (e.g., greater than and less than) two limits in the Outcomes Based on Goals analysis. This was overcome by inputting two SUMIFS functions for the lower and upper bounds, then taking the delta between the two functions respectively.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
#### Campaigns launched in May and June show the highest positive delta in successful vs failed campaigns.

#### Campaigns launched in December show the lowest delta in successful vs failed campaigns.

- What can you conclude about the Outcomes based on Goals?
#### Campaigns with goals from less than $1,000 to $5,000 and goals from $35,000 to $45,000 showed significantly increased percentage of success to that of failure.

- What are some limitations of this dataset?
#### A limit of this dataset is not being able to correlate the percentage of successful campaigns based on goal size with that of launch date. 

- What are some other possible tables and/or graphs that we could create?
#### A recommendation would be to correlate the percentage of successful campaigns based on goals size and launch date. This can be achieved by further breaking down the dataset by launch date and goals size. If the desired result is a successful campaign, a recommendation would be to trend the campaigns with goals from less than $1,000 to $5,000 and goals from $35,000 to $45,000 only with launch dates of May and June to determine is the success rate is even higher. 







