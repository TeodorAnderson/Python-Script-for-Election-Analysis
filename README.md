# Python Script for Election Analysis
## Teodor Anderson

## Overview of Election Audit

Tom, a Colorado board of elections employee, has tasked me with swtiching their process of calculating total votes, total votes per, and the percentage of votes that each candidate received and county has cast, from Excel into a python code. Given an Excel file of all the data necessary, I wil extract, calculate and present the results into an txt file for Tom and the board.

## Election Audit Results

![Screenshot_20221206_120220](https://user-images.githubusercontent.com/116928193/206011054-b30020cb-6dbb-4ad6-b5e8-4726f4854d94.png)

* The total amount of votes this election cycle was 369,711
* Denver was by far the largest voter county with 306,055 votes and 82.8% of the voters
* Jefferson came in second with 38,855 votes making 10.5% of the voters
* Next Arapahoe with 24,801 leaving it the last 6.7% of the voters
* As for candidates, Diana DeGette won the election with 272,892 votes, giving her a 73.8% super majority
* Next Charles Casper Stockham whipped up 85,213 votes landing him 23.0% of the votes cast
* And Anthony Doane aquired 11,606 votes, 3.1% of the total turnot
## Election Audit Summary

The script can be used for any election, if changes happen to the output interface, for example if you wanted to the the presidential election (going by a popular vote) all you would have to do is replace any mention of county past a print function to state, given that the election file name is updated without a name change and that the same columns are used as last cycles. Another modification is also change the mention of an output county to electoral votes per state and it would run for American presidential elections
