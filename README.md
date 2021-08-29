# Kickstarting with Excel

## Overview of Project

### Purpose
In the following analysis we will be evaluating data from Kickstarter projects across multiple countries based on their categories. This data includes goals, donations, backers, time lines, and the outcome for each project. Our desired result is to be able to identify differences of Kickstarter outcomes when compared to different variables of the provided data.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![alt text](https://github.com/HotMochaNoWhip/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
  
Analyzing the above data we can see the indivudal months in which a launched theater Kickstarter was either successful, failed, or canceled. We can see that some months tend to be more successful than others and overall it is more rare for a Kickstarter to be canceled. Let's discuss further observations with this in the results section.
  
### Analysis of Outcomes Based on Goals
![alt text](https://github.com/HotMochaNoWhip/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
  
Analysis of this graph gives us insight into how likely a play Kickstarter will be successful when compared to its fundraising goal. Viewing the graph at a glance we can immediately tell that there is a "deadzone" and what seems to be a ceiling before your chances of success drastically drop. We will also talk about further observations here in the results section.
  
### Challenges and Difficulties Encountered
  
For developing the graph of theater outcomes the most challenging issue was determining how to filter dates by months when formatting the chart. With a little effort we were able to fix the graph for our desired visual by removing the Axis Category "Year2" and "Quarters"
  
The biggest challenge was creating the graph for outcomes based on goals. In order to do this we had to create a new sheet of data that counted
how often plays were either successful, failed, or cancelled within ranges of goals. To count this we were introduced to a new function `COUNTIF()`. `COUNTIF()` allowed us to count how often something occured based on restriced criteria. The critera we used was plays, the outcome, and ranges of fundraising goal. This then allowed us to calulate a percentage for each outcome so that we could create the graph above.
  
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the Launch Date graph we can see a few things. The two most notable are the most successful range to start is between April and July, while the least successful is between October and December. Another interesting point of data is, that while there is still a very low chance, if a project were to be canceled its more likely to occur in January. 
  
- What can you conclude about the Outcomes based on Goals?
Looking at the graph we can see the deadzone that was described above to be between 20000 and 35000. You are more likely to succeed between two brackets of fundraising goals: 1 to 20000 and 35000 to 45000. 
  
- What are some limitations of this dataset?
Some of the limitations here are that we are unable to see specific variables. The results for each graph still seems to be vague and slight suggestions that dont let us know just how successful we can be in starting a project. Combining these two tables for each category could provide a more comprehensive analysis on how successful you are likely to be based on how much you need and when you want to start.
  
- What are some other possible tables and/or graphs that we could create?
As stated above, it would be very beneficial to be able to see a graph that combined the results of both outcomes. Creating something that shows the overal perctage something is successful during a certain time vs. when something is successful based on how much the goal is, could drastically improve the chances of determining when would be best for someone to start their kickstarter based on how much they need to make it work. 
