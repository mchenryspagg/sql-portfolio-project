# (ENTRY LEVEL SQL PORTFOLIO PROJECT)

## Table of contents

- [Overview](#overview)
  - [Dataset](#dataset)
  - [Root Cause Analysis Process](#root-cause-analysis-process)
  - [Links](#links)
  - [Built with](#built-with)
  - [Key Insights](#key-insights)
- [Acknowledgments](#acknowledgments)

## Overview
A portfolio project involving a detailed analysis of 37,997 high school/college student records to showcase key insights through the aid of effective visualizations aimed at evaluating the factors affecting student's academic performance in high school and colleges in the USA.

## Dataset

- This **[data set](https://content.cloudfront.entrylevel.net/experience/data3/module-4/Module+4+-+Task+Files.zip?_gl=1*pfl0lt*_ga*MTkwNzE2MzgwOC4xNjY2NzE1NTk0*_ga_8RTQ11GGMX*MTY3MDgwMTEyMS44OC4xLjE2NzA4MDUzNzcuNjAuMC4w)** contains four csv files of student data provided by Entry Level for the purpose of this report. The four csv files contain data about the _country info, student academic info, student family details_ and _student personal details_ respectively for 37997 student records. The four datasets were combined using sqlite to form a reporting table which served as our database from where we then created additional tables used to answer our research questions.

- Key column variables in the dataset includes :

| variables | Details |
| --------------------- | ---------------------- |
| gender | factor indicating gender |
| ethnicity | factor indicating ethnicity (African-American, Hispanic, Asian or other) |
| academic_score | student’s academic score throughout high school and college |
| student_tuition | cost of tuition for the student |
| education | the years of education the student has received |
| fcollege | factor. Is the father a college graduate? |
| mcollege | factor. Is the mother a college graduate? |
| home | factor. Does the family own their home? |
| urban | factor. Is the school in an urban area? |
| unemp | county unemployment rate in 2020 |
| income | high or low income household based on county average |
| wage | state hourly wage in manufacturing in 1980 |
| distance |  distance from 4-year college (in 10 miles) 
| region | factor indicating region (West, East or other) |
| avg_county_tuition | average state 4-year college tuition (in 1000 USD) |

## Root Cause Analysis Process
To ascertain a root cause analysis, we attempted to answer the followimg questions with the newly created tables

1. What are the proportion of educated students by ethnicity
2. How can we evaluate the Cost of college tuition against household income
3. What is the effect of a student's parents  education on the education of the student
4. Is location of school a determinant on tuition 
5. What is the differences in student's performance with respect to where the school is location
6. Which ethnic group has a higher performance rate in schools and which gender performs better on average?
7. Does the age of a student have an effect on their academic performance in school?
 

### Links

#### Solution URL: 

- [Project Report](https://drive.google.com/file/d/1g_9eSkNoOTPBWlbdGwKpvYdr_TC8jHWZ/view?usp=share_link)
- [Google Sheet Dashboard](https://docs.google.com/spreadsheets/d/e/2PACX-1vS8upZC6jUWUWom88WhFAnp6bxs6vlykOnz8ak5SmOqZ-IjR2ny8aNszT3yjFKj-izQ4EvY2KIJn-kv/pubhtml?gid=36790771&single=true)


### Built with

- SQLite
- Google Sheets
- Pivot tables, SQL Aggregations

## Key Insights

- The African American students are the least represented while the 'other' category of students are the most represented in our student's sample.						
- Average number of years spent by students in school is 14 years for students of all ethnicities.	
						
- There was no considerable effect of a student's age on their academic scores.						

- Students from high income homes pay on average slightly higher student tuition (0.72% higher) than those from low income homes.
						
- Students from high incomes homes pay a country tuition of averagely 1.23% higher than those from low-income homes
						
- There is no considerable effect of parents education on the education of the student						

- Student who have both parents educated perform better in academic scores and have more years of education than those with both or either parent uneducated						
- Students with both parents not educated perform the least in academic scores and have lesser years of education than those with both or either parents educated						
- Average country tuition for the western region of the country is very much lower than other regions of the country.
					
- There is no considerable difference in academic scores of students in the different regions/settlement type	
					
- Average academic scores per student across all region is 51%						

- Male students on average have better academic scores than female students	

- In terms of academic performance, Asians rank better than all other ethnic groups in the country.

- A plot of academic scores for all students shows a symmetrical distribution	

- More students have an academic score of 56% than any other score.					

- Lowest academic score of any student is 29% and highest of any student is 73%.

- 51.5% of all students passed  (scored greater than or equal to 50) whilst 48.5% of all students failed (scored less than 50).

![image1](https://user-images.githubusercontent.com/88894128/209207928-053987ee-5ffd-4d7f-b5ac-517a2037b9f0.png)


## Acknowledgments
Special thanks to Entry level for providing the dataset for this project and to the Data Analyst 3: Advanced SQL class tutor - Nabeel for the lessons and knowledge gained.
