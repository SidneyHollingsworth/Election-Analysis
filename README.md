# Election Analysis

## Overview of Election Audit 
The following congressional election audit was performed for the Colorado Elections Commision. Using provided election results data and Python, I tabulated, analyzed and provided synthesized election results, including candidate and county vote distribution, to the commission.

### About Dataset
Provided election results data included voter 'Ballot ID', voter 'County', and selected 'Candidate' with each row representating a vote cast. 

## Election-Audit Results

#### County Breakdown

- Total Votes: 369,711

- Number of votes and the percentage of total votes for each county:
  - Denver: 82.8% (306,055)
  - Jefferson: 10.5% (38,855)
  - Arapahoe: 6.7% (24,801)

- County with the largest number of votes: **Denver**

![Distribution of Votes by County](https://github.com/SidneyHollingsworth/Election-Analysis/blob/15f0012a44986871d970cceb55bfabb6d706a115/Resources/Graph_Vote_Distribution_by_County.png)

#### Candidate Breakdown 

- Number of votes and the percentage of the total votes each candidate received:
  - Diana DeGette: 73.8% (272,892),
  - Charles Casper Stockham: 23.0% (85,213),
  - Raymon Anthony Doane: 3.1% (11,606),

- Winning candidate: **Diana DeGette**
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

![Distribution of Votes by Candidate](https://github.com/SidneyHollingsworth/Election-Analysis/blob/15f0012a44986871d970cceb55bfabb6d706a115/Resources/Graph_Vote_Distribution_by_Candidate.png)

## Election-Audit Summary 
Might it be of interest to the Colorado Elections Commission, the `PyPoll_Challenge.py` Python script can be edited slightly and re-used for any election or poll as long as a like csv with three columns is provided. Existing script can even handle more than three unique County or Candidate Names.

Ways this script can be modified for future use:
1. Municipal proposition elections in which the Candidate column and related objects be renamed to Support for Proposition, For or Against.
2. Popular candidate by county.
