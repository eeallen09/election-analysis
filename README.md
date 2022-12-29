# election-analysis

## Overview of Election Audit

### The purpose of this election analysis audit is to provide the election committe with election results and voter turnout metrics.  

## Election Audit Results

* **Total Votes Cast:** 369,711

* **Votes by County (Highest to Lowest):**
  1. Denver: 82.8% (306,055)
  2. Jefferson: 10.5% (38,855)
  3. Arapahoe: 6.7% (24,801)

* **Largest County Turnout:** Denver

* **Votes by Candidate (Highest to Lowest):** 
  1. Diana DeGette: 73.8% (272,892)
  2. Charles Casper Stockham: 23.0% (85,213)
  3. Raymon Anthony Doane: 3.1% (11,606)

* **Election Winner:** Diana DeGette
  * Winning Vote Count: 272,892
  * Winning Percentage: 73.8%


## Election Audit Summary

### The Python script created for this audit can be used to automate anlyses for any election, to include other congressional districts, local elections, and even senatorial districts.  

1) Modification 1 - File Loaded
    <img width="547" alt="Load_File" src="https://user-images.githubusercontent.com/118704152/210012858-9db5034a-e613-4627-97ce-2645d3b29341.png">
    
2) Modification 2 - Standardization of Rows  
    <img width="450" alt="Row" src="https://user-images.githubusercontent.com/118704152/210012885-d6a5fb72-4912-4063-a522-4d46d6cd43d6.png">

3) Modification 3 - Adjust occurences of "County" to appropriate jurisdiction 
    <img width="469" alt="County_Occurrences" src="https://user-images.githubusercontent.com/118704152/210012913-d4acdc6b-82ff-4ef6-aaba-f1ee19b5118e.png">

Using this script for elections across Colorado would improve both the speed and accuracy of calculating election results.  The current process for calculating election results in Excel is more time consuming and prone to human error than running this Python script.  Through standardizing election analyses processes in Python, the election commission could provide faster and more accurate election results to Colorado voters.
