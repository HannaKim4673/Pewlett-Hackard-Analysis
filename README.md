# Preparing Pewlett Hackard for "Silver Tsunami"

## Overview of Analysis

### Purpose
The original purpose of this analysis was to analyze Pewlett Hackard employee data for future-proofing and prepare the company to deal with mass retirement of employees - i.e., the "silver tsunami." As for the challenge analysis, its main purpose was to find the number of Pewlett Hackard employees that would be retiring for each job title and to identify and count the number of employees who would be able to take part in a mentorship program. The mentorship program is being considered as a way to deal with the mass retirement, so the analysis was done to see if there were enough potential retirees in the company who could take part in the program instead of retiring.

## Results

### 2 Major Points from retiring_titles Table
- As visible in the green highlighted portion of the below table, the Senior Engineer position at Pewlett Hackard is the title that requires the most attention, since 29,414 employees with that title are projected to retire soon.
- Also, as visible in the blue highlighted portion of the below table, the Manager position at Pewlett Hackard is the title that requires the least attention and concern, since only 2 employees with that title are projected to retire soon.
  - ![](https://github.com/HannaKim4673/Pewlett-Hackard-Analysis/blob/main/Images%20for%20Readme/retiring_titles%20with%20highlights.png) 

### 2 Major Points from mentorship_eligibility Table
- As visible in the index of the last row of the below table, there are a total of 1,549 Pewlett Hackard employees who are retirement-ready and qualified to take part in a mentorship program. 
  - Note: the number of qualified employees is 1 less than the index number shown because the header row is included in the index count.
  - ![](https://github.com/HannaKim4673/Pewlett-Hackard-Analysis/blob/main/Images%20for%20Readme/mentorship_eligibility%20last%20row%20with%20index.png)
- Looking a the [mentorship_eligibility table](https://github.com/HannaKim4673/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibilty.csv), a large majority of the qualified employees are Senior Staff.

## Summary
As visible in the [retiring_titles table](https://github.com/HannaKim4673/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv), a total of 90,398 roles at Pewlett Hackard will need to be filled as the "silver tsunami" starts to happen. Unfortunately, given that high of a number, if only 1,549 retirement-ready, qualified employees are eligible for taking part in the mentorship program, Pewlett Hackard does not have enough retirement-ready, qualified employees to create an effective mentorship program that will prepare next-generation employees. Even if the number of retirement-ready, qualified employees was split to match each of the company's roles and titles, there are huge gaps between the number of employees that are available for mentoring and the amount of roles that need to be filled. Even giving mentors groups of new employees to teach may not be feasible, since there are just so many roles that need to be filled.

To gain better insight into how the "silver tsunami" will affect the company, the following two tables should be created. First, a table that provides a count of the retirement-ready, qualified employees that can take part in the mentorship program for each company role would provide a better picture of the feasibility of instituting a mentorship program. Secondly, a table that shows the average salary for each company role may help to explain why certain roles are going to explain higher losses than others.
