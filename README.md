# Election-Analysis

## Project Overview
Assisting a colorado board of election employee in an election audit of US congressional precinct and automating the process for it to be used in other elections. The following are questions that will be answered in this analysis.

1. How many votes were cast?
2. The number and percentage of votes for each county and candidate.
3. The county and candidate with the largest number of votes.
4. The winner of the election.
5. Instructions to reuse python script.

## Resources

- Software: Python 3.8.5, Visual Studio Code 1.55.0, git version 2.30.1.windows.1
- Data Source: election_results.csv


## Summary

The analysis of the election shows that:
- Total number of votes: 369,711

- The candidates and thier percentage (number of votes) :
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)

  
- The winner of this election:
  -Diana DeGette Won with 73.8% (272,892) of the votes
  


## Challenge Overview
As an additional assisting tool, we wanted to include each county in our analysis. Knowing how many voters are in each state will help officials make better decisions when planning for the next election season.

This section will include information about:

1.Each County's voter turnout rate.
2.The county with the most voters.

## Challenge summary

- Biggest voter turn out was in Denver with 82.8% (306,055) of the votes

- The percentage(number of votes) per county:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 3.1% (11,606)
 
## Election audit summary

To reuse this script in future elections follows these steps.
- [ ] Check that the CSV/text file follows the same format as the current one with **(Ballot Id, County, Candidate)** as headers. 
- [ ] Check the path of the `File_to_load` and `File_to_save` Variables. 
- [ ] Check if the print statement returns The desirable output.

If the format is different, then a few alterations to the script would be needed.
- [ ] Check the index of retrieved columns in the variables `candidate_name` and `county_name`.
- [ ] Data source has to include a candidate column and a county column.
- [ ] Data source should have unique voter ID's
