# Module 4 Challenge: Analyzing School District Data Using Pandas

#### Colin Brineman, M.A.

## Objective

### Overview
The objective of this project was to assist Maria, who is a data analyst for a school board, to prepare statistics summarizing students' standardized test performances, using Pandas.

### Purpose
Maria will present her analysis to the school board, so that they can compare how well the district is educating students across different schools and inform a strategy to address potential achievement gaps.

### Challenge
During the course of the module, I had already prepared all the necessary statistical tables, but due to suspected academic dishonesty, Maria tasked me with rerunning the analysis after removing Thomas High School 9th grade reading and math scores from the data.
    
## Results
I mention below only those statistical tables which have been affected by the removal of the tainted test scores. All other data should be assumed unchanged.

* District summary:
    - Average math score decreased by 0.1 points.
    - Percentage passing math decreased by 0.2%.
    - Percentage passing reading decreased by 0.1%.
    - Percentage overall passing decreased by 0.3%.

#### Fig. 1.1: Old District Summary
![Fig. 1.1: Old District Summary](/resources/Fig_1.1_Old_District_Summary.png)

#### Fig. 1.2: New District Summary
![Fig. 1.2: New District Summary](/resources/Fig_1.2_New_District_Summary.png)

* School summary
    - Thomas High School's average reading score increased by 0.1 points.
    - Thomas High School's percentage passing math decreased by 0.1%.
    - Thomas High School's percentage passing reading decreased by 0.3%.
    - Thomas High School's percentage overall passing decreased 0.3%.

#### Fig 2.1: Old School Summary
![Fig 2.1: Old School Summary](/resources/Fig_2.1_Old_School_Summary.png)

#### Fig 2.2: New School Summary
![Fig 2.2: New School Summary](/resources/Fig_2.2_New_School_Summary.png)

* High-performing and low-performing schools summary
    - Top-5 highest-performing schools' ranking was unaffected. Thomas High School remains the 2nd-highest-performing school in the district.
    - Bottom-5 lowest-performing schools' ranking was unaffected.

* Scores by grade per school
    - Thomas High School 9th grade average math scores were dropped from the table and replaced with "nan."
    - Thomas High School 9th grade average reading scores were dropped from the table and replaced with "nan."

* Scores by school spending
    - Average math and reading scores by school spending were unaffected.

* Scores by school size
    - Average math and reading scores by school size were unaffected.

* Scores by school type
    - Average math and reading scores by school type were unaffected.

## Summary
Manipulation of test scores is always a cause for alarm — especially for the students who may be adversely impacted. Fortunately, however, it appears that whatever manipulation of Thomas High School 9th grade reading and math scores did occur was relatively insignificant, as no aspect of our analysis was seriously affected by removing the tainted scores. The largest change in any particular summary statistic was well under 1%.