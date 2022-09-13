# Kickstarting with Excel

## Overview of Project

### Purpose
Our goal with this project was to analyze the information given in the spreadsheet and give our client useful feedback on the results of prior Kickstarter campaigns to help her make decisions about her aspirational own Kickstarter. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Performing an analysis on the data based on the time of year that each Kickstarter was introduced, we started by sorting the data to just the useful information, the Theater category. Then using our pivot table to sort out the data by month started, we were able to show the different rates of success throughout the year. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111708233/189954135-acc80af2-3621-43ab-85a8-1498224a70ba.png)
### Analysis of Outcomes Based on Goals
Similarly to the prior portion, we started by sorting out the data to have just what we need, using the "countifs" function in Excel to get our data on plays. Once we had it isolated, we were able to calculate percentages of success, failure, and canceled based on how high the goal of the original Kickstarter was, then give a helpful graphic to go along with it.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111708233/189954189-5e89e2d6-f0c8-4913-b042-04757647e801.png)
### Challenges and Difficulties Encountered
I encountered a few challenges, first with isolating the percentages to make the line chart without also having the total counts involved, but using the command click on mac solved that fairly quickly. Then a personal error in which I overlooked the category restriction had my data way too large and it looked entirely wrong, but with another look over my spreadsheet I was able to see the problem and fix it quickly.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
First, success seems to come easiest to theater Kickstarters introduced in the late spring, with May and June having the two highest success counts, with July follwing along that trend as well. Alternatively, there seems to be no meaningful trend with failed Kickstarters, as the count of failures hovers around the same number throughout the year.
- What can you conclude about the Outcomes based on Goals?
Under 20000 as a goal seems to give the best chance of success when compared to failure, as all the ranges under 20000 have a higher percentage of success than failure. We can easily tell our client that asking 45000 or more is dooming for the Kickstarter as the success rate is laughably low for those two ranges and would almost lead to certain failure. One interesting note is the large positive difference in success over failure in the range of 35000 to 44999 with over a 25% disparity in success and failure despite multiple ranges on the lower and upper end of this range having higher failure than success rate. This may be a range to target.
- What are some limitations of this dataset?
Some limitations overall may be the lack of information on where this money is coming from, as we know nothing about how it was raised or how our client can compare to these situations when it comes to supporting her Kickstarter. With more context of the situation of the person we are helping, we could certainly be even more helpful.
- What are some other possible tables and/or graphs that we could create?
One thing that would be really helpful would be looking at launch date success percentage instead of just the raw numbers, as seeing percent of success can give a different view than just the number of successes. 
