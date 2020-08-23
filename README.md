# School District Analysis
## Purpose
A school board revealed that a file (students_complete.csv) showed evidence of academic dishonesty in the 9th grade reading and math scores from Thomas High School. 
An analysis was done to see the full extent of this academic dishonesty. To perform the analysis, the 9th grade values were nulled to see how the district summary would be affected. 

## Method 
To show a difference between the two datasets: one with the 9th graders, and one not including the ninth graders, I ran two PyCity Jupyter Notebooks. One, I included the 9-12th grade values, and in one only the 10-12th grade values were looked at. Below, I will be posting the differences I found in the two notebooks. First image will always represent the findings including 9th graders and the following picture will show the chart without the 9th graders. 

## Results
### How is the district summary affected?
When the 9th grade values are nulled, district summary shows Thomas High School to show approximately 65% passing rate. This is because the values for 9th graders are still being counted, but they are counted as 0, bringing the overall grades of the school down. 

### How is the school summary affected?
When the grades 10-12 are only being analyzed, the percentage increases to almost 91%. This is because 9th graders are not being counted in the total for the new analysis.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School did better compared to other schools when ninth graders's overall passing grades were included into the analysis.
Thomas High School before and after replacing ninth graders' math scores: 

This is before and after replacing reading scores:

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
Math: 
![Math_with_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/Resources/THS_grade_math_ninth.png?raw=true)
### Scores by school spending
Remains the same.

### Scores by school size
Remains the same. 

### Scores by school type
Remains the same 

### Four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
