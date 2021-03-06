# Kickstarting with Excel: Challenge 

## Overview of Project
  Project 'Kickstarter Challenge' is a deep dive into the statistics behind Kickstarter Campaigns. This compilation of spreadsheets, tables, and charts holds and compares Kickstarters based on 21 categories of information. These categories include Names, country of origin, fundraising goals, outcomes, etc. 
### Purpose
   The purpose of collecting and analyzing Kickstarter background information in the 'Kickstarter Challenge' is to create a way for the user to draw conclusions on the inferred outcome of a given kickstarter based on past campaigns. In the example analysis the user, Louise, wants to compare the success of her play's Kickstarter to the launch dates and funding goals of other plays' campaigns. The data is sorted and charted in a format that reveals the trends behind success (or failure). This allows her to draw conclusions on the best times of year to start a campaign, as well as the fundraising goals with the highest rates of success. 
## Analysis and Challenges
   Data from over 4000 theater kickstarters is displayed based on country of origin (Great Brittain). The Spreadsheet pulls the outcomes of the British campaigns and separates the outcomes into three categories: Successful, Failed, and Canceled. The information is collated and separated by the month of the year the campaign started. The final product of this is a basis for a line graph that cleanly and easily conveys the trends behind the timing of Kickstarters vs the rate of success. 
#### Potential Challenge
   When considering the trend(s) portrayed in the chart, the user must understand that in finding the success rate, no other outside variable aside from time of year is being considered. For example, the month of March experienced a decline of approx. 20% in the success of outcomes (see fig. 1). This also happens to coincide with the upcoming end of the British fiscal year (April 5th) which could imply that individuals are less likely to freely donate their money to a Kickstarter until the tax deadline is met. In order to prove this correlation more research is needed, however for the purposes of portraying the effect of outside factors on campaign success this example works well.
   
   ![](fig.%201.png)
   
   (above: fig. 1)


### Analysis of Outcomes Based on Launch Date
   A visual analysis of the generated line graph (see fig. 2) reveals that Kickstarter Campaigns for plays are significantly more likely to succeed when launched in or around the month of May. This climax is followed by an almost linear decline in success rates for the next 4 months, with rates of failure staying nearly the same for May and the first 3 months of decline. Not only does the rate of success go down from May onward, but the total number of failed kickstarters from May to July indicates a decline in the total number of Kickstarter campaigns for plays altogether.By looking at the canceled statistic one can see that in number it doesn't make up for a significant amount of outcomes during these months. These facts should indicate to Louise that launching a Kickstarter for a play in May would hold the best chances of success. 
   
   
![](Theater_Outcomes_vs_Launch.png)

(above: fig. 2)

   
### Analysis of Outcomes Based on Goals
   The line graph generated by the outcomes based on goal is symmetrical along the 50% value of the Y-axis. This makes calculating the values of successful vs failed quite easy at a glance, by adding or subtracting a value's distance from the 50% line, the other value for successful or failed can be calculated for a given goal. All values up to $15000-$1999 have a higher average success rate than 50%. This trend is also observed from $35000-$34999. 

![](Outcomes_vs_Goals.png)

(Above: fig. 3)
### Challenges and Difficulties Encountered
   Like the challenge stated above for the outcomes based on launch date, the outcomes based on goal graph fails to take in information from outside variables that can greatly effect outcomes of success vs failure. For one, the number of campaigns is not listed as a variable on the graph, meaning that if just one campaign was successful at $100000 the success rate would be listed as 100%. This can be misleading to Louise because at a glance it looks like the success rate is excellent, but in reality it could just be an outlier or one specific case of high-rolling campaign backers that she may not have access to. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

   * Campaigns launched in or around the month of May have the highest success rates for the year.
   * Campaigns launched in the month of December have the lowest rate of success.

- What can you conclude about the Outcomes based on Goals?
   * Campaigns with a goal value of less than $19999 have a higher rate of success than 50%
   * Campaigns from $19999 upward have a lower chance of success (when also taking number of campaigns in the data set into consideration beyond $19999.)

- What are some limitations of this dataset?
   * The number of campaigns at each goal data point in the 'Outcomes Based on Goal' graph isn't taken into consideration.
   * The Theater 'Outcomes by Launch date' graph can be easy influenced by outside variables such as the example stated above, and the user wouldn't know the why behind the success rates. 
   

- What are some other possible tables and/or graphs that we could create?
   * a scatter plot using the success/failure rates to determine the success at a given goal that takes the number of campaigns at each goal set into consideration. It is my presumption that based on the data, there would be a large consentration of data points at the lower end of the graph (<19999). This would let the user understand that success/failure rates at the higher campaign goals are subjective to the amount of data points given. (Only one high-dollar campaign needs to succeed to display a 100% success rate and so on.)