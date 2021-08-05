# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

---
## Overview of the Project
**The purpose** of the project is to help Louise understand the historical trends of crowdfunding campaigns, to set up her own crowdfunding campaign for to help fund her play, Fever.

### Background
Kickstarter, like other crowdfunding platforms, allows project creators to add incentives for different pledge amounts. We are helping Louise, an up and coming Playwright wants to start a crowd funding campaign to help fund her play, Fever. She estimated a budget of over $10,000, and is hesitant about juming into her first fundraising campaign. So, we are helping Lousie to set up her incentives, by using excel. we are using excel to organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a project's campaign successful. we'll use these insights to help louise plan her own and set it up for sucess. Using excel to analyze current site data, we'll help her gain a greater understanding of campaigns from start to finish, and we'll be able to set her campaign to mirror other successful ones in the same category. We'll help Louise kickstart her production by performing analysis on the kickstarter dataset to uncover trends. Excel will help us perform different type of calculations.

---
## Analysis and Challenges
1. The overview of the analysis is well described with screenshots (2 pt).
2. Challenges or difficulties that were encountered, and how they were overcome, are well explained. If there were no difficulties, describe any possible challenges or difficulties that could be encountered (2 pt).

Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, we are visualizing campaign outcomes based on thier launch dates and thier funding goals.

### Analysis of Outcomes Based on Launch Date
To help Louise plan her campaign timeline, we have to understand how campaign length might be tied to its outcome. More specifically, whether the length of a campaign makes a difference in determining its success. To understand this, we are performing analysis by correlating the lauch date with its outcome.  In order to do this, first, the Unix timestamps are converted to a more readable format day-month-year format. to understand more specifically, we have considered ***Theater*** category as it is more related to Louise's play ***Fever*** Using Pivot table and Pivot chart in excel the following visualozation has been generated.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85645485/128386305-227e870a-fc18-4c7e-a7e3-d95d1a829071.png)
We've discovered trends in the theater category with our Outcomes sheets. The month that launched the most successful Kickstarter campaigns was May. However, January, June, July and October all had roughly the same number of failed campaigns launched. Considering the failed, June seems to be a good month to launch a campaign!

### Analysis of Outcomes Based on Goals
We are helping Louise to set up her funding Goal amount, in order to be more successful. In order to do this, we have to understand the correlation between the Fund raised Goal and its success/failure. We are Using the Excel skills to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. For this, we have created the dollar-amount ranges so projects can be grouped based on their goal amount. we are using a new function, COUNTIFS(), to collect the outcome and goal data for the “plays” subcategory. Below is the line chart titled "Outcomes Based on Goal" generated to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85645485/128386298-1188f550-1b3c-4a2f-b098-4c654a2af1e0.png)

We can observe that *the lower is the goal amount, higher is the success rate*. But, if the goal amount ranges $15,000-$19,999 there is an exact 50% of success and failure, which can be ideal funding goal amount for Louise's play *Fever*.

### Challenges and Difficulties Encountered

The Kickstarter dataset has some extreme data points in the Goal/Pledged amount, which are outliers and are not representing the data we require to analze for Louise's Play. Identified the outliers by creating the Box and Whisker plot, which helped to locate the outliers in the dataset.

---
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The month that launched the most successful Kickstarter campaigns was May
  2. Considering the failed, June seems to be a good month to launch a campaign!
  
- What can you conclude about the Outcomes based on Goals?
  1. The lower is the goal amount, higher is the success rate
  2. Louise can set up her funding goal amount ranging $5,000-$15,000

- What are some limitations of this dataset?
  - The Kickstarter dataset has some extreme data points in the Goal/Pledged amount, which are outliers and are not representing the data we require to analze for Louise's Play.

- What are some other possible tables and/or graphs that we could create?
1. The below chart *Parent Category Outcomes* is generated to see which parent categories performed well and which ones did not.
![Parent_Category_Outcomes](https://user-images.githubusercontent.com/85645485/128386303-9ffd72ed-4993-4034-a551-bbdfcdc6bd7b.png)

2. The category outcomes can be analysed even more by using filters of different countries and also sub-categories. The following is one such visualization for Great Britan Catergory Outcomes.
![GB_Category_Outcomes](https://user-images.githubusercontent.com/85645485/128403245-f329c1f4-984e-453b-86a3-e22281b0bfb4.png)

3. Using the Kickstarter Dataset, we can calculate the mean, median, variance, and standard deviation using the statisctics formulae. The below table is one such exsple of descriptive statistics.
<img width="502" alt="Descriptive_Statistics" src="https://user-images.githubusercontent.com/85645485/128403242-0ef3210d-0145-415d-8cc7-5c354b806815.png">
---

>Thank you!😊
