# Election_Analysis

## Project Overview

### Purpose
The purpose of this week’s assignment was to explore the capabilities Python to analyze data in a csv file.    

### Data Analyzed
The specific dataset analyzed included election data from congressional district in Colorado that included three counties and three candidates. Throughout our weekly modules, we began analyzing the data to determine results for each candidate.  For this challenge, we expanded our analysis to also include the county data and results.  
### Deliverables
The deliverable for this assignment was a prepare code that would properly calculate and write our election results to a text file.  

## Election Results
- Total votes cast in the congressional district: 369,711
- Counties in the congressional district and their corresponding votes/percentage of total votes:
  - Jefferson: 38,855 votes (10.5% of the total votes)
  - Denver: 306,055 votes (82.8% of the total votes)
  - Arapahoe: 24,801 votes (6.7% of the total votes)
- County with largest number of votes: Denver
-	Candidates in the election and their corresponding votes/percentage of total votes:
    -	Charles Casper Stockham: 85,213 votes (23.0% of the total votes)
    - Diana DeGette: 272,892 votes (73.8% of the total votes)
    - Raymon Anthony Doane: 11,606 votes (3.1% of the total votes)
-	Winning candidate: Diana DeGette with 272,892 votes (73.8% of the total votes)

Screenshot #1: Shows some of my beginning code (where I load data, tell it where to write/save outputs, and initialize variables).  It also shows my terminal output below the code

![image](https://user-images.githubusercontent.com/92705556/148712160-6c3a9a32-5486-4fa0-aac6-0ab809c221f2.png)

Screenshot #2: Shows the county code, including the code snippet for writing data for “Largest County Turnout” to the text file.

![image](https://user-images.githubusercontent.com/92705556/148712196-39eca35c-76f1-4ec3-b652-28a9ad2d38b7.png)

Screenshot #3: Shows my final election results output.

![image](https://user-images.githubusercontent.com/92705556/148712211-d9859b7f-f591-4d89-8e31-3b656c54a136.png)

# Election Summary

## Letter to Election Commission

Dear Election Commission,

As you can see from the results above, Python can be used to efficiently analyze large datasets and display simple and easily understood results.  The Python programming language is also intuitive and simple to follow.  With clearly delineated variables, ‘for’ and ‘if’ statements, and proper indentation, I believe Python is the best means of analyzing election data moving forward.  By using the code I have attached, you can easily adapt it to read and write results for almost any election data.  Ways you could adapted my code for your election data:

1) 	For lines 8-11 (file_to_load and file_to_save), you would just navigate to your election data and txt files.  

2)	For lines 52 and 55 (candidate_name and county_name), if the candidate names are not in column 3 and the county names are not in column 2, you would change the values in the brackets to the proper column numbers (actual column number minus one because column 1 is counted as ‘0’).  

3)	If instead of candidates you have ballot initiatives, you could change “candidates_names” to “ballot_initiative_answers”.

![image](https://user-images.githubusercontent.com/92705556/148712251-f749dcd3-3b9a-4c56-839a-dc2e42643702.png)

![image](https://user-images.githubusercontent.com/92705556/148712266-3afbb908-823f-4fa6-ba77-a6ee2c2df1d9.png)
