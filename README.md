# Election-Analysis
Using Python through Visual Studio Code to analyze raw election result data and determine the winner of the election based on popular vote.
## Overview and Process of Election Audit
For our project, we were tasked with assisting Tom, an employee of the Colorado Board of Elections, on providing the winner of the election based on popular vote using Python to analyze our data. 

In order to provide an accurate, fair outcome and conduct an election audit for Tom and the Board, we must determine the following:

1. Total number of votes
2. List of all candidates who received votes
3. Total number of votes each candidate received
4. % of votes each candidate received
5. Winner of election
6. Voter turnout for each county
7. % of votes for each county compared to total count
8. County with highest turnout

## Resources Utilized to Complete Audit
Tom was able to provide us with a CSV file containing the raw election results.  The dataset provided us with a large, unorganized file containing each separate vote that was casted for the candidate of choice. We utilized Python to analyze the dataset of election results in code editor, Visual Studio Code.

The raw, more detailed Election Results Dataset can be viewed by clicking [here](https://github.com/nataliabench/Election-Analysis.git) under "Resources" folder.

## Election Summary and Results
We conducted an election audit on the data for the **three candidates**: Charles Casper Stockham, Raymon Anthony Doane, and Diana DeGette. The total number of votes cast for the three candidates were 369,711.

Charles Casper Stockham recieved 23% of the total number of votes, which was equivalent to 85,213 votes. Raymon Anthony Doane received 3.1% % of the votes, equivalent to 11,606 votes.  As for Diane DeGette, who received 73.9% of the total number votes resulting in an enormous lead with 272,892 votes. 

By simply concluding those two values from the data, we can determine **the winner of the election based on popular vote was Diane DeGette**! Congratulations!

As for our deeper analysis on the counties, Jefferson County consisted of 38,855 voters which lead to 10.5% of votes out of the total count coming from Jefferson. Denver County had 306,055 voters and 82.8% of votes out of the total count came from Denver. Lastly, Arapahoe County had 24,801 voters with a smaller statistic of only 6.7% of votes coming from them.

Denver County had an overwhelming lead with the **highest voter turnout** compared to the other two Colorado counties.  This could depend on varying populations per county, access to voting stations, county diversity and much more.

Below, you may view a screenshot of the text file containing the final results.
![alt text](https://github.com/nataliabench/Election-Analysis/blob/a8d5c3a7e21d2717c73979fad94355e8c99eb265/Analysis/Election_Analysis_ResultsSC.png)

## Election Analysis Summary
 The Python script we created was extremely efficient for the task given, primarily due to the dataset relating to a smaller set of data. Since our analysis focused only on Colorado and the three candidates, our script was able to perform the calculations quickly and easily.  But, if our task were to change to focus on a larger scale population, like the United States Presidential elections, we would need to refractor our code. Our original code would be used as the foundation of the refractored code in order to develop a faster producing script for larger datasets as well as allowing our script to perform other detailed functions to find more useful trends.  Our refractored code could be used to determine detailed information on specific groups of people, voter count per state, school district analysis, and so forth.  We could alter the code to function for various situations that require the evaluation of numerical data.
