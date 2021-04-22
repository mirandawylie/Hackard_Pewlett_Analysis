# Hackard Pewlett Analysis

## Overview
Hackard Pewlett is preparing for a “silver tsunami” as many current employees reach retirement age. To prepare for this change, the number of retiring employees per title and the employees eligible to participate in a mentorship program were determined.

## Results
* Research began by creating a retirement titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955.

    Link to data: Data/retirement_titles.csv

* The retirement titles table had duplicate entries for some employees because they have switched titles over the years. Using the DISTINCT ON statement to retrieve the first occurrence of the employee number, the unique titles table was created to display the most recent title for each employee. 

    Link to data: Data/unique_titles.csv

* With this unique titles table, the number of retiring employees was configured:
![retiring_titles.png](Images/retiring_titles.png)

    Link to date: Data/retiring_titles.csv

* The employees eligible for the mentorship program are listed as follows:
![mentorship_eligibility.png](Images/mentorship_eligibility.png)

    Link to data: Data/mentorship_eligibilty.csv

## Summary
The number of retiring employees are 90,398 and the number employees eligible for mentorship are 1,549. So while the mentorship program is a good option for recruitment, Hackard Pewlett will need to find more solutions for the impending "silver tsunami." I recommend additional analysis to track the job title trajectory. Could Hackard Pewlett expect any employees transferring from other departments for these job openings? Since those with Senior titles are retiring the most, does this provide more opportunity for middle management? Lastly, will all those eligible for retirement actually retire or stay on?