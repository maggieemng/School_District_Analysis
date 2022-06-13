# School_District_Analysis
## Overview: 
The purpose of this analysis is to utilize student/school data to find out various different metrics in regards to school performance and test scoring for the district. However, later on it is known that there has been academic dishonesty, specifically for the grades of Thomas High School 9th graders. As such, we had to remove their scores and recalculate all the different metrics to get to a more accurate representation. 

## Results:
###### How is the district summary affected?

Per comparison of "PyCitySchools.ipynb" and "PyCitySchools_Challenge.ipynb", it is noted that there is no difference between the two and thus the district summary had not been affected by the academic dishonesty. 

###### How is the school summary affected?

The Overall Passing % for Thomas High School in "PyCitySchools.ipynb" is 90.9%, and the Overall Passing % for Thomas High School in "PyCitySchools_Challenge.ipynb" is 65.1% when taking into account all 4 grades population, which is a pretty large decline of 25.8%. However, the difference is only 90.6% when calculated using population omitting 9th graders, which is also the ultimate %. Which means that omitting values for Thomas High School 9th graders only changed the overall passing % by -0.3%.

###### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

It did not make a material difference.

###### How does replacing the ninth-grade scores affect the following:

###### Math and reading scores by grade - 

No change except for that for Thomas High School 9th grade the values are all "NaN" now. 

###### Scores by school spending - 

Nothing changed. 

###### Scores by school size - 

Nothing changed. 

###### Scores by school type - 

Nothing changed. 

## Summary: 
Overall the school district analysis changes include: Thomas High School 9th grade math and reading values to become "NaN", Thomas High School %s to change slightly (but not enough to make a big difference for the overall analysis project), Total number of useable values for Thomas High School to decline, and total overall number of data points in this project. However, after comparison, there are not many differences despite the changes from this issue. 
