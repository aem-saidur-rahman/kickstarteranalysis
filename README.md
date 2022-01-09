# **Kickstarting with Excel**

## **Overview of Project**

Kickstarter is a successful crowdfunding service, however, only a third of its campaigns made it through the funding process with a positive outcome. Here we have analyzed over 4000 campaign data to identify the impact of different factors in a campaign’s success. Findings are presented using pivot tables and graphs to provide Louise (an up-and-coming playwright who wants to start a fundraising campaign to fund her play) with essential information briefly.

### **Purpose**

To provide necessary feedback to Louise which will help her set a realistic goal, timeline, and location for her next Kickstarter campaign, to raise for her upcoming play *Fever*, to be successful. Her estimated budget is 10,000$ +.

## **Analysis and Challenges**

This analysis considered multiples factors to support the stakeholder’s decision. Campaign outcomes based on launch date, goals, category, subcategory and Descriptive statistics (Mean, Median, Standard Deviation, Upper Quartile, Lower quartile and IQR of Goal and Pledged). Conditional formatting, CountIF, Pivot table were used during the analysis.

![](https://github.com/aem-saidur-rahman/kickstarteranalysis/blob/master/Resources/Parentcategory_outcomes.png)

                             Music,Theater and Film & Video are top 3 successful parent categories.
                    

![](https://github.com/aem-saidur-rahman/kickstarteranalysis/blob/master/Resources/Subcategory_outcome.png)

                             Plays is the most successful subcategory by far.




Although theater and plays graph as category and subcategory tells a very promising story but in descriptive statistics it showed Mean goal of successful us kickstarters is around 5000$, and mean goal of failed is over 10,000$. Louise probably needs to reconsider her ambition of 10,000+.



One challenge with the dataset was lack of recent data, since 2017 a lot has changed considering the current world scenario. More recent data might show some different outcomes. Since this is the latest data available so the recommendations should be made with this note to Louise.







### **Analysis of Outcomes Based on Launch Date**

![image](https://github.com/aem-saidur-rahman/kickstarteranalysis/blob/master/Resources/Theater_Outcomes_vs_Launch..png)
                                Theater Outcomes based on launch date showed some months have higher success rate than others.


### **Analysis of Outcomes Based on Goals**




![image](https://github.com/aem-saidur-rahman/kickstarteranalysis/blob/master/Resources/Outcomes_vs_Goals.png)


Goals below 5000$ has over 70% success rate



## **Results**

 **-What are two conclusions you can draw about the Outcomes based on Launch Date?**

•	April, May and June have a higher rate of success, good time to plan a launch.

•	October has the highest failed rate, this month should be avoided

**-What can you conclude about the Outcomes based on Goals?**

•	Goals below 5000$ has more than 70% success rate. Louise’s goal is 10,000$+, that range (10,000$-14,999$) has a success rate of 54% only, which is a concern

**-What are some limitations of this dataset?**

•	Dataset has 21 countries information, and each has its own goal and other numbers in respective currency. For further cross-country analysis, these numbers need to be converted into a common currency for better comparison.

•	Some of the categories/sub-categories don't have projects in all years/months, so there is no continuous relationship over the time.

 **-What are some other possible tables and/or graphs that we could create?**

 •	Number of backers per category, number of campaigns by year, number of plays by year, number of backers per country, and number of plays per country.


