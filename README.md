# School District Analysis
A review of the impact of academic success by school size, type of school, and funding provided.
---
---

## Overview
There are multiple factors that should be considered to determine what attributes to a school's success or failure. Even within a single district, factors such as the type of school, the budget, grade level, and the school's size can greatly shift a school's performace record. 

### Purpose of the Analysis
In this analysis, 15 high schools, grades 9-12, were compared to help identify trends. Please note that only math and reading scores were analyzed, and 70% or better is considered passing.
Here is the initial, unsorted data. Please review the findings against this image to support future action(s). 

![District Overview](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/District%20Summary.PNG?raw=true)

## Results
Subheading - Using bulleted lists and images of DataFrames as support, address the following questions.
There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data

- DISCTRICT vs CHARTER school design was also compared. There is a strong relationship showing Charter schools outperform District schools, with over 40% more students achieving an overall passing score. Please also note that within District schools, the average score is 77 while the percentage of students passing is 67%. This indicates the spread of scores varies greatly within District schools.

![School Type vs Passing Grades](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/School%20Type%20v%20Passing%20Grades.PNG?raw=true)

- These views show the top 5 overall performers in the district and the bottom 5 performers. Several trends are visualized here:
  - The bottom 5 performers have at least double the student population of the top 5 performers.
  - The range of Per Student Budget for the bottom performers is $637 - $655. The top performers' budgets range $578 - $638. Since the per student budgets are similar, this shows this is not the best indicator of failure or success.
  - Reading scores and the percentage of students passing reading are strong for the both top and bottom performers.
  - Math scores shows great differences between top and bottom performers: For the top 5 schools, over 90% are passing math with average of ~83%. The bottom 5 schools show maybe 2/3rds of their students are passing, and the average math scores are in the mid-upper 70s.

![Top 5 Performers](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Overall%20Performing%20School%20Profile%20-%20Best.PNG?raw=true)

![Bottom 5 Performers](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Overall%20Performing%20School%20Profile%20-%20Worst.PNG?raw=true)

- BUDGET: Many would attribute academic success to the school's funding. In this analysis, schools were categorized into 4 ranges and their grouped performance was averaged. Interestingly, a negative correlation is evident across the district. That said, the above discussion on Per Student Budget should discourage quick decisions on budget modifications.

![Budget vs Passing Grades](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Budget%20v%20Passing%20Grades.PNG?raw=true)
 
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  - Scores by school spending
  - Scores by school size
  - Scores by school type

### Visual Aides
Link to image 2: 

## Excluding Ninth Graders' Data from Thomas High School
In this exercise, we ran a comparison without 9th graders' scores from Thomas High School's data to investigate their impact on overall performance. The following shows significant changes in the school's profile and its student's success.

![District Summary with Thomas High School's 9th grade excluded](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/District%20Summary%20-%20Thomas%20HS%20Adjusted.PNG?raw=true)

### Major Change 1
The percentage of students who earned a passing score **score of at least 70% in MATH rose from 66.9% to 93.2%.**

### Major Change 2
The percentage of students who earned a passing score **score of at least 70% in READING rose from 69.6% to 97.0%.**

### Major Change 3
The percentage of students who earned an overall passing score (based upon Reading and math scores) jumped by 25%!

### Major Change 4
Thomas High School ranks 13th within the district; after 9th graders' scores were removed Thomas High School ranks 2nd.

Ultimately, excluding ninth graders' from analysis made an enormous impact on the school's performace record. It is advisable that additional analyses are performed to determine whether this is true only for Thomas High School, or if ninth graders' scores lower the overall performance of schools across the district. However, this snapshot shows that across the district, it may not play as significant a role at other schools:

![Grade Level vs Math Scores](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Grade%20level%20v%20Math%20Scores.PNG?raw=true)

![Grade Level vs Reading Scores](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Grade%20level%20v%20Reading%20Scores.PNG?raw=true)

---
To review the complete dataset please follow this link: [School District Analysis](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

