# Election Analysis

> Helping with Colorado's election with analysis using Python.

## Overview of Project

A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election using a set of programmatic tools of Python, Visual Studio Code, and Git.

## Summary

The analysis os the election show that:

Using Python and reading in the CSV election data set we determined out of the 369,711 votes some patterns and analysis.

We created a python script and would read and write data, performed calculations on the counts, and used loops and conditional statements to report our analysis.

- There were 369,711 votes cast in the election.
- The three candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- With the candidate results being:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Candidate 3 received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

### Resources

- Data Source: election_results.csv
- Client requirements
- Software: Python 3.7.7, Visual Studio Code, 1.47.3, Git 2.27

### Out Put Document

> We've submitted an outlined report located in the analysis folder under election_analysis.txt.

```
Election Results

---

#### Total Votes: 369,711

County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

---

#### Largest County Turnout: Denver

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

---

Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

---

```

## Challenge Overview

> We helped Seth and Tom submit the election audit results to the election commission.

1. The data we need to retrieve.
2. Capture and calculate the total number of votes cast through looping.\*
3. Get a complete list of candidates who received votes.
4. Calculate the total number of votes each candidate received.
5. Calculate the percentage of votes each candidate won.
6. Determine the winner of the election based on popular vote.

### Election Audit Results

With the out file located in the resources folder we answer the following points and questions:

- How many votes were cast in this congressional election?
  - Total Votes: 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - County Votes:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Which county had the largest number of votes?
  - Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

Colorado saw three counties tally up to 369,711 votes. The biggest of the counties with a 82.8% was Denver. We processed the votes for three candidates of Charles, Diana, and Raymon. With 73.8% of the votes towards Diana DeGette, that is 272,892 of the 369,711 total votes.

## Election-Audit Summary

Expanding the Election Audit to include voter turnout by county with candidates results has been a great way to take advantage of the convenience a script provides.  The added insight can be a guide for future election performance, so that you may properly allocate resources where turnout is low or demographics are hard to reach.

A little time invested into customizing the script can provide on-demand analysis for years to come.  

Modifying the script to produce turnout results by county is just one of many ways that minor adjustments to the code can reveal critical data.  For example, we could also dive deeper and determine what percentage of each county voted for each candidate by adding an if-statement to the code.  These type of Decision Statements are how the code runs calculations and all we've done is provide it with a data file. 

Similarly, if this were a federal election, we could use the same script and change the county to states. 

In short, no matter the number of candidates or counties, the script used to perform the Election Audit can be a valuable resourse for the board.  
