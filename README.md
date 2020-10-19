# School District Analysis
A review of academic success by school size, type of school, and funding provided.
---
---

## Overview
Multiple factors should be considered to determine what contributes to a school's successes and failures. Even within a single district, factors such as the type of school, budget, grade level, and school size can greatly alter a school's performance record. 

### Purpose of the Analysis
In this analysis, 15 high schools, grades 9-12, were compared to identify trends. Please note that only math and reading scores were analyzed, with 70% or better considered passing.
Here is the initial, unsorted data. Please review the results below against this image. 

![District Overview](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/District%20Summary.PNG?raw=true)

## Results
Please review how the metrics impacted the school disctrict's outcomes.

### District vs Charter Schools
There is strong evidence from the data showing Charter schools outperform District schools, with over *40% more students* achieving an overall passing score. Among District schools, the average math score is 77 (67% of students passing) whereas Charter schools have an average math score of 83.5 (with 90% of students passing). The comparison of the average score vs students passing indicates the range of scores is greater among District schools.

![School Type vs Passing Grades](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/School%20Type%20v%20Passing%20Grades.PNG?raw=true)

### Budget
Many may attribute academic success to a school's funding. In this analysis, schools were categorized into 4 ranges and their grouped performance was averaged. Interestingly, a negative correlation is evident in this view. That said, let's continue reviewing the budget on a Per Student Budget level.

![Budget vs Passing Grades](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Budget%20v%20Passing%20Grades.PNG?raw=true)

Several conclusions can be drawn from the images below. In particular, compare the range of Per Student Budget for the bottom performers ($637 - $655) to the top performers' ($578 - $638). Since the per student budgets are similar, this shows budget is not the best indicator of failure or success, and should further discourage quick decisions on budget modifications.

**Top 5 Performers** 
![Top 5 Performers](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Overall%20Performing%20School%20Profile%20-%20Best.PNG?raw=true)

**Bottom 5 Performers**
![Bottom 5 Performers](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Overall%20Performing%20School%20Profile%20-%20Worst.PNG?raw=true)

### School Size
Let's also consider school size. Are the needs different for larger vs smaller schools? Do students have differing access to resources or tools? As seen in the images above, the bottom 5 performers have at least double the student population of the top 5 performers. Here's another view that specifically outlines grouped results. Small and medium size schools appear to have similar, positive student outcomes. Large schools (2000-5000 students) have far worse outcomes, particularly in math and overwhelmingly in the percentage of students who earn an overall passing grade.

![School Size v Grades](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/School%20Size%20v%20Passing%20Grades.PNG?raw=true)

### Math vs Reading
Reading scores and the percentage of students passing reading are fairly strong for the both top and bottom performers.

Math scores, however, show great differences between top and bottom performers. For the top 5 schools, over 90% are passing math with average of ~83%. The bottom 5 schools show over 1/3rd of students failing, and the average math scores are in the mid to upper 70s.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
  - Scores by school spending
  - Scores by school size
  - Scores by school type

## An Exercise in Excluding Ninth Graders' Data
In this exercise, we ran a comparison without 9th graders' scores from Thomas High School's data to investigate their impact on overall performance. The following shows significant changes in the school's profile and its student's success.

![District Summary with Thomas High School's 9th grade adjusted](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/District%20Summary%20-%20Thomas%20HS%20Adjusted.PNG?raw=true)

- The percentage of students who earned a passing score score of at least 70% in **MATH rose from 66.9% to 93.2%.**
- The percentage of students who earned a passing score score of at least 70% in **READING rose from 69.6% to 97.0%.**
- The percentage of students who earned an overall passing score (based upon Reading and math scores) jumped by 25%!
- Thomas High School ranks 13th within the district; after 9th graders' scores were removed Thomas High School ranks 2nd. This aligns better with the conslusions drawn above, including the Charter shcools and medium sized school are high academic performers.

Ultimately, excluding ninth graders' from analysis made an enormous impact on the school's performance record. It is advisable that additional analyses are performed to determine whether this is true only for Thomas High School. However, these snapshots show that across the district, it may not play as significant a role at other schools:

**Snapshot of Grade Level vs Math Scores**
![Grade Level vs Math Scores](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Grade%20level%20v%20Math%20Scores.PNG?raw=true)

**Snapshot of Grade Level vs Reading Scores**
![Grade Level vs Reading Scores](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/Resources/Grade%20level%20v%20Reading%20Scores.PNG?raw=true)

## Summary
Factors that have probable correlation to the percentage of students who pass are:
- Small and medium sized schools outperform schools over 2000 students.
- Charter schools outperform District schools.
  - Of import, charter schools tend to have fewer students.
- Math programs have lower scores than Reading programs at all schools. 
- To markedly boost overall performance, funnel more attention toward the Math programs.

---
To review the complete dataset please follow this link: [School District Analysis](https://github.com/emilymcdaniel/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

