# Overview of Election Audit
The project is to help Tom, a Colorado Board of Elections employee, using Python to complete the election audit of a recent local congressional election. The election audit will provide total number of votes cast, the voter turnout for each county, the percentage of votes from each county out of the total count, the total number of votes and percentage of votes each candidate received, the winner of the election based on popular vote.

# Election-Audit Results
* There were 369,711 votes cast in the election.

* The breakdown of number of votes and percentage of total votes for each county were:

  -From Jefferson: There were 10.5% of the votes and 38,855 number of votes. 

  -From Denver: There were 82.8% of the votes and 386,055 number of votes. 
  
  -From Arapahoe: There were 6.7% of the votes and 24,801 number of votes. 

* Denver had the largest number of votes

* The breakdown of number of votes and percentage of total votes for each candidate were:

  -Charles Casper Stockham received 23.0% of the votes and 85,213 number of votes.
  
  -Diana DeGette received 73.8% of the votes and 272,892 number of votes.
  
  -Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.
  
* Diana DeGette won the elction by 73.8% of the votes and 272,892 number of votes.

# Election-Audit Summary
The script is designed for Colorado Board of Elections to provide a election audit in short time, not only automate the process but perform calculation quickly. Moreover, the script could be used for any election with some modifications.
Let’s say the script will be used not only in Colorado but also in other states. The csv will add in state information in column D and expand more rows of other states data. We could modify the code providing county results into state results. As the data we want to calculate will be in column D, we will modify extracting state name from county_name = row[1] into state_name = row[3] (line 51) and modify printout words from “Largest County Turnout:” into “Largest State Turnout” (line 115). All the variable, list, and dictionary we created for calculating county result will be used to calculate for state result based on column D. To avoid confusion, we could change the name of variable, list, and dictionary into state-related names. In this way, the script could provide state results without a huge modification or adding more code.
