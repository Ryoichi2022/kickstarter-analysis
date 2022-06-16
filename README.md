Challenge 1
# kickstarter-analysis

## 1. Overview of Project
A playwright, Louise, is considering starting a crowdfunding campaign for her play, Fever. This analysis is performed to provide Louise with insights into a crowdfunding campaign and help her organize her own successfully. Based on Louise’s estimate, the budget will be over $10,000 for her play.

Expectation throughout the project is to determine whether there are specific factors that impact the result of the campaign. In addition, Louise expects to gain better understanding of crowdfunding campaign based on the analysis.

## 2. Analysis and Challenges
### i. Data Analyzed
The data contained 4114 campaigns launched between May 2009 and March 2017. The detail of each campaign included information such as name, blurb, goal and pledged amount, outcomes, country, launch date, deadline, parent category, and subcategory.

### ii. Description of Analysis Performed
As the analysis is expected to contribute to Louise’s successful campaign, and she tries to set the campaign to mirror other successful campaigns in the same category, the focus of the project was on crowdfunding campaign for plays, which is a subcategory under theater. The analysis consisted of the following steps: First, the data was summarized by parent category and subcategory, and then, outcomes were reviewed by launch date. In addition, outcomes were analyzed based on goal amount.

### iii. Challenges
The data volume was a challenge in the analysis, and there are many potential factors to be considered. In the analysis, launch date and goal amount were reviewed. However, country, as well as average donation that is calculated by dividing pledged amount by backers count, could be reviewed for further insights.


## 3. Results
### i. Theater Outcomes by Launch Date
#### More Successful Campaigns in Theater/Play Category
As is shown in the graph Parent Category Outcomes, the theater category is the most popular in all categories in the data. Under the category, there were 1393 campaigns, out of which 1066 campaigns were for plays based on the graph Subcategory Outcomes – Theater. Apparently in the graph, there were successful campaigns (694 campaigns) more than failed campaigns. 
 
![](https://github.com/Ryoichi2022/kickstarter-analysis/blob/main/Parent%20Category%20Outcomes.png)
![](https://github.com/Ryoichi2022/kickstarter-analysis/blob/main/Subcategory%20Outcomes%20-%20Theater.png)

### ii. Two Conclusions from Launch Date Analysis
To review campaigns under the theater category more closely, the data was summarized by Launch Date in the graph Theater Outcomes Based on Launch Date.
 
![](https://github.com/Ryoichi2022/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
 
* Higher Successful Rate in May and June - Based on the graph, it appears obvious that campaigns were more likely to be successful when they were launched in May or June. 166 campaigns were started in May, and 111 or 67% of these campaigns were concluded successfully. In the same way, out of 153 campaigns that were launched in June, 100 campaigns, or 65%, were successful. Also, both months are the most popular month to launch campaigns.

* Lower Successful Rate in December - To the contrary, December appears unfavorable to launch campaigns. According to the data, the number of campaigns launched in December was lower than any other months. In addition, the campaign’s success rate was the lowest in December (49%) of all the months in the year.

### iii. Goal as Success Factor of Campaign
Finally, 1047 terminated campaigns under the theater/plays category were analyzed by goal amount of campaigns. As shown in the Outcomes Base on Goal graph, success rate is higher than failed rate in campaigns with goal less than $15,000. It is also noted that 961 or 92% of the terminated campaigns under the theater/plays category were with campaign goal lower than $15,000. Considering Louise’s estimate budget ($10,000) for the play, the crowdfunding campaign goal is likely to be less that $15,000, and the goal amount could be one of the factors that impact the result of the campaign.
 
![](https://github.com/Ryoichi2022/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### iv. Limitation of Dataset
* Geographical Limitation - One of the limitations of the dataset is that the data mainly consists of campaigns in the United States and Great Britain. More specifically in the case of the theater/plays category, 985 of 1066 campaigns were from both countries. Therefore, the results will not necessarily apply in other areas.

* Variety in Campaign Goal - As mentioned in the Goal as Success Factor of Campaign section, most of the campaigns included in the dataset were campaigns with its goal below $15,000. If more data is collected on campaigns with higher goal amount, the conclusion will be reached differently.

### v. Other Possible Tables
As the data contained campaigns in the United States and Great Britain, a possible table will be created only with the campaign data in both countries. Also, blurb was outside of consideration in the analysis, but if there is a common word that could impact the result of the campaign, such analysis will be helpful in organizing a campaign.
