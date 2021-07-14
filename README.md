# Colorado Congressional Election Audit

## Overview of Election Audit
I was tasked by a Colorado Board of Elections employee to complete an audit of a recent local congressional election using Python in order to determine the following:

1. Calculate the total vote count. 
2. Get a complete list of counties that people voted in.
3. Calculate the percentage of votes cast by each county. 
4. Determine the county with the largest voter turnout.
5. Get a complete list of the candidates that received votes. 
6. Calculate the total number of votes received by each candidate.  
7. Calculate the percentage of votes won by each candidate. 
8. Determine the winner of the election based on vote count. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, PyCharm 2021.1.3

## Election-Audit Results:
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The counties were:
  - Jefferson
  - Denver
  - Arapahoe
- The county results were:
  - Jefferson accounted for 10.5% of the vote with 38,855 votes. 
  - Denver accounted for 82.8% of the vote with 306,055 votes. 
  - Arapahoe accounted for 6.7% of the vote with 24,801 votes. 
- The county with the largest turnout was:
  - Denver, which accounted for 82.8% of the vote with 306,055 votes. 
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote with 85,213 votes. 
  - Diana DeGette received 73.8% of the vote with 272,892 votes. 
  - Raymon Anthony Doane received 3.1% of the vote with 11,606 votes. 
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes. 

## Election-Audit Summary
The code used for this election audit can easily be utilized for other election audits. For example, by changing the data source that's loaded to the code (aka the "file_to_load" variable) one can easily use this code to run an audit on any election in order to determine winning candidate and county with the highest turnout, regardless of number of candidates or counties (this may, however, require modifying the "candidate_name" and "county_name" variables if their columns appear in a different location than where they were on the original data file used for this analysis). This code could also be modified if an audit/analysis needs to be done on which candidate won the popular vote for each county by counting how many times a candidate's name was voted for on a ballot ID within each county.
