# Election_Analysis
For Module 3

## Overview of election audit
This analysis is made to audit the result of the election in Colorado (3 counties Jefferson, Denver, and Arapahoe) by counting the total votes and votes for each candidate and by deciding the winning candidate.
The votes is counted by three following voting methods, Mail-in Ballot, punth cards, and direct recording electronic.

Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.
## Election - Audit results:
### Number of votes:


* Total number of votes is 369,711.
* Denver got the most votes 306,055, which is 82.8% of the total votes.
* The following is the number of votes and the proportion of votes of each county  


| County | Number of votes | % of votes| 
| ---- | ---- | ---- | 
| Jefferson | 38,855 | 10.5% |
| Denver | 306,055 | 82.8% |
| Arapahoe| 24,801 | 6.7% |


### Winning candidate:
* The candidate who won the election is **Diana Degette** by winning **73.8%** of total votes.
* The following is the number of votes and the proportion of votes of each candidate  

| Candidate | Number of votes | % of votes| 
| ---- | ---- | ---- | 
| Charles Casper Stockham | 85,213 | 23.0% |
| Diana DeGette | 272,892 | 73.8% |
| Raymon Anthony Doane| 11,606 | 3.1% |



### Election Audit Summary:
* The winning candidate in Colorado congressional election was Diana Degette with 272,892 votes, which is 73.8% of total votes.
* Denver had the largest number of votes, 306,055.

#### Proposal to the election commission
This script can be used for other elections as well such as senetorial districts and local elections. 

#### Presidential Primary election
In presidential primary elections, 2 candidates are selected from all the candidates running for state constitutional, US Congressional, and state legislative offices.  
We can use the following code to get the name of the 2 candidates who got the most votes.  

#To see the candidate who got the most votes.  
candidate1st = max(candidate_votes, key=candidate_votes.get)  
#To see the candidate who got the second most votes  
candidate2nd = sorted(candidate_votes, key = candidate_votes.get)[-2]  
print(f"The winning candidates are {candidate1st} and {candidate2nd}" )  

