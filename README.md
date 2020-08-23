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

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
With math scores, the difference was that the score decreased slightly.
With reading scores, the difference was that the score increased slightly. 

![Math_with_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/math_school_ninth.png?raw=true)

![Math_without_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/math_school_no_ninth.png?raw=true)

![Reading_with_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/reading_school_ninth.png?raw=true)

![Reading_without_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/reading_school_no_ninth.png?raw=true)

### Scores by school spending
There was no change. 

![Spending_with_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/Resources/spending_ninth.png?raw=true)

![Spending_without_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/Resources/spending_no_ninth.png?raw=true)

### Scores by school size
Overall, math percentage increased, reading percentage decreased. 

![Size_with_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/Resources/size_ninth.png?raw=true)

![Size_without_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/Resources/size_no_ninth.png?raw=true)

### Scores by school type
There was no significant change in the school type.
![type_with_ninth](https://github.com/pratishthasingh1/School_District_Analysis/blob/master/Resources/type.png?raw=true)

### Four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. 9th graders were no longer being counted, which means their scores were being inputed as "0"
2. Total values were skewed because 9th graders still had student names that were being counted, so the percentage decreased.
3. Once the total values were edited to only have 10-12th graders, the percentage went back to a value that made sense.
4. District and school summary showed the biggest differences, otherwise within each category, the overall passing percentage was also affected significantly.
