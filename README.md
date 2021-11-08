# An Analysis of Kickstarter Campaigns
Performing analysis on kickstarter dataset to uncover trends in a successful campaigns launched.
## Project Overview
A playwright Louise wants to start a fundrising campaign to fund her play "Fever". She is estimating a budget of over 10000USD. Louise’s play came close to its fundraising goal in a short amount of time. And now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals.
### Purpose
The purpose of the project is to help Louise determine whether there are specific factors that make the project campaign successful.
## Analysis and Challenges
We use excel to organize, sort and analyze crowdfunding data to find out if there is a correlation between the outcome of the campaigns and the date when they were launghed.
Also, if the amount of funding goals set had any impact on the campaigns to be successful or not.
### Analysis of Outcomes Based on Launch Date
[https://github.com/Cryptotwister/Kickstarter-Analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png].
By creating a pivot table and using the line chart to visualize the outcomes based on launch date, we can determine that:
1. The best month to launch a successful campaign is May, followed by June and July. However, by the year-end success fate fells dramatically.
2. The worst time to launch a play campaign is December, since it has the lowest success rate and quite high failure rate.
### Analysis of Outcomes Based on Goals
[https://github.com/Cryptotwister/Kickstarter-Analysis/blob/main/resources/Outcomes_vs_Goals.png].
To be able to analyze the correlation between funding goals and campaigns outcome we used a countifs formula to break down the number of outcomes for "plays" with goals ranging from less than 1000 USD to more than 50000 USD. To visualize the results we used a line chart. We establish, that:
1. The success persentage of around 70 is for plays with funding goals of less than 5000 USD and 35000 to 45000 USD.
2. For the goals range of 10000 to 15000 USD the success rate is only slightly above 50%.
## Results
### Conclusions on Outcomes based on Launch Date
1. The worst time is October and December.
2. The best time to launch the Play is May, June and July. Therefore, we recommend to launch a play during summere months.
### Conclusion on Outcomes based on Goals?
1. For Louise's goal of above 10000 USD the success rate is about 55%. It is noticible that bringing down the amount of funding needed increases the chances for the play to be successful.
### Limitations of this dataset
The dataset provided does not give us the understanding of the demographics  of the backers to be able to target the audience needed, which could definitely increase the chances for the play to succeed.
### Some other possible tables and graphs that we could create
Subcategory of Outcomes chart gives us the idea of the success of plays comparing to others. As well as the success of "Theater" as the Parent category also overperforms the counterparts.
![Subcategory Outcomes](https://user-images.githubusercontent.com/42978221/140676390-02a958f2-fc44-4823-a75f-76bb15a42266.png)
![Parent Category Outcomes](https://user-images.githubusercontent.com/42978221/140676861-4506ca21-b30e-4243-9924-bd409099a7f7.png)
