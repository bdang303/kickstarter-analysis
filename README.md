# Kickstarting with Excel

## Overview of Project
A dataset of Kickstarter crowdfunding events that contained various data elements was provided to provide insights on. These Kickstarter events occurred in various countries, spanned across multiple types and categories of events, as well as had varying outcomes. 

### Purpose
Louise is the owner of this dataset and is seeking help to better interpret all the data available from Kickstarter events that have occurred or are in progress. By further analyzing the data available, we’d be able to help Louise identify which categories of events are successful that she can focus on. In addition, we can also identify events that were not as successful based on the data provided. Following the analysis, we’d be able to summarize and provide key insights that Louise would be able to use to take action on.

## Analysis and Challenges
During the year, there were over 4,000 Kickstarter events with relevant data points to dig into. These 4,000 events spanned across 9 different categories, all of which had varying probabilities of success/failures based on metrics. 

### Analysis of Outcomes Based on Launch Date
The Kickstarter events that we had data available for was from the period of 2009 through 2017. One of the key data elements we had available was the “outcomes” of each of these events informing us whether or not these events were successful, failed, or cancelled. A key valuable insight that would help is to determine which months of the year were theater events more successful that others. Using pivot tables and charts, the outcomes of the trends over the months we displayed as ![Outcomes Based on Launch Date](https://github.com/bdang303/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
In addition to outcomes, another key metric available in the dataset were the goals (fundraising amount) that were set for each of these theater Kickstarter events. By breaking down the outcomes of events based on the dollar value goals set for each event, we could determine whether or not a lower or higher goal would influence the success of an event. Based on the data, the outcomes looked like ![Theater Outcomes Based on Goals](https://github.com/bdang303/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
As it would likely be challenging to provide insights on every single type of event, it would be a bit more efficient for us to focus on a single type to be able to provide more valuable conclusions. Thankfully, Louise noted that “plays” was a category of events that she was interested in learning more about.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 1) Every month, out of the total number of Kickstarter events held in that specific month, you’d have a higher number of successful events compared to failed events, which means a majority of events held have successful outcomes. 2) The summer months from May through August seem to have the highest number of successful events, also driven but the total number events held during this period. 

- What can you conclude about the Outcomes based on Goals? There seems to be a negative correlation between the probability of success, and goal amount. Meaning, the higher the goal is set for an event, the lower the probability for success would be for that event. 

- What are some limitations of this dataset? The data provided spanned from 2009 through 2017, however a good portion of the data was available from 2014 through 2016. 2017 had limited data for only 2 months, so would be great to see the outcomes of the entire year to provide a better year over year picture.

- What are some other possible tables and/or graphs that we could create? As the focus of the analysis was centered around the “theater” parent category, we could dive a layer deeper by analyzing the 3 subcategories within the “theater” categories to determine if there were any trends based on plays, musicals, or spaces.
![image](https://user-images.githubusercontent.com/93288351/147708785-35cb4837-e971-4233-a3f7-a08558218b83.png)

