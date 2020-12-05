# Election_Analysis
## A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calcualte the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.51.1

## Summary
The analysis of the election show that: 
- There were 369,711 votes cast in the election. 
- The candates were: 
  - Charles Casper
  - Diane Degette
  - Raymon Anthony Doane
- The candidates results were: 
  - Charles Casper received 23.0% of the vote for a total of 85,213 votes. 
  - Diane Degette received 73.8% of the vote for a total of 272,892 votes. 
  - Raymon Anthony Doane received 3.1% of the vote for a total of 11,606 votes. 
- The winner of the election was: 
  - Diane Degette, who received 73.8% of the vote for 272,892 total votes. 

## Election-Audit Overview
The purpose of this congressional election-audit is to summarize the voting results for three counties in terms of number of votes and the voting percentage. From there, we will print out the results both to the terminal, and also to a text file. These result will be added to prior work done in capturing the results for each candidate. 

## Election-Audit Results 
* There were a total of 369,711 votes cast in this congressional election.
* The following represents the number of votes and vote percentage for each county: 
  - Jefferson: Total Votes = 38,855. % of the total vote = 10.5%
  - Denver: Total Votes = 306,055. % of the total vote = 82.8%
  - Arapahoe: Total Votes = 24,801. % of the total vote = 6.7%
* Denver had the highest number of votes with a total of 306,055 votes or 82.8% of the total vote. 
* The following represents the number of votes and vote percentage of each candidate: 
  - Charles Casper Stockholm: Total votes = 85,213. % of the total vote = 23.0%
  - Diana Degette: Total votes = 272,892. % of the total vote = 73.8%
  - Raymon Anthony Doane: Total votes = 11,606. % of the total vote = 3.1%
* Diane Degette had the highest number of votes with a total of 272,892 votes or 73.8% of the total vote. 
## Election-Audit Summary
### The software used for this election-audit can be used for any election. Below are a couple of examples that show how you might use this in future elections: 
  - The dictionary holding the counties and vote totals can be modified to capture any group of counties simply by substituting with the elections results file a new group of candidates, counties and vote totals. 
  - This can be applied to a national election by creating a dictionary of states, as opposed to counties, and running the same logic to capture state totals, percentages, and creating any summary information associated with this. 

The nice thing about the approach done here is that any election can be summarized in a one page document, giving the observer the ability to understand the results of an election in a single glance. 
