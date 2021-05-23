# Colorado-Election-Analysis

## Project Overview

This project is an election audit of local congressional election in Colorado conducted in two parts: a candidate analysis and a county analysis. Utilizing a dataset consisting of 369,711 votes, I examined trends in regards to the votes won by candidates and voter turnout by county. Via these two analyses, information on how each county's voter turnout influenced the outcomes of the election may be discerned.    

***Part #1: Candidate Analysis***
 - First I calculated the total number of votes cast. 
 - Then I compiled a list of all candidates who had received votes.
 - Next I found the total number of votes received by each candidate. 
 - Afterwards, I found the percentage of votes each candidate won.
 - Finally I determined the winner of the election based on the popular vote.

***Part #2: County Analysis***
 - First I compiled a list of all counties where votes were cast.
 - Following that, I found the total number of votes by county. 
 - Finally, I determined the county that had the largest turnout of voters. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.7, Visual Studio Code 1.51.1

## Summary

Findings from this analysis show the following:
![image1](analysis/results_table.png?raw=true "Title")

 - There were 369,711 votes in the election. 
 - The breakdown of votes by candidate was 23% (85,213) of votes for Charles Casper Stockham, 73.8% (272,892) of votes for Diana DeGette, and 3.1% (11,606) of votes for Raymon Anthony Doane.
 - The breakdown of votes by county was 10.5% (38,555) of votes cast in Jefferson County, 82.8% (306,055) of votes cast in Denver County, and 6.7% (24,801) of votes cast in Arapahoe County.     
- As a result, the winner of the election is Diana DeGette and the county with the largest voter turnout is Denver.
- This script can be modified for use in analysis of any election by including a prompt for the user to input the name of a unique data file for that particular analysis, and a prompt for the results txt file to be saved in the location of the user's choice.  
