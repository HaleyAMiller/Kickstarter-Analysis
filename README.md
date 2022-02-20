# Kickstarting with Excel

## Overview of Project

### Purpose
A local playwright Louise originally sought assistance in her goal to crowdfund a new play. To better understand trends, an analysis was performed on various metrics of data from the crowdfunding platform Kickstarter. By utilizing Excel Pivot Tables and Pivot Charts, the data was able to be transformed further to highlight tendencies. Upon analysis of data of similar Kickstarter campaigns, recommendations were made on how Louise could move forward to ensure a successful Kickstarter campaign for her play. While Louise did not quite reach her goal, she was able to raise most of her goal amount in a short period of time. Looking forward, Louise then asked for an exploration on how successful other Kickstarter campaigns were based on their launch dates and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
One important aspect of successful campaigns appeared to be the launch date of the campaign in relation to the type of campaign. For this, a Pivot Table was used to look at the relationship between month a campaign was launched in relation to the outcome of the campaign. A Pivot Chart was then used to simplify the data into a line graph for Louise to easily understand. The graph below shows the number of successful, failed, and canceled campaigns for all theater campaigns. As indicated in the figure below, the largest number of successful theater campaigns were launched in May, June, and July. Additionally, trends indicate that the later in the year the campaign is launched, the less successful it might be.

![Theater Outcomes by Launch Date](https://user-images.githubusercontent.com/99554642/154868121-143ab4e1-669b-49c1-bb06-48ab5cb5aa40.png)


### Analysis of Outcomes Based on Goals
Another significant element to the Kickstarter campaigns was the goal amount. For Louise to see the range of goal amounts as well as the outcome of the campaign, the data was organized using the COUNTIF function in Excel to show the number of plays for each outcome in goals. The goals were looked at in $5,000 dollar increments, beginning with campaigns with a goal of less than $1,000 and ending with campaigns with a goal of over $50,000. Then, the percentage of successful, failed, and canceled goals were calculated within each goal increment, which was then transformed into another line graph. Based on the line graph, it can be observed that goals within the ranges of $0-$19,999 and $35,000-$44,999 had a higher percent success rate than their failed counterparts. Likewise, Kickstarter campaigns with goals from $15,000-$34,999 and goals over $45,000 had a higher percent of failed outcomes than successful outcomes.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99554642/154868139-2f8f6b97-e17a-4110-9b58-b336d6e1b8b4.png)


### Challenges and Difficulties Encountered
One of the largest challenges with manipulating this data was ensuring the correct parameters were set when utilizing the COUNTIF function in excel, as setting the incorrect parameters within the function would have provided very skewed and incorrect data. Another challenge was using the correct filters on the Pivot Table for the outcomes based on launch date. Switching which parameters were in the particular filter tabs would make interpreting the data more confusing and might affect the results delivered to Louise.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the data and corresponding graph, theater campaigns had the highest rates of success in May, June, and July. The number of successful campaigns steeply declined the remaining months of the year. Additionally, while the number of failed campaigns stayed consistent over the course of the year, the ratio of failed campaigns to successful campaigns increased in the later months of the year. For Louise, one conclusion that can be drawn is that she might increase her chance at having a successful campaign if she launches her campaign in May, June, and July. Another conclusion for Louise is that she might have an increased chance at a failed campaign if she attempts to launch a campaign in December, November, and especially October.

- What can you conclude about the Outcomes based on Goals?

Looking at the graph for outcomes based on goals, there appears to be multiple spikes in successful campaigns. However, upon analysis of the actual number of successful campaigns, a significantly large portion of successful campaigns had the goal of less than $5,000. This information could assist Louise in future Kickstarter campaign as it would be advised that she would likely have more success in funding her play with a goal amount of less than $5,000.

- What are some limitations of this dataset?

One limitation of this data set is that all the data originates from one platform, Kickstarter. The platform Kickstarter might have different campaign success rates and trends for plays than other crowdfunding or fundraising sources. For example, platforms like Patreon of GoFundMe might have higher success rates for play fundraising. Moreover, other platforms might have more success with campaigns with higher campaign goals. Utilizing data from multiple sources could provide better insight inti making future fundraising efforts more successful for Louise.

- What are some other possible tables and/or graphs that we could create?

Some additional graphs that might be helpful to Louise would be a graph highlighting the relationship between outcomes and the length of campaign to see how campaign length might affect a campaign’s success. Another visualization that could be beneficial would be a chart depicting the number of backers along with the campaign outcomes to show how many backers Louise should aim to draw in for more successful fundraising campaigns.

