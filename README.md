# Election-Analysis
The main purpose of this project is to complete the local congressional election audit for the Colorado Board of Election. In this project, our final Python script will need to be able to deliver the following information when the script is run to complete the audit:
a) Total number of votes cast
b) A complete list of candidates who received votes
c) Total number of votes each candidate received
d) Percentage of votes each candidate won
e) The winner of the election based on popular vote
f) The voter turnout for each county
g) The percentage of votes from each county out of the total count
h) The county with the highest turnout

Election-Audit Results:
•	How many votes were cast in this congressional election?
Total vote casted were 369,711 in this congressional election.
 
•	Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
 Jefferson recieved 10.5% of total votes (38,855)
 Denever recieved 82.5% of total votes (306,055)
 Araphoe recieved 6.7% of total votes (24,801)
 
•	Which county had the largest number of votes?
Denver had the largest number of votes: 306,055 votes as shown in the above image
•	Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
 
Charles Casper Stockham received 85,213 votes, which is 23.0% of the total votes, followed by Diana DeGette received 272,892 votes, which is 73.8% of the total votes. Raymon Anthony Doane received 11,606, which is 3.1% of the total votes that were cast in this congressional election.
•	Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
     	Diana DeGette won the election and received 272,896 votes which is 73.8% of the total votes.
Election-Audit Summary:
The Python script can be used with little modification for any future elections from county city to state level elections. This script needs to be modified as per the usage n following ways:
1)	Election data file location to read/write to use in the script: This script has the location as per my local data file location. Once can change the location and use it
2)	We need to add few more validation code to check the data file does not have any duplicates or missing data.
3)	The election data file column order can be different for each data file. So, code need to change according to which column needs to be accessed for the counting and at which column number. 
