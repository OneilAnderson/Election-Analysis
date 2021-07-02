# Election-Analysis

## Project Overview 
We are given the task to complete the election audit for a local election for the Colorado Board of Elections. After completing the collection of data for the candidates in the election, the Committee asks us for information based on the counties that are involved in the election.

For the candidate portion , these tasks included:

 1.Calculating the total number of votes cast. 
 
 2.Forming a complete list of candidates who received votes.
 
 3.Tallying the total number of votes each candidate received.
 
 4.Counting the percentage of votes each candidate won.
 
 5.Stating the winner of the election based on popular vote.
 
For the county portion, these tasks included:

1.Tallying the voter turnout for each county.

2.Calculating the percentage of votes for each county out of the total votes.

3.Finding the county with the highest turnout.

## Resources
Data Source - election_results.csv
Software - Python 3.9.5, Visual Studio Code, 1.38.1

## Results
The analysis of this elections shows:

- There were 369,711 votes casted in the election.

- The countys that were present were :  
   - Denver
    
   - Arapahoe
   
   - Jefferson
 
- The county results were :

   -Jefferson made up 10.5% with 38,855 votes.
 
   -Denver made up 82.8% with 306,055 votes.
 
   -Arapahoe made up 6.7% with 24,801 votes.
   
- The largest county turnout belongs to:

    - Denver with 306,055 votes.
  

- The candidates were :

  -Charles Casper Stockham
  
  -Diana DeGette
  
  -Raymon Anthony Doane
  
- The candidate results were :

    -Charles Casper Stockham received 23.0% of the vote with 85,213 votes.
    
    -Diana DeGette received 73.8% of the vote with 272,892 votes.
    
    -Raymon Anthony Doane received 3.1% of the vote with 11,606 votes.
    
- The winner of the election was:

  -Diana DeGette, who received 73.8% of the vote with 272,892 votes.
  
## Summary 

 The script that was created for this tasks fully explains the county and candidate information for this election. However, if the election committee wanted to modify this script for a different election, there are a few ways it could be changed. One way to modify the script for a different election is to change the file_to_path information to load in a different set of data. This can allow the program to run a similar set of data with different outcomes for candidates and counties. Another way of modifying the script is to add a new variable, such as the Party the candidate represents. For example, if the political parties are locate in a column in our data, we could change to include it with candidate_name and pull the data when the candidates are pulled. these are two good ways the script could be modified for a different election.

