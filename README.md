# Election_analysis_challenge

## Overview of Election Audit

At the beginning of the module, I was asked to find the total votes of the election, each candidate's votes, and their percentage of votes. Finally, the winner would be the person having the most votes. However, now I have to figure out the vote turnover for each county and their percentages while finding the highest among them. All of this is possible by [reading the csv file](https://docs.python.org/3/library/csv.html) and writing it inside another txt file.the

## Election-Audit Results

* How many votes were cast in this congressional election? The total votes for this election are 369,711 votes. 
[![Capture.jpg](https://i.postimg.cc/fTz03MYZ/Capture.jpg)](https://postimg.cc/Btzvk9hw)
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct. The three counties' number of votes and percentages are shown below.

[![fds.jpg](https://i.postimg.cc/QCy9GTCb/fds.jpg)](https://postimg.cc/bS1N1dQD)

* Which county had the largest number of votes? Denver is the county with the highest number of votes. 
[![fsdcx.jpg](https://i.postimg.cc/Nf2L2LL3/fsdcx.jpg)](https://postimg.cc/qz0p9Jsw)

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received. The three candidates' votes and their respective percentages are depicted in the image below.
[![czx.jpg](https://i.postimg.cc/vZBghM8y/czx.jpg)](https://postimg.cc/JGfz7fBY)

* Which candidate won the election, what was their vote count, and their percentage of the total votes? Diana won the election, and her vote count and the percentage are shown in the image below.

[![ccc.jpg](https://i.postimg.cc/hGRnjb5Y/ccc.jpg)](https://postimg.cc/zy762W5w)

## Election-Audit Summary

Some changes must be implemented to apply this python file for other elections. The first modification is to change the new csv file's path and change the text file's path that we are writing the new results. The second modification is to change the index of the row that we want to read based on the initial csv. We used the [2] index to retrieve the candidate's name in our challenge.
