# Election_Analysis
Python
# Overview of Election Audit
Seth and Tom need to submit an election audit to an election commision. They have been given all of the voter results in a csv file.

Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.
* The file that they need to process has 369,711 lines of data/votes.
* There are 3 counties in the dataset. Denver county controlled the election with over 300 thousand of the votes. A turnout of a massive 82.8%.
* The other two counties, Jefferson and Arapahoe had 10.5% and 6.7% respectivly.

* DeGette won the election with 73.8% of the vote. The results are as follows: 
![results](https://github.com/James-Harkin/Election_Analysis/blob/main/Results.jpg?)
# Proposal
I propose that this script can be used for other elections. The way it is right now, with no modifications; provided that the csv is the same format. The loops are liquid enough to handle any amount of votes, candidates and counties.

However providing a more secure script may be desired. Currently the script doesn't look at the ballot id of each vote. Carefully examining and cross checking the validity of each ballot with a third party may be best. Before counting each vote, the script would simply compare and make sure the ballot id only appears once, is valid, ect.
