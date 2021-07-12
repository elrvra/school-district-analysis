# PyCitySchools with Pandas

## Overview of School District Analysis:

### Purpose of this Analysis
Maria, the chief data scientist for a city school district is responsible for analyzing information from a variety of sources and in a variety of formats. In this role, she is tasked for preparing all standardized test data for analysis, reporting, and presentation to provide insight about performance trends and patterns. These insights are used to inform discussions and strategic decisions at the school and district level. I will start by helping Maria analyze data on student funding and student’s standardized test scores. I was given access to every student’s math and reading scores as well as various information on the schools they attend. I’ve been task is to aggregate the data and showcase trends in school performance. This analysis will assist the school board and super intendent in making decisions regarding the school budgets and priorities. 

Additionally, the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I’ve replaced the math and reading scores, Maria would like me to repeat the school district analysis that I did for her and write up a report to describe how these changes affected the overall analysis.

## Results:

### Bulleted list that addresses how each school district metrics was affected by the changes in the data
- Total Students = 39,170 (before data cleanup) to 38,709 (after data cleanup)
- Average Math Score = 79.0 (before data cleanup) to 78.9 (after data cleanup)
- Average Reading Score = 81.9 (before data cleanup) to 81.9 (after data cleanup)
- % Passing Math = 75 (before data cleanup) to 74.8 (after data cleanup)
- % Passing Reading = 86 (before data cleanup) to 85.7 (after data cleanup)
- % Overall Passing = 65 (before data cleanup) to 64.9 (after data cleanup)

## Summary:

### Statement that summarizes four changes to the school district analysis after reading & math scores have been replaced
Prior to the data cleanup of the school district, there was a total of 39,170 students. Additionally, there was a slight change in the Average Math Score, % Padding Math, % Passing Reading, and % Overall Passing data points before and after ignoring Thomas High School (THS)'s 9th grade students. This is because the average scores in both math and reading were quit similar with a less than 1% difference. 