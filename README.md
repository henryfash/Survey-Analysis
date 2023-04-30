### Project Title : Survey Dataset Analysis

#### Research Questions:
- Question 1: how many samples were collected on each day?
- Question 2: what proportion of the total respondents were aged less than 45?
- Question 3: create a new column in the dataframe “age_group”. This column should contain the age group the respondent belongs to. The age groups are 18-25, 25-40, 40-55 and 55+.
- Question 4: how many samples were collected for each age-group? Which age-group had the most samples?
- Question 5: what proportion of the respondents had opted for the RJD party in both the Vote_Now and the Past_Vote questions?
- Question 6: for each day of sample collection, determine the proportion of respondents who were fully satisfied with the performance of the CM. So if there were a total of 1000 samples on day 1 and 300 out of those said they were fully satisfied, then our answer for that day would be 0.3.
- Question 7: In a similar fashion create a day-wise proportion of respondents that opted fully dissatisfied with their MLA. Create a line plot of the result with date on x-axis and proportions on the y-axis.
- Question 8: create a pivot-table (or crosstab) with index as Past_Vote, Column as Vote_Now and cell values as the count of samples.
- Question 9: repeat the above question with the cell values as the sum of “weight”.
- Question 10: create a dataframe by performing a group by over age_group and calculate the count of total samples under each age_group.
- Question 11: create a dataframe by performing a group by over age_group and finding the count of total samples for each age_group that opted for the JD(U) party in Vote_Now.
- Question 12: join/merge the two dataframes from questions 10 and 11 with the common column as age_group.