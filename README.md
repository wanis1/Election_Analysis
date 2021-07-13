# Election_Analysis

## OVERVIEW OF ELECTION AUDIT:
The purpose of this election analysis is to determine the winning candidate of the election based on the highest votes received and the county with highest vote turnout using Python. We wrote the final results on a text file (election_analysis.txt) showing the total votes and vote percentage earned by each candidate, total votes and vote percentage came from each county, the winning candidate of the elections and the county name with highest vote turnout.

## ELECTION AUDIT RESULTS:
### Total Votes Cast in Congressional Election:
Total votes cast in this congressional elections were 369,711.

> ![image](https://user-images.githubusercontent.com/86074187/125487634-b4481a46-b3fe-4e8a-847e-72ab38112aba.png)

### Breakdown of the Numbers for Each County:
The table below represents the number of votes casted from each county as well as what percentage that number was of the total votes cast in the election.
|**COUNTY**|**NO. OF VOTES RECEIVED**|**% OF TOTAL VOTES**|  
|----------|-------------------------|--------------------|
|Arapahoe| 24,801| 6.71% |
|Denver| 306,055| 82.78% |
|Jefferson| 38,855 |10.51%|

>![image](https://user-images.githubusercontent.com/86074187/125489471-2048b4aa-342d-4465-a086-167b352b9824.png)

### County with Largest Vote Turnout:
County that had the largest number of votes is Denver.

>![image](https://user-images.githubusercontent.com/86074187/125489812-67f811b2-df26-4d70-b3d0-27bcc6fd8fa4.png)

### Breakdown of the Numbers for Each Partcicipating Candidate:
The table below represents the total number of votes each candidate received as well as what percentage that number is of the total votes received in the election.
|**CANDIDATE**|**NO. OF VOTES RECEIVED**|**% OF TOTAL VOTES**|  
|----------|-------------------------|--------------------|
|Charles Casper Stockham|85,213|23.0%|
|Diana DeGette|272,892|73.8%|
|Raymon Anthony Doane|11,606|3.1%|

>![image](https://user-images.githubusercontent.com/86074187/125490350-bd34276b-070d-410e-aa3f-6f04a0e90c7e.png)

### Winning Candidate:
Winning candidate for this election is Diana DeGette. She received a total of 272,892 votes which is 73.8% of the total votes received in the election.

>![image](https://user-images.githubusercontent.com/86074187/125490673-4876ce5e-14f9-4dfb-97f4-166f07436ecf.png)


Here is the summary of the final results:

>![image](https://user-images.githubusercontent.com/86074187/125491450-b210abd2-f4d0-41c4-8aab-50a59f3a5b11.png)

## ELECTION-AUDIT SUMMARY
This code can be easily used by the election commission for any election. This code is very customizable so with few modifications, this code can produce results for any election.
For example, if the elction results are stored in an .xlsx file, instead of csv, we can import different dependencies to read .xlsx file such as xlrd. The modification will just be needed to make in the beginning of the code:

>![image](https://user-images.githubusercontent.com/86074187/125493231-d0dec496-7894-4ff7-8a35-bf005c74ff77.png)

Also, if the election involves regions other than counties, such as states or provinces or even cities, we can modify step 4, step 5 and step 6 of the code accordingly.

>![image](https://user-images.githubusercontent.com/86074187/125493536-267c3765-9645-4487-b14a-7e6421493c8f.png)

>![image](https://user-images.githubusercontent.com/86074187/125493620-78e61aee-ebde-4baa-af71-38ee3dd3029e.png)







