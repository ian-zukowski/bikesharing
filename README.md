# bikesharing

[Link to Dashboard](https://public.tableau.com/app/profile/ian.zukowski/viz/Citibike_Analysis_16599734364970/CitiBikeAnalysis?publish=yes)

<!-- Overview of the analysis: Explain the purpose of this analysis. -->
## Overview of Project:
The company Citibike requires analysis of their provided services in New York City locations. The Tableau story linked above visualizes the Citibike data to describe bike usage based on Gender, Weekday, and Trip Duration data.

### Resources Used:
* Data Sources: NYC_Citibike_Challenge_Solved.csv
* Tableau Public: 2022.2.0 
* Jupyter Notebook: 6.4.8


<!-- Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image. -->
## Data Visualizations
[ian-zukowski](Resources/Readme_Images/story1.png)
* The most common time frames for bike use on weekdays are during the morning+afternoon commute. 
* The most common time frames for weekend bike use is between 9am-8pm
---
[ian-zukowski](Resources/Readme_Images/story2.png)
* The line chart shows the average checkout length is centered around 5 minutes for all users.
---
[ian-zukowski](Resources/Readme_Images/story3.png)
* The line chart shows the total amount of time a bike was checked out for, grouped by gender. The average time regardless of gender still appears to be ~5 minutes. 
* It is also important to note that male users comprise a significant portion of the customer base.
---
[ian-zukowski](Resources/Readme_Images/story4.png)
* For known genders the most common timeframe for bike usage is during morning+afternoon commutes on weekdays.
* However when filtering to only "UNKNOWN" gender the most common usage is during the weekend between the hours of 9am-8pm.
---
[ian-zukowski](Resources/Readme_Images/story6.png)
* The most popular days are Thursday and Friday which are majority Subscribers.
* Wednesday and Sunday are the least popular days. Sunday especially sees significantly lower usage from subscribers.
---
[ian-zukowski](Resources/Readme_Images/story5.png)
* The majority of users are subscribers who tend to use CitiBike services more on weekdays.
* However when filtering the heatmap to only show the 19% of customers who do not  have subscriptions, the vast majority of usage is on the weekend.
---
<!-- Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset. -->
## Summative Analysis
There are several takeaways that the company can get from this data. One key takeaway is that the majority (65-75%) of users are male. This knowledge could aid the marketing department in targeted ad initiatives that focus on masculinity or other features that have a higher likelihood of catering to the existing user base. It also could beg the question of why so few customers (25-35%) are female. Perhaps the company needs to spend resources reaching out to women to use their services more, or identify variables that are currently hindering women from using their services.

Another key statistic is that 81% of users are subscribers. This information on its own may not be as useful, but in conjuction with data about how subscribers use their services it can become quite powerful. Subscribers tend to use the bikes more often during the workweek, and it appears that usage during the work week is primarily during the morning/afternoon commutes. As such, most of the userbase appears to be using the services for purposes related to their work. Perhaps the company can invest resources and advertise themselves also as a means of traveling to lunch with colleagues during the day as well. This could mitigate the current low-volume zone seen during the week between 10am-3pm.

One final point to focus on is the significant drop in usage from subscribers on Sundays. It is the only day with under 200,000 subscriber rides. Or to put it better, there is a decrease of just over 83,000 rides from the average amount of subscribers per day. The company should discuss methods to increase ride usage of Sundays to align it closer to the average daily usage.