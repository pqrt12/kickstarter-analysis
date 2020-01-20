# kickstarter-analysis
Performing analysis on Kickstarter data to uncover treads (module 1)

## An Analysis of Kickstarter Campaigns.

### Challenge
One excel file data-1-1-3-StarterBook.xlsx.zip and three image files onGoal.png, onGoal_1.png and onLaunchDate.png are uploaded for review. The downloaded original data set are kept in sheet "Kickstarter". 

1, Outcomes Based on Goals
Only campaigns with subcategory "play" are kept and the data is saved in the data sheet "KS-plays". 
To minimize typo, etc, a working sheet "wksh-on-goals" is created. The same function using "countifs()" is applied to the whole table, against campaign goals less than or equal to varying goals. Note, the last row has the maximum goal. 
The final sheet is "Outcomes Based on Goals", the analysis results are shown in image onGoal.png, or onGoal_1.png with additional overlaid project counts. 
Since not enough campaigns / projects with goals greater than $25000, no conclusions may be drawn for them. Otherwise, smaller goals tend to increase "successful" chance. Projects with goals around $10000, which is the budget of Louise's play Fever, the "successful" rate is about 50%. 

2, Outcomes Based on Launch Date
A pivot table and the chart is given in sheet "Outcomes Based on Launch Date".
The best time to launch a campaign is from May to August, and the worst time period is from October to December. 

3, Limitation and Improvement
To draw better conclusions, it would help if we could conduct studies on similar projects to Louise's play Fever.
The outcome "successful" / "failed" may be not a good metrics; instead, may be the absolute fund pledged is more important, regardless of the claimed goal. 
