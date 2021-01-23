# Challenge 4: School District Analysis

## Overview of The School District Analysis
This analysis is in response to a school board request to assess the impact of possible academic dishonesty in the grades reported for 9th grade class at Thomas High School. The school board wants to know the full extent of the academic dishonesty, so as to uphold the state-testing standards. Baseline statistics will be generated from the provided school data file. Then, the Thomas High School 9th grade values will be removed, and the analysis repeated, and then compared with the original results.

The Jupyter notebooks used for this analysis are:
* Baseline Results: [Challenge Baseline.ipynb](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Challenge%20Baseline.ipynb). The analysis was conducted using all the provided school data.
* Cleansed Results: [PyCitySchools_Challenge.ipynb](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb). The analysis was conducted with the math and reading scores for Thomas High School 9th graders removed.


The report below summarizes the findings as a result of the analysis.
## School District Analysis Results
### District Summary
This analysis displays totals and averages for all schools and all grades.
| Baseline Results | 
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/District%20Summary%20Baseline.png) | 

| Cleansed Results |
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/District%20Summary%20THS%20Nine%20Removed.png) |

### School Summary
This analysis displays totals and averages for all grades broken down by school. 
| Baseline Results | 
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/School%20Summary%20Baseline.png) | 

| Cleansed Results |
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/School%20Summary%20THS%20Nine%20Removed.png) |

Note: The percentage passing values for Thomas High School in the "Cleansed Dataset" are significantly lower since all grade nine students didn't have a math grade or a reading grade. 
### Math Scores By Grade
This analysis displays math averages by grade and by school with a per grade average for all schools in the final row.
| Baseline Results| Cleansed Results |
| --------------- | ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/Baseline%20Math%20by%20Grade%20.png) | ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/Math%20by%20Grade%20THS%20Nine%20Removed.png) |
### Reading Scores By Grade
This analysis displays reading averages by grade and by school with a per grade average for all schools in the final row.
| Baseline Results| Cleansed Results |
| --------------- | ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/Baseline%20Reading%20By%20Grade.png) | ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/Reading%20By%20Grade%20THS%20Nine%20Removed.png) |
### Scores By School Spending 
This analysis displays the math and reading scores and percentages by spending ranges. 
| Baseline Results | 
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/Spending%20Summary%20Baseline.png) | 

| Cleansed Results |
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/Spending%20Summary%20THS%20Nine%20Removed.png) |
### Scores By School Size
This analysis displays the math and reading scores and percentages by school sizes.
| Baseline Results | 
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/School%20Size%20Baseline.png) | 

| Cleansed Results |
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/School%20Size%20THS%20Nine%20Removed.png) |

### Scores By School Type 
This analysis displays the math and reading scores and percentages by school types.
| Baseline Results | 
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/School%20Type%20Baseline.png) | 

| Cleansed Results |
| ---------------- |
| ![](https://github.com/Hala-INTJ/School_District_Analysis/blob/main/Resources/School%20Type%20THS%20Nine%20Removed.png) |

## School District Analysis Summary
1. In the "District Summary", the average reading score was unchanged but the average math score dropped by 0.1% after removing Thomas High School math grades for grade 9 students.
2. In the "School Summary", the Thomas High School average math score went down by 0.07% and the average reading score went up by 0.05%.
3. In the "Math Scores By Grade", the average math score for grade 9 for all schools decreased by 0.26%. 
4. In the "Reading Scores By Grade", the average reading score for grade 9 for all schools decreased by 0.08%.
5. There were no differences in the average math or reading scores for "Scores By School Spending", "Scores By School Size" and "Scores By School Type".

### Analysis Conclusion 
It does not appear, given the very small variations in the results, that there is any evidence of academic dishonesty with regards to the math and reading scores for Thomas High School 9th graders. 